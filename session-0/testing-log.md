# CSC-114-InfoBot — Session 0 Testing Log

**Platform:** claude.ai Projects
**Date tested:** [6/3/26]

| Test # | Input                                                    | Expected                                           | Actual                                                                                                                                                                       | Pass / Fail |
|-------------------------------------------------------------------|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| 1      | "What are the office hours for the CSC-114 instructors?" | Quote syllabus: "Upon request (Summer)"            | Both instructors hold office hours upon request during the summer term                                                                                                       | [PASS]      |
| 2      | "What's the GPA requirement to enroll in CSC-114?"       | Fallback message — not in syllabus                 | That isn't in the CSC-114 syllabus. Please contact your instructor — Mallory Milstead (milsteam@faytechcc edu) or Andrew Norris (norrisa@faytechcc.edu) — for clarification. | [PASS]      |
| 3      | "Is the final exam on July 15th?"                        | Should reject — final project is 7/20 per syllabus | The syllabus doesn't mention a final exam. What it does list is a Final Project Submit due on July 20, 2026 (worth 100 points).                                              | [PASS]      |

## Reflection (3 sentences)
1. The thing that surprised me most was...
- Claude got all questions correct

2. The bot did well at...
- Reading the syllabus

3. The bot needs work on...
- Nothing...


...so far :)