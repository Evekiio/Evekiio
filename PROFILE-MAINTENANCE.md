# Maintaining this portfolio

Update this profile manually through focused feature branches and pull requests. Follow AGENTS.md: draft, local validation, ready, then normal merge when applicable checks allow. No scheduled updater is required.

## Add a project

Use this repeatable pattern, adapting the length to the available evidence:

### Project name
Optional original section artwork with descriptive alt text.
**Discipline** · Public source or private overview · Verified stage

**The purpose:** the human problem or experience.
**The engineering:** two or three concrete decisions and their value.
**Current boundary:** what exists, what is planned and what remains unverified.
Public project/source/release links, where available.

Keep essential information in Markdown. Use natural headings and single-column flow so the profile works at narrow widths. Favor a small number of meaningful projects over a repository inventory.

## Check the evidence

- Read current authorized source before changing a claim. Record the inspected revision in the PR.
- Separate default-branch changes from downloadable releases; distinguish concepts from gameplay.
- Summarize private work only at the owner's approved high level. Never publish private source, internal documents, client details or assets.
- Preserve artwork credits, source links and existing history. Keep professional identity separate from unrelated creative identities.
- Avoid badges, dynamic counters and claims that will silently go stale.

## Validate and publish

Check relative paths, heading anchors, SVG XML, accessible image descriptions and self-contained SVGs. Inspect the actual GitHub rendering on desktop and at 320px/390px in light and dark views; verify image loading, wrapping and overflow. Review the exact changed files and confirm remote main has not moved before merging.

Record checks and limitations honestly in the PR. No CI workflow is configured for this profile; do not call a manual check a CI pass. After merge, confirm the exact remote commit and the live profile. Use a new commit or revert PR for corrections; preserve rollback history.
