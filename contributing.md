# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

## What belongs here

This is a curated list of Claude Skills for design work — UX design, UX research, UI design, accessibility, usability testing, brainstorming, design systems, and writing / humanizer skills. A "Claude Skill" here means a folder with a `SKILL.md` file (see [agentskills.io](https://agentskills.io)) that Claude Code or compatible harnesses load on demand.

Only add items you have personally used or reviewed. Curation beats coverage.

## Adding an entry

1. Fork the repository and create a branch.
2. Add your entry at the bottom of the most appropriate category.
3. Use this exact format:

   ```
   - [Name](https://github.com/owner/repo) - Short, objective description ending with a period.
   ```

4. Rules for the entry:
   - Title-cased link name.
   - Description starts with an uppercase letter, ends with a period, and describes the skill itself — not the list.
   - No marketing copy. No emoji in the description.
   - Skills must be non-AI-generated, actively maintained, and genuinely useful.
5. Open a pull request. In the PR body explain why the skill is awesome and link to the `SKILL.md` file.

## Security expectations

Every submitted skill must be reviewed for:

- **Source.** Only reputable authors or clearly attributed forks.
- **Code behaviour.** No skills that exfiltrate data, execute remote code, phone home, or run untrusted binaries without consent.
- **Permissions.** Skills that touch the filesystem, network, or shell should scope their actions explicitly in `SKILL.md`.
- **Footguns.** Skills that edit Git history, push to remotes, or call external APIs must flag this in their description.

If you spot a skill in this list that no longer meets these expectations, open a PR to remove it.

## Updating your pull request

Maintainers may ask for edits, usually for spelling, formatting, or guideline compliance. Please update promptly.

## Removing an entry

Open a PR or issue. Valid reasons include: the project is archived, unmaintained for 12+ months, broken, AI-generated slop, or has developed security concerns.
