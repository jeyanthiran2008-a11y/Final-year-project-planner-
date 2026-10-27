# Capstone 39 — Final-Year Project Planner and Report Assistant

A beginner-friendly, browser-based project planning assistant for final-year CSE teams. It helps students shortlist project ideas, score feasibility, plan milestones, draft technical report sections from their own notes, check report readiness, and turn weekly progress notes into a status report.

> **Important:** This is a student support tool, not a source of verified academic facts. Verify all references, technical claims, dates, and generated text. Do not submit AI-generated writing as your own without following your institution's rules.

## Features
- 10 sample project ideas with a transparent feasibility scorecard
- Editable project details and milestone plan
- Report-section drafting from student-provided notes
- Project readiness and report-quality checklist
- Weekly notes → status report automation
- Prompt library, verification log, before/after example, viva quiz, and presentation outline
- Runs locally in a web browser; no account, server, API key, or installation required

## Run the app
1. Download or clone this repository.
2. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.
3. Enter your project details and try each tab.
4. Use **Export report** or **Export project data** to save your work.

All processing happens in your browser. The app does not call an AI service; report drafting is template-based. If you use an external AI tool as part of the assignment, document the tool, prompt, output, and verification separately.

## Repository structure
- `index.html` — app interface
- `styles.css` — responsive styles
- `app.js` — app logic, scorecard, report draft, checklist, and weekly status automation
- `docs/` — project plan, research summary, report draft, verification report, ethics, and demo script
- `data/` — example notes and scorecard data
- `prompts/` — reusable prompts and usage notes
- `presentation/` — 7-slide review deck outline
- `tests/` — manual test plan and results template

## GitHub upload
Create a new repository on GitHub, then upload the files and folders in this ZIP. Keep the folder structure intact. Alternatively, extract the ZIP, open a terminal in the extracted folder, and run:

```bash
git init
git add .
git commit -m "Add Capstone 39 project planner"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the example URL with your own repository URL.

## Project status
This package is a complete starter submission package. Items marked **[STUDENT TO COMPLETE]** require your own real research, actual testing, team details, and institution-specific information. Do not claim tests or research were completed unless you performed them.
