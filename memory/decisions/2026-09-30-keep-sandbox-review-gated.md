---
adr: 1
title: Keep the dogfood sandbox review-gated
date: 2026-09-30
author: "Sarmad"
status: accepted
tags: [dogfood, review, process]
---

# Keep the dogfood sandbox review-gated

## Context

This vault is the Cohort project's public dogfood sandbox. Solo vaults
may self-merge per the Cohort security model (SECURITY.md section 4), so
review gating is optional here.

## Decision

Keep `review_gated: true`. Every writeback ships as a pull request with
human approval.

## Rationale

Dogfooding the review-gated path is the point of this vault: every cycle
exercises branch, PR, review, and squash merge, which is the flow real
teams are recommended to use.

## Consequences

Every writeback needs a branch and a PR; nothing lands on main directly.
Slower by minutes, honest by construction.
