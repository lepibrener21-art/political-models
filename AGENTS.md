# Guide for AI assistants

Keep reads and writes small. This repo is designed so most questions can be answered from `INDEX.md` alone.

## Reading order

1. `INDEX.md` — always first. Do not open model cards unless the task needs detail.
2. `framework/axes.md` — only when scoring or comparing.
3. Individual `models/*.md` — only the ones relevant to the task.
4. `sources.md` — only to resolve a citation key.

## Writing rules

- One model per file: `models/<kebab-case-slug>.md`, built from `framework/template.md`.
- Keep the fixed headings and order. Bullets over paragraphs. Target under 400 words per card.
- Scores live in frontmatter only; never repeat them in the body.
- Cite sources by key (`[brennan2016]`); full entries go in `sources.md` once, never in cards.
- Link related models by slug instead of re-explaining them.
- Every new or changed card must be reflected in `INDEX.md` in the same change.
- Mark claims about current events with the year checked, e.g. `(as of 2026)`.
- Present contested points as contested; include the strongest objection to every model.
