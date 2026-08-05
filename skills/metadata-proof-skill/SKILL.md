---
name: metadata-proof-skill
description: Throwaway skill folder used only to exercise the ClawHub reusable skill-publish workflow in dry-run mode.
---

# Metadata Proof Skill

This folder exists so the ClawHub reusable `skill-publish.yml` workflow has a
real target to resolve during a dry run. It is never published for real: every
job that references it hardcodes `dry_run: true` and supplies no ClawHub token.
