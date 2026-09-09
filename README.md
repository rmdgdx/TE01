# TE01 · Astronomy Project Development and Management

Course website for **TE01 — Astronomy Project Development and Management**
(BS Astronomy, Department of Earth and Space Sciences, College of Arts and Sciences,
Rizal Technological University) · First Semester, AY 2026–2027 ·
Assoc. Prof. Ryan Manuel D. Guido, Ph.D.

## Contents

| File | What it is |
|---|---|
| `index.html` | **Landing page** — the enhanced course syllabus, with a Course Materials section linking every chapter pack |
| `ch1-lecture.html` … `ch7-lecture.html` | Chapter lecture packs: annotated lectures, framework figures, 20-item HOTS mastery tests with answer dropdowns, linked primary sources |
| `ch1-reinforcement.html` … `ch7-reinforcement.html` | Reinforcement sets: 20 fresh HOTS multiple-choice items + 3 HOTS essays with model answers |

All pages are single-file, self-contained HTML (no external assets or build step) —
they work offline, render on any device, and print cleanly.

## Publishing with GitHub Pages

1. Create a new repository (e.g. `te01`) on your GitHub account.
2. Upload the contents of this folder to the repository root — either
   drag-and-drop on the GitHub website (*Add file → Upload files*) or:

   ```bash
   git remote add origin https://github.com/<your-username>/te01.git
   git push -u origin main
   ```

3. In the repository: **Settings → Pages → Build and deployment** —
   Source: *Deploy from a branch*, Branch: `main`, Folder: `/ (root)`. Save.
4. The site goes live at `https://<your-username>.github.io/te01/`,
   with the syllabus as the landing page.

## Chapter map

1. Overview of Research Methods and Design Principles *(Week 1)*
2. International and National Research Agendas and Country Development Plans *(Week 2)*
3. Philippine Laws on Science-Related Government Agencies *(Weeks 3–4)*
4. Environmental Legislation and Maritime Jurisdiction *(Weeks 5–6)*
5. Intellectual Property and Technology Transfer *(Weeks 8–9)*
6. R&D Project Management: Budgeting and M&E *(Weeks 8–9)*
7. Principles of R&D Management and the Magna Carta for S&T Personnel *(Week 10)*

Weeks 7, 11, and 18 are assessment milestones (Long Quiz 1 · Midterm ·
Final Presentation and Innovative Pitching). Chapters 8–9 (Research Agenda
Development · Proposal Crafting & Innovative Pitching) will be added on release.
