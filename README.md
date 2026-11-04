# TrueNorthIT/.github

Org-wide GitHub defaults for TrueNorthIT.

- `workflow-templates/`: templates shown under *Actions → New workflow → By TrueNorthIT*.
- `.github/workflows/`: shared (reusable) workflows that org repos call with `uses: TrueNorthIT/.github/.github/workflows/<name>.yml@<tag>`.

This repo is **public** and holds plumbing only. Prompts, model settings and agent code live in the private `TrueNorthIT/tn-local-agents` kit, which these workflows fetch at a pinned tag.
