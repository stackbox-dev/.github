# .github — organization defaults

This repository holds **default community-health files** for the `stackbox-dev`
organization. GitHub applies each of these to any repo that does **not** define its
own copy:

- `.github/PULL_REQUEST_TEMPLATE.md` — the PR description template
- `.github/ISSUE_TEMPLATE/` — bug & feature issue forms
- `SECURITY.md` — how to report a vulnerability
- `CONTRIBUTING.md` — the contribution flow (branch → PR → 1 approval)

A repo overrides any default by committing its own version of that file.

Governance SOPs (access model, repo standards) live in the `sop` repository —
`github-teams.md` and `github-repo-standards.md`.
