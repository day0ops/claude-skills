# claude-skills

Personal (non-work-specific) Claude Code skills, public since none of them
reference confidential or company-internal detail.

## Skills

- [`obsidian`](obsidian/SKILL.md) - find, navigate, read, and edit notes in
  the personal and work Obsidian vaults.

## Using these skills

Added as a git submodule of [day0ops/dotfiles](https://github.com/day0ops/dotfiles)
at `claude-skills/`, which symlinks each skill directory from here into both
`~/.claude/skills` and `~/.claude-work/skills` via Stow. `git submodule
update --init --recursive` (already run on dotfiles rebuild) keeps it in
sync - no separate clone step needed.
