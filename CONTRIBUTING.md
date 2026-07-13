# Contributing

This is the org-wide baseline. Each repo's own `README` / `CONTRIBUTING` covers
setup and any repo-specific rules that go beyond this.

## Flow
1. **Branch** off the repo's default branch. (It varies by repo — `main`, `master`,
   or `release` — check before branching.)
   Recommended name: `<type>/<ticket>/<short-desc>`, where `<type>` is one of
   `feat` `fix` `chore` `refactor` `test` `perf`.
   > WMS repos **enforce** a `(IB|CI|OB)-FUL-<digits>` ticket format in the branch name;
   > other squads follow their own ticket prefix. Match your repo's convention.
2. **Commit** using [Conventional Commits](https://www.conventionalcommits.org/)
   (`feat:`, `fix:`, `chore:`, …) and reference the ClickUp card.
3. **Before pushing**, run the repo's formatter + linter (`prettier`/`eslint` for
   TS/JS, `ruff` for Python). Let the pre-commit / pre-push hooks run.
4. **Open a PR** against the default branch, fill in the template (What / Why /
   How to test), and make sure CI is green.
5. **Get one approving review.** Any teammate can approve — you can't approve your
   own PR. Resolve all review comments before merging. If you push new commits, the
   approval resets, so get a fresh one.
6. **Merge** — merge commits only (no squash/rebase); the branch is deleted
   automatically after merge.

## Reviewing
An approval means you actually looked. You don't need to understand every line, but
you should know **what** the PR does and **why**. If you can't tell, ask the author
before approving.

## Ownership
Dependency, CI, container, and config files are owned by `@stackbox-dev/dev-leads`
via `CODEOWNERS` in the repos that define it — those changes need a dev-lead's review.

Full access model and repo standards: see the `sop` repo (`github-teams.md`,
`github-repo-standards.md`).
