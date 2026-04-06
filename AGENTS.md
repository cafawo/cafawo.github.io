# Agent Instructions

- Treat this repo as an `academicpages` / GitHub Pages / Jekyll template. Prefer built-in collections, layouts, includes, data files, front matter, and config over new mechanisms.
- Preserve the existing structure. Do not rename, move, or delete pages, collections, assets, permalinks, navigation entries, or links unless the user explicitly asks.
- Keep existing URLs and internal/external links working. If a change could affect navigation, permalinks, SEO, GitHub Pages behavior, or content outside the request, warn the user first.
- Make the smallest change that solves the request. Do not perform unrelated cleanup or infer missing requirements.
- Do not guess. If content, behavior, scope, or intent is ambiguous, say so instead of inventing an answer.
- Stay close to the template's existing patterns and functions. Avoid custom code, custom layouts, new plugins, new build steps, or bespoke JS/CSS unless the user explicitly approves.
- Any custom solution requires explicit user acceptance before implementation.
- Prefer editing content in Markdown files and existing collection entries first: `_pages/` for standalone pages, `_publications/`, `_talks/`, `_teaching/`, and `_portfolio/` for archive-driven content, and `_data/navigation.yml` for menu links.
- For new entries in `_publications/`, always set `publication_type` in front matter. Use `peer_reviewed` for published peer-reviewed work and `working_paper` for working papers. The publications page renders `Peer-Reviewed` first and `Working Papers` second, with newest items first inside each section.
- Treat `_config.yml`, `CNAME`, `url`, `baseurl`, `repository`, and navigation as site-wide settings with broad impact. Do not change them without explicit user intent, and warn about the blast radius first.
- If `_config.yml` is changed, note that local Jekyll preview typically needs a restart for the change to take effect.
- Follow the repo's existing conventions in `_config.yml`, `_data/`, `_pages/`, `_publications/`, `_talks/`, `_teaching/`, `_portfolio/`, and `assets/`.
- If a requested change has possible blast radius beyond the requested scope, state that clearly before proceeding.
