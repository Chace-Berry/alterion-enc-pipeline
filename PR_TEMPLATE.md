# Pull Request: [PR Title]

**Branch:** `your-branch` → `main`
**Date:** DD Month YYYY
**Author:** Your Name / GitHub handle
**Reviewer:** <!-- leave blank — assigned by maintainers -->
**Issue:** [#000](https://link-to-issue) <!-- required — open an issue first if one doesn't exist -->
**Labels:** `bug` `enhancement` `security` `docs` `refactor`

---

## Summary

<!-- 2–4 sentences. What does this PR do and why? What problem does it solve or what value does it add?
     "Updated README" or "fixed typo" are not valid summaries — if that's all this PR does, it should not be a PR. -->

---

## Changes

| File / Module | Summary of Changes |
|---|---|
| `src/example.rs` | Describe what changed and why |

---

## Detailed Change Notes

### `src/example.rs`

<!-- Describe what this module does in the context of the crate and what specifically changed.
     Include before/after snippets where the change is non-obvious. -->

**Before:**
```rust
// old code
```

**After:**
```rust
// new code
```

---

## Bug / Failure Cascade *(if applicable)*

<!-- Use this table when fixing a chain of related bugs. Delete section if not applicable. -->

| # | Root Cause | File | Symptom / Impact |
|---|---|---|---|
| 1 | Describe the root cause | `file.rs` | What it caused |

---

## Testing

### What was tested
- [ ] Unit tests added or updated
- [ ] Integration tests pass (`cargo test`)
- [ ] Manually verified behaviour described in the summary

### How to reproduce / verify
1. Steps to set up
2. Action to perform
3. Expected result

---

## Public API changes *(if applicable)*

<!-- Delete if no public API surface changed. -->

| Item | Before | After | Breaking? |
|---|---|---|---|
| `fn example` | signature before | signature after | Yes / No |

---

## Notes & Risks

### Known limitations
- <!-- Any edge cases not addressed in this PR -->

### Follow-up work
- <!-- Any tech debt or follow-on issues created by this change -->

### Breaking changes
<!-- None / describe any breaking changes to the public API or wire format -->

---

## Checklist

- [ ] I have read the [CONTRIBUTING.md](CONTRIBUTING.md) in full
- [ ] This PR solves a real, stated problem — not a cosmetic or self-promotional change
- [ ] Every line of code submitted is code I understand and can explain
- [ ] No AI-generated code has been submitted without being fully read, understood, and verified
- [ ] `cargo check`, `cargo test`, and `cargo clippy` all pass with no new warnings
- [ ] Public items added or changed have rustdoc comments
- [ ] I have not bumped version numbers, edited unrelated files, or added my name to any list

---

## Sign-off

| | |
|---|---|
| **Author** | Your Name |
| **Reviewer** | <!-- assigned by maintainers --> |

*By opening this PR the author confirms the checklist above is complete and the change is ready for review.*
