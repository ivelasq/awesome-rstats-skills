# Contribution Guidelines

## Adding a skill

Open a pull request with your addition. Each entry should:

- Link to the skill's containing directory (not directly to `SKILL.md`)
- Be placed under the most relevant existing category, or propose a new one if none fits
- Follow the format: `- [name](url) by [@author](https://github.com/author) - One-sentence description ending with a period.`
- Be genuinely useful and not a duplicate of an existing entry

## Adding a skill collection

Link to the repository root. Use the same format as skills:

`- [repo-name](url) by [@author](https://github.com/author) - One-sentence description ending with a period.`

## Adding a tutorial or blog post

Link to the post or page directly. Author attribution can be a plain name if the author has no GitHub handle:

`- [Post Title](url) by Author Name - One-sentence description ending with a period.`

## Removing an entry

Open a PR with a brief explanation if a link is broken or the content is no longer maintained.

## What counts as a skill?

A skill is a reusable prompt file designed to extend an AI coding assistant (e.g., Claude Code) with a specific workflow.
It should do one thing well and be scoped to R programming.
R programming is to be interpreted somewhat loosely, allowing for any skills which touch on R in some nontrivial manner.
For example, a Quarto skill which has features for better rendering of a `ggplot` would be allowed.
