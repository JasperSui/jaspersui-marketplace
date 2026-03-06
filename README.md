# jaspersui-marketplace

Claude Code plugins by Jasper Sui.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add JasperSui/jaspersui-marketplace
```

## Available Plugins

### iTerm2 Tab Status

**Description:** Show iTerm2 tab status (running/idle/attention) for Claude Code sessions

**Install:**
```bash
/plugin install iterm2-tab-status@jaspersui-marketplace
```

**What you get:**
- Real-time iTerm2 tab status indicators
- Three states: running, idle, attention (flashing)
- Configurable via `~/.config/claude-tab-status/config.json`
- Setup, config, and uninstall slash commands

**Repository:** https://github.com/JasperSui/claude-code-iterm2-tab-status

---

## Marketplace Structure

```
jaspersui-marketplace/
├── .claude-plugin/
│   └── marketplace.json       # Plugin catalog
├── LICENSE
└── README.md                  # This file
```

## Support

- **Issues**: https://github.com/JasperSui/jaspersui-marketplace/issues

## License

Marketplace metadata: MIT License

Individual plugins: See respective plugin licenses
