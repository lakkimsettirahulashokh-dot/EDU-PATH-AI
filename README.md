# EduPath AI

**Your learning and career command center**

A student workspace for exploring careers, planning learning, analyzing study PDFs and preparing for interviews.

## Features
- Career explorer with role profiles and skill suggestions
- Self-assessment questionnaire with transparent scoring
- Editable learning roadmap and study task planner
- PDF text extraction, topic clues, notes and practice-question prompts
- Mock interview question bank with self-review rubric
- Resume builder with print-to-PDF
- Sample scholarship directory and progress dashboard

## Technology
- HTML5, CSS3 and Vanilla JavaScript
- Browser `localStorage` for local persistence
- No API keys, backend, server-side code or database
- No build step or package installation required

## Run locally
1. Extract this ZIP.
2. Open `index.html` in a modern browser.
3. If your browser restricts local file behavior, run a static server from this folder:
   - `python -m http.server 8000`
   - Open `http://localhost:8000`

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site.

## Privacy and storage
- User-created entries are stored in this browser's local storage.
- Data does not sync between users or devices.
- Clearing site data may remove saved entries. Use **Export data** to download a backup.
- Do not enter highly sensitive personal information.

## Important limitations
Career suggestions and study feedback are rule-based learning aids, not professional placement advice. Scholarship entries are sample records and must be verified.
- This is a hackathon prototype, not an official public service.
- It uses deterministic browser-side logic, not a cloud AI model.
- Some content is illustrative sample content and must be independently verified.
- PDF Analyzer supports selectable text in many PDFs using a lightweight browser-side parser; scanned/image-only or complex encrypted PDFs may not extract correctly. OCR is not included.
- Google Fonts are an optional external styling resource; the site falls back to system fonts if unavailable.

## Suggested GitHub repository description
Your learning and career command center — a responsive, local-first hackathon prototype built with HTML, CSS and JavaScript.

## Test checklist
- [ ] Open the site on desktop and mobile widths.
- [ ] Navigate through every module.
- [ ] Add a record or task, refresh, and confirm local persistence.
- [ ] Export a JSON backup.
- [ ] Test with a selectable-text PDF if using the PDF Analyzer.
- [ ] Confirm that demo and sample data are clearly labelled.
