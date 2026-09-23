# purba-proto-154 — THROWAWAY

A prototype for [purba#154](https://github.com/kalonji-tools/purba/issues/154).
It measures what the signing rewrite does to a branch that carries a merge commit.

**Nothing here is a contribution and nothing here merges anywhere. Delete this repository.**

Deviations from purba, deliberate:

- the `Origin` job and the `check-origin.sh` step are removed. An agent must never
  write a `Signed-off-by:` trailer, and the origin rule is not under test.
- `require_code_owner_review` is off. There is no `CODEOWNERS` here.
- `Quality` is a stub that passes. The real gate is not under test.
