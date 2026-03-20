# Contributing to alterion-enc-pipeline

Thanks for your interest in contributing. This is a security-critical crate — the bar is high and the rules are firm. Read this in full before opening anything.

---

## Before you start

Open an issue first. Describe the problem or the change you want to make and wait for a maintainer to respond before writing any code. PRs opened without a linked issue will be closed without review.

---

## What we want

- Genuine bug fixes with a clear root cause identified
- Security improvements with a well-reasoned rationale
- Performance improvements that are measurable and don't compromise correctness
- Missing test coverage for existing documented behaviour
- Platform compatibility fixes (the keyring layer, build targets, etc.)

---

## What we do not want

**Do not open a PR for:**

- Fixing a typo, adding a full stop, or rewording a sentence in the README or docs — these are not contributions
- Adding your name, handle, or social link anywhere in the repo
- Reformatting code you did not otherwise change
- Bumping dependency versions without an accompanying security advisory or breakage reason
- Renaming things for personal preference
- Anything described as "cleaning up" or "improving readability" without a functional change

PRs of this kind waste reviewer time and will be closed immediately. Repeat offenders will be blocked.

---

## No slop

Do not submit AI-generated code.

This means: if you used an AI assistant to write or refactor any part of your submission, you are responsible for having read every line, understood what it does, verified it is correct, and being able to explain it in review. Submitting output you do not understand is not a contribution — it is noise that creates security risk in a crate that handles cryptographic material.

If a reviewer asks you to explain a change and you cannot, the PR will be closed.

---

## Standards

- All code must compile with `cargo check` and pass `cargo test` with no new failures
- `cargo clippy -- -D warnings` must produce no new warnings
- Every public item you add or modify must have a rustdoc comment
- Unsafe code is not permitted
- Do not introduce new dependencies without a strong justification discussed in the issue first
- Wire format and public API changes are breaking — they require a major version bump discussion before any PR is raised

---

## Pull request process

1. Fork the repository and create a branch from `main`
2. Name your branch clearly: `fix/keyring-missing-entry`, `feat/rotate-api`, etc.
3. Fill out every section of [PR_TEMPLATE.md](PR_TEMPLATE.md) — incomplete templates will be closed
4. Link the issue your PR resolves in the template header
5. Complete the checklist at the bottom of the template before requesting review

Maintainers review on their own schedule. Do not ping, bump, or reopen closed PRs.

---

## Security vulnerabilities

Do not open a public issue or PR for a security vulnerability. Email the maintainers directly. You will receive a response within 72 hours.

---

## License

By submitting a pull request you agree that your contribution will be licensed under the [GNU General Public License v3.0](LICENSE) and that you have the right to make that contribution.
