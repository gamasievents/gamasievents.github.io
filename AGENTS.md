# AGENTS.md

## Repository Snapshot (verified)
- This repo currently contains content assets, not a runnable app scaffold.
- Root files are `pagina-feste.txt`, `pagina-compleanni.txt`, `pagina-cerimonie.txt`, and this file.
- Media folder contains `img/logo.jpg`.
- No `README*`, package/runtime manifest, lint/test config, CI workflow, or other agent-instruction files were found.

## What Agents Should Assume
- Treat `pagina-*.txt` as source marketing copy in Italian.
- Preserve each file's structure when editing: keyword/meta block, section headings, CTAs, and form-field list.
- Do not invent build/test commands; none are configured.

## Verification
- There is no automated lint or test suite.
- For text-only edits: verify spelling/format consistency and clean diff.
- If web files are added later, use `python3 -m http.server 4173` for manual preview.

## Maintenance
- Update this file whenever tooling, CI, or additional instruction sources are added.
