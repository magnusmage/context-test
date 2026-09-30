---
name: "context-test (synthetic dogfood sandbox)"
format_version: "1.0.0"
visibility: public
members:
  - handle: "evdatsion"
    name: "Founder (dogfood)"
    role: founder
review_gated: true
rules: "VAULT.md is the manifest. Memory rules live in the Cohort spec (docs/TECHNICAL.md); this vault follows the Cohort vault schema v1."
---

# context-test, Synthetic Dogfood Vault

> **This vault is a public test-only sandbox.** Every fact, person, and
> decision here is synthetic dogfood content for the Cohort project.
> Nothing real belongs here, ever.

Shared team context for this team's AIs. Loaded by Cohort connectors at
session start; writebacks arrive as human-reviewed commits.

- **Visibility:** public (deliberate; this is a test sandbox, see SECURITY.md T4)
- **Review:** writebacks go through PR with ≥1 other human approving
- **Format:** Cohort vault schema v1. See the Cohort repo, docs/TECHNICAL.md §4
