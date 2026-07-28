# AGENTS.md

## Cursor Cloud specific instructions

This is the `qwts/.github` repository: GitHub's org-wide **community health
defaults** (per ENG-0008). It is documentation/configuration only.

- Tracked content is just Markdown/config: `README.md`, `SECURITY.md`,
  `SUPPORT.md`, `PULL_REQUEST_TEMPLATE.md`, and `.github/CODEOWNERS`.
- There is **no application, build system, test suite, or dependency
  manifest** (no `package.json`, no `requirements.txt`, no `Makefile`, no
  `.github/workflows`). Nothing to install, build, run, or lint via a package
  manager, and the environment update script is intentionally a no-op.
- "Running" this repo means GitHub serving these files as defaults to any
  `qwts` repo that lacks its own copy. Verification is limited to checking the
  files exist, are non-empty, that internal Markdown links resolve, and that
  `.github/CODEOWNERS` is syntactically valid.
- Delta model: a repo that needs a variation adds its own file; do **not** edit
  these defaults to special-case one repo. Canonical baseline list lives in the
  playbook (`docs/sop/repo-baseline-files.md`).
- `.github/CODEOWNERS` deliberately names agent-primitive paths (`AGENTS.md`,
  `CLAUDE.md`, `.claude/`, `.codex/`, `.cursor/`, `.github/`, `.mcp.json`) in
  addition to the `*` wildcard, so those stay owned even if `*` is relaxed.
