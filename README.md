# GitHub Issues Flow

A repository created to describe one method of using GitHub Issues within development workflows.

<img src="https://github.com/DenisUstinov/github-issues-flow/blob/main/github-issues-flow.png" width="100%" />

---

## Weekly Sprint  
**Label:** ![weekly](https://img.shields.io/badge/weekly-1d76db?style=flat&color=1d76db)

Created every Monday.  
Title: **Weekly Sprint**  
Textarea:

## Planning

### Sprint goal
A short weekly goal and the expected result.

### Tasks for the week
Numbered by priority.

### Notes
Additional remarks.

During the week, all daily issues are marked as belonging to the current Weekly Sprint.

Examples:  
- **1st Weekly Sprint:** https://github.com/DenisUstinov/github-issues-flow/issues/1  
- **2nd Weekly Sprint:** https://github.com/DenisUstinov/github-issues-flow/issues/6

At the end of the week, add a comment to the Weekly Sprint:

## Retrospective

### Problems and difficulties
Main problems of the week.

### Conclusions and improvements
Conclusions and improvements.

## Sprint results

### Were the sprint goals achieved
A brief assessment of goal completion.

Based on this comment, create the next Weekly Sprint and close the current one.

---

## Daily Stand-Up  
**Label:** ![daily](https://img.shields.io/badge/daily-c5def5?style=flat&color=c5def5)

Created every day based on the previous day's comment.  
Title: **Daily Stand-Up YYYY-MM-DD**  
Textarea:

## What I plan to do?
Numbered tasks for the day.

Examples:  
- **1st Daily Stand-Up:** https://github.com/DenisUstinov/github-issues-flow/issues/2  
- **2nd Daily Stand-Up:** https://github.com/DenisUstinov/github-issues-flow/issues/4

At the end of the day, add a comment:

## What has been done?
Actual results of the day.

## Blockers and difficulties
Daily problems in priority order.

Based on this comment, create the next Daily Stand-Up.

---

## Work Tasks (units of work)

Created from a Daily Stand-Up as sub-issues.  
Title: short, e.g., **Add .gitignore**  
Textarea: one-sentence explanation (“what” and “why”).  
Milestone/Project: if needed.  
Closed when completed.

**Task-type labels with colors:**

- ![blocked](https://img.shields.io/badge/blocked-b60205?style=flat&color=b60205)
- ![chore](https://img.shields.io/badge/chore-C0C0C0?style=flat&color=C0C0C0)
- ![docs](https://img.shields.io/badge/docs-006b75?style=flat&color=006b75)
- ![feat](https://img.shields.io/badge/feat-0e8a16?style=flat&color=0e8a16)
- ![performance](https://img.shields.io/badge/performance-0052cc?style=flat&color=0052cc)
- ![refactor](https://img.shields.io/badge/refactor-635961?style=flat&color=635961)
- ![review](https://img.shields.io/badge/review-e99695?style=flat&color=e99695)
- ![security](https://img.shields.io/badge/security-b60205?style=flat&color=b60205)
- ![test](https://img.shields.io/badge/test-fbca04?style=flat&color=fbca04)

Examples:  
- **Task of Day 1, Weekly Sprint 1:** https://github.com/DenisUstinov/github-issues-flow/issues/3  
- **Task of Day 2, Weekly Sprint 1:** https://github.com/DenisUstinov/github-issues-flow/issues/5

---

## Summary

This creates two continuous chains:  

- Weekly Sprint → next Weekly Sprint  
- Daily Stand-Up → next Daily Stand-Up  

And individual work tasks that are simply completed and closed.
