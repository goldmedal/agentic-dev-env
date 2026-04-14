# agentic-dev-env

Personal utility scripts and settings for agentic development workflows.

## Tools

| Script | Description |
|--------|-------------|
| `claude-exec-plan` | Launch Claude Code in an isolated git worktree for plan-driven coding tasks |

## Install

Symlink all scripts to `~/.local/bin`:

```bash
chmod +x bin/*
mkdir -p ~/.local/bin
for f in bin/*; do
  ln -sf "$(pwd)/$f" ~/.local/bin/
done
```

Make sure `~/.local/bin` is in your `PATH`:

```bash
# Add to ~/.zshrc or ~/.bashrc
export PATH="$HOME/.local/bin:$PATH"
```

## License

Apache License 2.0
