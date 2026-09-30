# HeyTraders Marketplace

Claude plugins for HeyTraders.

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add heytraders/heytraders-marketplace
```

## Available Plugins

### heytraders

Hey-Traders! Quant Trading gives Claude agent-native access to HeyTraders through Claude's browser. You can use it with Claude in Chrome or with the Claude desktop app's built-in Browser pane.

**Install:**

```
/plugin install heytraders@heytraders-marketplace
```

**What you get:**

- Chart analysis and chart operations: indicators, drawings, panes, and layout
- Market data and market research
- Strategy building and backtesting
- Strategies in simulated paper mode

The plugin does not place, change, or cancel real orders. It also does not run live trade-mode strategies or connect exchanges.

**Repository:** https://github.com/heytraders/HeyTraders-Claude

## Removed Plugins

`heytraders-cli` was a legacy plugin and is no longer listed. When this marketplace updates, Claude Code drops it from users' enabled plugins and reports it as removed.

## Marketplace Structure

```
heytraders-marketplace/
├── .claude-plugin/
│   └── marketplace.json       # Plugin catalog
└── README.md
```

## Support

- **Issues**: https://github.com/heytraders/heytraders-marketplace/issues
- **Plugin**: https://github.com/heytraders/HeyTraders-Claude

## License

MIT
