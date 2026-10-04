---
author: "Sarmad"
date: "2026-10-04"
tags: [facts]
---

# Team facts

Long-lived facts every teammate's AI should know. One fact per bullet;
keep it short, current, and non-obvious.

- This vault is a public, test-only dogfood sandbox for the Cohort
  project; synthetic data only, forever.
- Writebacks in this vault always ship as pull requests
  (review_gated: true), so every dogfood cycle exercises the review path.
- Session logs nest by year and month; the first writeback of a new
  month creates a new sessions/YYYY/MM/ directory.
- The sandbox now tracks a released Cohort (v0.2.0, tagged 2026-10-02);
  LOAD behavior on the shipped skill matches the pre-release manual
  runs.
- Cohort main now carries skill spec_version 0.3.0 (browser-repo
  bootstrap option); the installer still pins v0.2.0 until the beta
  feedback defines v0.3.0.
