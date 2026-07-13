## What
<!-- What does this PR change? One or two sentences. -->

## Why
<!-- The motivation, and a link to the ClickUp card / issue. -->

## How to test
<!-- Steps a reviewer can follow to verify the change. -->

## Checklist
<!-- Self-attestation — tick what applies to this repo/change. -->
- [ ] Formatter run (`prettier` for TS/JS, `ruff format` for Python)
- [ ] Lint passes with no new warnings (`eslint` / `ruff check`)
- [ ] Types / build check where applicable (`tsc --noEmit` / build)
- [ ] Tests added or updated, and passing, for this change
- [ ] DB migrations (if any) are backward-compatible
- [ ] No secrets, credentials, or `.env` values committed
- [ ] Commits follow Conventional Commits (`feat` / `fix` / `chore` / `refactor` / `test` / `perf`)

> A reviewer should be able to tell **what** this does and **why** from the description
> above — even without reading every line. If they can't, add detail before requesting review.
