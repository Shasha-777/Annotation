# Annotation Guidelines for Song Lyrics Project

These guidelines are designed to ensure consistent and accurate annotation of song lyrics. They simulate a real-world annotation QA workflow such as those used at companies like Spotify, Amazon, and YouTube.

---

## 🎯 Objective
To label each lyric sample based on four dimensions:
- **Genre (Verified)**
- **Sentiment**
- **Policy Flag**
- **Theme**

These annotations will support content understanding, safety checks, and recommendation systems.

---

## ✅ 1. Genre (Verified)
**Definition:** The music genre as interpreted from the lyrical content, tone, and listed tag.

### Options:
- Rap
- Pop
- R&B
- Rock
- Country
- Folk
- Electronic
- Unknown

### Guidelines:
- Use the genre listed in the original `tag` column as a reference.
- If lyrics clearly align with another genre (e.g., acoustic or country style), modify accordingly.
- If genre is unclear, mark as `Unknown`.

---

## 2. Sentiment
**Definition:** Emotional tone conveyed through the lyrics.

### Options:
- Positive
- Neutral
- Negative

### Examples:
- **Positive:** Lyrics about love, joy, success, motivation.  
  _"I’m the greatest, no one can stop me."_
- **Neutral:** Descriptive or storytelling lyrics without strong emotion.  
  _"She walked down the road and saw the moonlight."_
- **Negative:** Lyrics about pain, anger, heartbreak, threats.  
  _"I don’t want to live anymore."_

---

## 🚨 3. Policy Flag
**Definition:** Whether the lyrics violate general platform safety policies (Spotify, YouTube, etc.)

### Options:
- Safe
- Flagged

### Flagged Criteria:
- Hate speech or slurs
- Threats of violence
- Explicit drug use
- Graphic sexual content
- Harassment or bullying

> *If in doubt, mark as "Flagged" and explain in annotation_notes.*

### Examples:
- **Safe:** _"I’m flying high with my dreams in sight."_
- **Flagged:** _"Shoot ‘em down with my Glock, leave no trace behind."_

---

## 4. Theme
**Definition:** The core message or topic the lyrics explore.

### Common Themes:
- Love
- Heartbreak
- Violence
- Motivation
- Struggle
- Wealth
- Empowerment
- Mental Health
- Party
- Social Commentary

### Guidelines:
- Choose the most prominent theme.
- If multiple themes are present, choose the one that dominates the message.
- If unclear, write explanation in annotation_notes.

---

## 📝 Annotation Notes
**Purpose:** Add reasoning or flag ambiguity.

Examples:
- “Unclear if lyrics are violent or metaphorical”
- “Mentions drugs but not in a glorifying way”
- “Lyrics feel more motivational than romantic”

---

## 🔄 Review & Feedback
- Revisit guidelines after every 50–100 annotations.
- Log common edge cases in `reviewer_conflicts.csv`
- Suggest updates to this document in `feedback_loop_notes.md`

---

**End of Guidelines**

> Version: 1.0  
> Created by: Shashanka Oruganti  
> Last updated: [Insert Date]
