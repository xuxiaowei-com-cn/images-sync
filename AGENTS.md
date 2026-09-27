# Agent Skills

Agent skills for this project and their usage scenarios.

## DCO Skill

**When to use:** Every time you commit code (`git commit`), to ensure the commit message complies with the Developer Certificate of Origin (DCO) and automatically appends the `Signed-off-by:` line.

@skills/DCO.md

## Gitmoji Skill

**When to use:** Every time you commit code (`git commit`), to pick an appropriate gitmoji shortcode as the commit message title prefix based on the change.

@skills/GITMOJI.md

## English Commit Message Skill

**When to use:** Every time you commit code (`git commit`), to write the commit message title and body in English.

Commit messages MUST be written in English, including the title that follows the gitmoji shortcode. Do NOT write Chinese in the commit message title or body. The `Signed-off-by:` line keeps the name and email from `git config`.

```text
:shortcode: English commit message here

Signed-off-by: <git config user.name> <git config user.email>
```
