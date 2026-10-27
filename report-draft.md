# Project Report Draft — Capstone 39

> **Draft only.** Complete all student placeholders, insert actual screenshots and test evidence, add verified citations, and follow your department's template. Do not claim unperformed research or tests.

## Title
Final-Year Project Planner and Report Assistant

## Abstract
Final-year CSE teams need to select a manageable project, coordinate milestones, and produce clear documentation. This project proposes a lightweight browser-based assistant that structures these activities using a project-idea scorecard, editable milestone plan, report-section templates, weekly progress-note automation, and a readiness checklist. The prototype is built with HTML, CSS, and vanilla JavaScript and runs locally in a modern browser. Its report drafting feature uses student-provided notes and fixed templates rather than an external AI service. The approach is intended to improve organization and make verification tasks visible; it does not independently validate sources or guarantee academic quality.

**[STUDENT TO COMPLETE]** Add actual evaluation method, measured results, limitations, and keywords after testing.

## 1. Introduction
### 1.1 Background
A capstone project requires students to make scope decisions, review related work, manage milestones, test a solution, and communicate results. Keeping these activities in separate documents can make progress difficult to track.

### 1.2 Problem statement
Teams need a simple structure for comparing project ideas and keeping planning, reporting, and progress updates organized.

### 1.3 Objectives
- Compare candidate project ideas using a transparent scorecard.
- Record project objectives and milestone evidence.
- Structure report sections from the team's own notes.
- Convert weekly notes into a reviewable status report.
- Provide a readiness checklist for verification and ethical use.

### 1.4 Scope and limitations
The prototype is a static, local browser app. It has no login, shared database, external AI integration, automatic plagiarism detector, or citation verification service.

## 2. Literature Review
**[STUDENT TO COMPLETE]** Summarize at least three reliable sources. Compare their purpose, method, findings, and limitations. Explain how the evidence informs this project's design. Add verified citations in the citation style required by your institution.

## 3. Requirements and Design
### 3.1 Functional requirements
1. Display ten example project ideas.
2. Allow feasibility, impact, and risk scores from 1 to 5.
3. Calculate a weighted score.
4. Capture title, team, supervisor, due date, problem, and objective.
5. Display a milestone plan.
6. Generate a section outline from user notes.
7. Categorize weekly notes into progress, next steps, blockers, and other notes.
8. Track readiness checklist completion.
9. Export project data as JSON and drafts as text.

### 3.2 Non-functional requirements
- Usable on desktop and mobile browsers.
- No server required for the prototype.
- Labels and keyboard-operable controls.
- Clear warnings that outputs need human review.
- Simple, maintainable source code.

### 3.3 Architecture
The app uses a client-only architecture: HTML presents the controls, CSS handles responsive layout, and JavaScript processes the scorecard, templates, checklist, and exports. Checklist state is stored in browser local storage. No information is sent to a server.

**[STUDENT TO COMPLETE]** Add your own architecture diagram and screenshots of the running application.

## 4. Implementation
The implementation is split into five interface areas: idea scorecard, project plan, report assistant, weekly automation, and readiness checklist. The scorecard calculates a weighted score from feasibility, impact, and inverse risk. The report assistant inserts notes into a predefined section structure. Weekly automation uses keyword rules to categorize lines; therefore, the categorization may be imperfect and must be checked by a person.

## 5. Testing and Evaluation
**[STUDENT TO COMPLETE]** Run the tests in `tests/test-plan.md` and enter real outcomes. Include browser/device, date, expected behavior, observed behavior, pass/fail, and evidence. Evaluate whether the weekly-note categories are accurate on several examples. Do not report hypothetical results as actual results.

## 6. Ethical Considerations
The application should support planning rather than replace student learning. Users must verify facts, cite original sources, disclose AI assistance as required, and follow the institution's academic-integrity policy. The app's output should not be submitted unchanged as a student's original work.

## 7. Conclusion and Future Work
The prototype provides a basic structure for project planning and reporting. Its value must be assessed through actual user testing and supervisor feedback. Future improvements could include collaborative storage, configurable rubrics, accessibility testing, and optional AI integration with privacy and verification safeguards.

## References
**[STUDENT TO COMPLETE]** Add only sources you actually read and verified. Check author, title, year, DOI/URL, and required citation format.
