# Contributing

Thanks for helping improve these marketing skills! Here's how to contribute.

## Types of Contributions

### Improve an existing skill
- Fix unclear instructions
- Add missing frameworks or steps
- Improve the self-review criteria
- Add examples or templates
- Fix typos or formatting

### Suggest a new skill
- Open an issue describing the skill
- Explain what it would cover and who it helps
- Bonus: include a draft

### Report a problem
- Open an issue describing what went wrong
- Include what you asked Claude to do and what happened

## Skill File Guidelines

Every skill lives in `skills/[skill-name]/SKILL.md` and should follow this structure:

1. **Role definition** — What Claude should act as
2. **Workflow** — Step-by-step process
3. **Sections/frameworks** — The actual marketing knowledge
4. **Self-review** — Quality criteria for Claude to check its own output
5. **Output format** — What the final deliverable looks like

### Principles

- **Works for any business type.** Don't assume SaaS. If a section is SaaS-specific, include alternatives for service businesses, local businesses, etc.
- **Designed for claude.ai Projects.** No file path references, no terminal commands, no codebase assumptions. Users are in the chat interface.
- **Specific over vague.** "Ask for their pricing with actual numbers" not "Gather pricing information."
- **Process over principles.** Walk Claude through a workflow, don't just list best practices.
- **Self-review built in.** Every skill should include a step where Claude evaluates its own output.

### Naming

- Lowercase with hyphens: `email-marketing`, not `EmailMarketing`
- Descriptive but concise
- The folder name should match what a user would naturally say: "help me with email marketing" → `email-marketing`

## How to Submit

1. Fork the repo
2. Create a branch: `feat/skill-name` or `fix/skill-name-description`
3. Make your changes
4. Open a PR with a clear description of what you changed and why

## Questions?

Open an issue — happy to help.
