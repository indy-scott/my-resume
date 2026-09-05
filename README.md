# Scott Hepburn — Resume Source

This repository is the canonical source for Scott Hepburn's career history, skills, and selected projects. It is intentionally broader than a one- or two-page resume so tailored resumes can select the experience most relevant to a specific role without inventing details.

## Repository structure

- [`MASTER_RESUME.md`](MASTER_RESUME.md) — complete public-safe career source
- [`projects/`](projects/) — current and completed project records
- [`templates/project.md`](templates/project.md) — template for adding project evidence
- `private/contact.md` — local-only contact details used when generating applications; excluded from Git
- `private/source/` — original resume files; excluded from Git

## Tailoring rules

When generating a job-specific resume:

1. Treat `MASTER_RESUME.md` and `projects/` as factual source material.
2. Select and reorder material to match the job posting; do not add unsupported claims.
3. Preserve employers, titles, and dates.
4. Prefer quantified outcomes when the source provides them.
5. Pull private contact fields from `private/contact.md` only for the final application document.
6. Keep the public repository free of street addresses, phone numbers, and reference contact details.

## Updating the source

Add durable career facts to `MASTER_RESUME.md`. Give substantial projects their own Markdown file under `projects/`, using the project template. Capture technologies, scope, actions, outcomes, and verification while the details are fresh.
