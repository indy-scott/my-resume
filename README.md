# Scott Hepburn — Resume Source

This repository is the canonical source for Scott Hepburn's complete career history, skills, and projects. It is designed to accumulate more detail than any single resume should contain, allowing job-specific resumes to select relevant evidence without inventing or losing information.

## Repository structure

- [`MASTER_RESUME.md`](MASTER_RESUME.md) — concise, public-safe consolidated resume
- [`experience/`](experience/) — detailed, expandable records for every role
- [`projects/`](projects/) — current and completed project records
- [`templates/experience.md`](templates/experience.md) — template for expanding a role
- [`templates/project.md`](templates/project.md) — template for adding project evidence
- `private/contact.md` — local-only contact details used when generating applications; excluded from Git
- `private/source/` — original resume files; excluded from Git

## Tailoring rules

When generating a job-specific resume:

1. Treat `experience/`, `projects/`, and `MASTER_RESUME.md` as factual source material.
2. Select and reorder material to match the job posting; do not add unsupported claims.
3. Preserve employers, titles, and dates.
4. Prefer quantified outcomes when the source provides them.
5. Pull private contact fields from `private/contact.md` only for the final application document.
6. Keep the public repository free of street addresses, phone numbers, and reference contact details.

## Updating the source

Add every role to `experience/`, including details that may not fit a normal resume. Record responsibilities, accomplishments, technologies, scale, collaborators, and measurable outcomes as they become available. Keep `MASTER_RESUME.md` concise and synchronized with the role records. Give substantial projects their own Markdown file under `projects/`. Never remove useful source facts merely because they are not relevant to the current target role.
