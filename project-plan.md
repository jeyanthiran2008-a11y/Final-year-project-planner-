# Project Plan — Capstone 39

## 1. Project overview
**Title:** Final-Year Project Planner and Report Assistant  
**Target audience:** Final-year CSE project teams  
**Problem:** Student teams may find it difficult to compare project ideas, estimate feasibility, organize milestones, draft report sections, and create consistent weekly updates.  
**Proposed solution:** A static browser application that provides a feasibility scorecard, milestone plan, note-based report templates, weekly status-report automation, and a readiness checklist.

## 2. Objectives
1. Provide a transparent way to compare ten sample ideas.
2. Help teams record scope, objectives, milestones, and risks.
3. Structure report drafts from student-supplied notes.
4. Convert weekly notes into a categorized status report.
5. Encourage source verification, citation, plagiarism checks, and disclosure of AI assistance.

## 3. Scope
**Included:** local browser app; no sign-in; template-based drafting; editable scorecard; checklist; text/JSON export.  
**Not included:** cloud storage, team collaboration, live AI API, plagiarism-detection engine, or automatic validation of citations.

## 4. Proposed technology
- HTML for structure
- CSS for responsive presentation
- Vanilla JavaScript for scoring, templates, local checklist state, and exports
- JSON and Markdown for project records and documentation

## 5. Milestones
| Week | Activity | Evidence |
|---|---|---|
| 1 | Define problem, audience, and requirements | Approved problem statement |
| 2 | Review official guidelines and related sources | Source log and research summary |
| 3 | Evaluate project ideas and risks | Scorecard |
| 4 | Design app and data flow | Architecture sketch |
| 5 | Build app modules | Working prototype |
| 6 | Run manual tests and record defects | Test log |
| 7 | Prepare report and review slides | Report draft and slide outline |
| 8 | Final demo, feedback, and revisions | Demo evidence and supervisor feedback |

**[STUDENT TO COMPLETE]** Replace the indicative eight-week schedule with the institution's actual dates and assigned team members.

## 6. Risks and mitigation
| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| Incorrect or fabricated AI-generated claims | Medium | High | Verify against original sources; record uncertainty |
| Plagiarism or missing citations | Medium | High | Cite sources, rewrite independently, follow college policy |
| Scope too large | Medium | Medium | Keep the initial app static and focused |
| Lost local browser state | Medium | Medium | Export project JSON regularly |
| Misclassified weekly notes | Medium | Medium | Human review before sharing |
| Accessibility problems | Medium | Medium | Keyboard, labels, contrast, and mobile checks |

## 7. Acceptance criteria
- User can edit scores for ten ideas and see a weighted score.
- User can enter project details and see milestone rows.
- User can draft a section from their own notes.
- User can turn notes into categorized weekly status output.
- User can tick checklist items and see completion percentage.
- User can export JSON and text reports.
- Main workflows work in a modern desktop and mobile browser.

## 8. Ethics and privacy
The prototype runs in the browser and does not send information to a server. Students should not enter sensitive personal data. Verify claims, cite original sources, disclose AI assistance, and do not represent template text as original research.
