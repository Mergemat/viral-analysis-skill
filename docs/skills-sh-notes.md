# skills.sh Notes

These are the practical docs conclusions used for this repo.

## Repository Layout

`skills` discovers skill folders in standard locations, including the repository root and `skills/<name>/SKILL.md`. This repo uses the root layout:

```text
SKILL.md
```

This keeps installation simple for a single-skill repo.

## Install Command

The CLI installs from a GitHub source:

```bash
bunx skills add Mergemat/viral-analysis-skill -g -y
```

The skill name comes from the root `SKILL.md` frontmatter: `viral-analysis`.

## Listing and skills.sh Page

skills.sh listing is driven by anonymous CLI install telemetry. The repo page appears after the repo has been installed through the CLI and cache refreshes.

`skills.sh.json` only affects how the repo page is grouped on skills.sh. It does not change install behavior or skill content.

## Safety

Skills are executable instructions for agents. Users should inspect `SKILL.md` before installing. This skill contains no scripts or supporting executables.
