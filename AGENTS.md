# AGENTS.md

Guidance for AI agents working in this repository.

## Workflow

- Never commit on `main`. Create a working branch first.
- Keep changes focused on the task; avoid unrelated edits.
- Write clear, imperative commit messages.
- Push to the working branch only. Do not open pull requests; automation does that.

## Code quality

- Prefer clean, readable code and long-term fixes over quick patches.
- Add tests where they make sense.
- For UI work, wire the change into the production page or component. A story, preview, or fixture is not a substitute.

## Git hygiene

- Do not modify git user configuration.
- Do not add Co-authored-by or Signed-off-by trailers.
- Never put credentials in URLs, commands, config, or output.
