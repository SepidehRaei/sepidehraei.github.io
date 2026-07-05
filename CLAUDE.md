# CLAUDE.md — Sepideh Raei personal academic website

Static hand-built site (no frameworks, no build step): `index.html`, `research.html`,
`teaching.html`, `cv.html`, one stylesheet `css/style.css`, PDFs in `files/`, photo in
`images/profile.png`. GitHub Pages. Branches: `main` = original live site, `dev1` = redesign
for A/B test against main. Work on `dev1`.

## Redesign brief (July 2026)

Model site: https://pjalgotrader.github.io (Pedram Jahangiry, USU). Traits adopted:
tagline hook in hero, numbered sections (§ 01 …), credential badges, CTA buttons,
typography-driven minimalism (serif display + sans body), social/footer icon links.
Also inspired by clean macro-economist sites (Pascal Michaillat style): papers grouped
by theme, generous whitespace, clear link chips.

User requests:
- Research page: feature every paper with a short **hook** (punchy 1–2 sentences, NOT the
  abstract); keep abstracts collapsible. Group by research theme.
- Teaching page: short appealing teaching-philosophy paragraph, per-course summaries,
  feature courses and awards prominently.
- Omit the generic tagline "macroeconomist working in taxation and public finance and
  modeling" — use something with more personality.
- A/B test: keep same file names/structure as main so pages are comparable.

## Distilled tenure-package facts (source: "Portfolio Overview - Sepideh Raei.pdf", Fall 2024)

Package path (Google Drive, additional working dir):
`.../TAC committee/Tenure Package - Summer 2024/` — Portfolio Overview PDF is the master
summary; individual paper PDFs in `Papers/`; syllabi in `teaching appendix/`
(1500_syl.pdf, 4020_syl.pdf); teaching evals: IDEA*.pdf, eval_excel.png, citation.jpg.
No need to re-read the bulky package — everything relevant is below.

### Profile
- Associate Professor of Economics, Dept. of Economics and Finance, Huntsman School of
  Business, USU. At USU since Fall 2018. PhD Economics, Arizona State University.
- Role: 50% teaching, 40% research, 10% service.
- Fields: Macroeconomics, Public Finance. Research question: how tax systems and public
  policy shape behavior of households, firms, and banks; method = structural models +
  empirics + counterfactual policy experiments.
- Office 606 Eccles Business Building, sepideh.raei@usu.edu, 435-797-2321.

### Teaching (for teaching.html)
- Highlights: 1,100+ students in 6 yrs; Teacher of the Year (E&F Dept) 2022; Undergraduate
  Faculty Mentor of the Year 2020; ETE Teaching Scholar Certificate 2022; AEA Summer
  Fellowship (Washington Center for Equitable Growth) 2023; GTA award ASU 2014–16;
  developed 3 courses (ECN1500, ECN4020, USU1010); mentored 10+ Undergraduate Teaching
  Fellows; chaired 1 MS thesis; avg "Excellent teacher" eval 4.5/5.
- ECN 1500 Intro to Economic Institutions, History & Principles: Gen-Ed, ~75/section,
  fall+spring, plus advanced Huntsman Scholar section (~50).
- ECN 4020 Intermediate Macroeconomics: spring, ~25 students, required for econ major/minor.
- USU 1010 Connections: first-year transition course (Fall 2023).
- Philosophy pillars: (1) ethics of care — learns all names by day 2, personalized praise
  emails, students feel seen; (2) rigor — "everybody is a genius" multiple-intelligences
  framing, critical thinking over memorization; (3) motivation — every lecture opens with a
  real-world puzzle (e.g. "is the economy growing?" → GDP). Goal: lifelong learners.
- Student quotes available in portfolio (used on teaching page).

### Research (for research.html) — themes and hooks
Themes: 1) Tax reform & household welfare, 2) Firms, taxes & global production,
3) Legal form of organization (cross-cutting: firms + banks), 4) Time-inconsistent
preferences & welfare (with Feigenbaum).
Publications already on site with abstracts (9 pubs, 1 WP, 4 WIP) — hooks written from
those abstracts; per-paper key numbers: gradual tax reform → 95% vs <25% short-run
winners; LFO reform → +1.25% output (published EM version; portfolio's 6.8% is older
draft — use published 1.25%); China VAT reform → ~half of R&D rise from manufacturing
outsourcing; profit shifting → domestic multi-establishment firms bigger than comparable
MNEs.
- 30+ research presentations. RePEc: journals top 3%–15%.
- Non-peer-reviewed: "Which jobs and industries are most affected by COVID-19?" w/ Bilicka,
  Center for Growth and Opportunity.

### Service (kept off site per current scope; available if a service section is wanted)
Curriculum committee 2019–; E&F Research Scholarship comm 2024–; referee for J. Public
Econ, Economic Modelling, Public Finance Review, Southern/Eastern Econ J, Health Econ Rev;
Midwest Macro program committee 2020, 2022.

## Conventions
- Tabs for indentation in HTML, CSS uses 2-space; keep hand-authored, dependency-free.
- Hooks live in `.pub .hook` paragraphs; abstracts stay inside `<details>`.
- CV page is just a download card for `files/cv_sepideh_raei_junuary_2026.pdf`.
