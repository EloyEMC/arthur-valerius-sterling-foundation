# Arthur Valerius Sterling Foundation

Static literary archive: a diegetic 2008 Foundation website initiated by Catherine “Kate” Sterling, presented in the visual language of an institutional website from 2006. Kate is Arthur and Elizabeth’s architect daughter; the site records their household, papers, and absences without making her a detective or secret custodian.

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000/>. No build step or JavaScript is required. The output deliberately uses a fixed 960px desktop canvas, float-based columns, simple links, tables, and conservative CSS rather than responsive/mobile-first techniques.

## Cloudflare Pages

Use these project settings:

| Setting | Value |
|---|---|
| Framework preset | None |
| Build command | Blank (or `exit 0`) |
| Output directory | `.` |
| Custom domain | `arthurvaleriussterling.org` |

Cloudflare Pages serves the repository root as unchanged static files. No backend, database, accounts, comments, analytics, cookies, or dynamic service is part of the site.

## Route map

- `index.html` — Home: purpose, couple, household legacy, and cared-for incomplete archive.
- `foundation.html` — The Foundation: the 2008 digital preservation project and its limits.
- `site-history.html` — Site history: Kate’s initiative, source materials, and the gradual cataloguing plan.
- `legacy.html` — The Sterling Legacy: books, correspondence, papers, photographs, notebooks, the IBM Selectric, and missing materials.
- `about.html` — Arthur Valerius Sterling: biography, career, portrait, and unresolved disappearance.
- `elizabeth-crawford.html` — Elizabeth Crawford Sterling: historian, independent professional life, marriage, illness, and household record.
- `chronology.html` — partial shared chronology.
- `works.html` — Arthur’s approved research papers and three provisional Elizabeth records.
- `works/causal-structure.html` and `works/inheritance-without-memory.html` — paper records and abstracts.
- `archive.html` — current catalogue without invented totals or accession numbers.
- `editorial-notes.html` — cataloguing limits, corrections, and open questions.
- `fiction-notice.html` — complete Editorial Framework and fiction/diegetic disclosure.
- `styles.css` — fixed-width 2006–2008 presentation using CSS 2.1-era layout techniques; no responsive behavior.
- `assets/` — supplied Arthur portrait images, presented with documentary provenance pending.

## Editorial boundaries

The papers remain explicitly fictional/diegetic, unsubmitted, unpublished, and not validated scientific results. Elizabeth is a historian of European cultural and intellectual history, not a scientific collaborator. The 2008 Foundation material is based on family papers and available materials after Elizabeth’s death around 1984 and Arthur’s 1991 disappearance; later cataloguing additions are identified as later work, not retroactively attributed to the first site. Unknown details remain pending or incomplete. The site does not invent institutional facts, item counts, scans, locations, staff, donors, awards, or an explanation for Arthur's disappearance.
