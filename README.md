# HeyTraders Marketplace

Claude Code plugins for quantitative trading.

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add heytraders/heytraders-marketplace
```

## Available Plugins

### heytraders-cli

CLI for quantitative trading. Analyze charts, fetch market data, run backtests, and execute trades — all from the terminal.

**Install:**

```
/plugin install heytraders-cli@heytraders-marketplace
```

**What you get:**

- 30+ chart actions with 67 drawing types and 400+ indicators
- Market data screening with expression-based scan and rank
- Async backtesting with result analysis
- Order management and live strategy subscriptions
- Pre-built quant analyst agent for autonomous trading workflows

**Repository:** https://github.com/heytraders/heytraders-cli

## Marketplace Structure

```
heytraders-marketplace/
├── .claude-plugin/
│   └── marketplace.json       # Plugin catalog
└── README.md
```

## Support

- **Issues**: https://github.com/heytraders/heytraders-marketplace/issues
- **CLI Plugin**: https://github.com/heytraders/heytraders-cli

## License

MIT
