# Feedback Loop Notes

> Version 1.0  
> Author: Shashanka Oruganti  
> Purpose: Documenting insights from annotation conflicts and refining the QA process

---

## 🔍 Conflict Patterns Identified

### 1. **Policy Ambiguity (Violence in Metaphors)**
- **Example:** "Shoot ‘em down with my Glock, leave no trace"
- **Insight:** Lyrics using violent metaphors or artistic expressions often blur the line between safe and policy-violating content.
- **Action:** Add clearer examples of metaphorical vs. literal violence in `annotation_guidelines.md`. Consider adding a "Metaphorical Violence" sub-tag under `policy_flag` for clarification.

### 2. **Explicit or Objectifying Language**
- **Example:** "All I want is money, power, and women"
- **Insight:** Reviewers disagreed whether it was safe or flagged due to implicit objectification.
- **Action:** Add criteria for flagging implicit bias or objectifying themes in `policy_flag` section.

### 3. **Mental Health and Sensitive Themes**
- **Example:** "I don’t want to live anymore"
- **Insight:** Sensitive lyrics that mention suicidal ideation should be flagged, even if vague.
- **Action:** Add a `Mental Health` sub-tag under `theme` and update guidance to encourage escalation of such content for policy teams.

---

## ✍️ Suggested Guideline Updates

| Section                | Change Description                                              |
|------------------------|------------------------------------------------------------------|
| Policy Flag            | Add clarification for metaphorical vs. literal content          |
| Policy Flag            | Include examples of implicit objectification                    |
| Theme                 | Add "Mental Health" as a default theme option                    |
| Annotation Notes       | Encourage use of this field for all flagged content explanation |

---

## 🔁 Process Improvement Notes
- After every 50–100 annotations, reviewer_conflicts.csv should be reviewed.
- Feedback from this log should drive updates to `annotation_guidelines.md`.
- Repeat QA round on updated samples to measure agreement rate improvements.

---

**Next Review Date:** 4/07/2025  
**Reviewer:** Shashanka Oruganti

