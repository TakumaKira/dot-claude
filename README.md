# dot-claude

Git-managed Claude Code user configuration (`~/.claude`).

## What's Tracked

- `agents/` - Custom agent definitions
- `skills/` - Custom skills (hand-authored; symlink-installed skills are ignored)
- `output-styles/` - Output style configurations

## What's Ignored

- `settings.json`, `settings.local.json`, `config.json` - Machine-specific settings
- Skills installed via `npx skills add` (machine-local symlinks)
- Session data, caches, logs, telemetry
- Plugin management files, usage data, browser data

## Setup

1. Clone this repo:
   ```bash
   git clone https://github.com/TakumaKira/dot-claude.git ~/Git/dot-claude
   ```

2. Backup existing config:
   ```bash
   mv ~/.claude ~/.claude.backup
   ```

3. Create symlink:
   ```bash
   ln -s ~/Git/dot-claude/.claude ~/.claude
   ```

4. Verify Claude Code works by running `claude` in your terminal.
