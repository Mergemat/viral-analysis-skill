# Viral Analysis Skill

[![skills.sh](https://skills.sh/b/Mergemat/viral-analysis-skill)](https://skills.sh/Mergemat/viral-analysis-skill)

`viral-analysis` is an agent skill for content critique and repackaging. It teaches an agent to evaluate content through working comparables, first-promise diagnosis, story friction, culture pressure, and executable repackaging.

## Install

Using Bun:

```bash
bunx skills add Mergemat/viral-analysis-skill -g -y
```

Using npm:

```bash
npx skills add Mergemat/viral-analysis-skill -g -y
```

Install for Codex specifically:

```bash
bunx skills add Mergemat/viral-analysis-skill --agent codex -g -y
```

## Use

Ask your agent to use `viral-analysis` when you want to diagnose why a piece of content underperforms, compare it against working examples, or repackage an idea into a stronger hook and structure.

Example prompts:

```text
Use viral-analysis on this reel and compare it with my last 5 stronger posts.
```

```text
Use viral-analysis to turn this broad idea into a concrete first-frame premise and 30-second structure.
```

## What It Does

- Builds an evidence stack before judging.
- Compares the target against working examples.
- Diagnoses the first promise.
- Separates the asset from the packaging.
- Converts broad beliefs into concrete moments.
- Reads culture as format pressure.
- Gives executable repackaging, not generic advice.

## Video Links

If a linked video needs direct inspection, the skill tells the agent to use `yt-dlp` and analyze the downloaded file instead of relying only on metadata, captions, or thumbnails.

## Structure

```text
SKILL.md
skills.sh.json
docs/skills-sh-notes.md
```
