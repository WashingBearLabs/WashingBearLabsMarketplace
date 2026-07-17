# WashingBearLabs Plugins

A plugin marketplace by [WashingBearLabs](https://github.com/WashingBearLabs), for
both **Claude Code** and **GitHub Copilot CLI**.

This repository serves both clients from a single marketplace:

- Claude Code reads `.claude-plugin/marketplace.json` → installs the Claude build.
- GitHub Copilot CLI reads `.github/plugin/marketplace.json` → installs the
  Copilot-native build (cross-platform: macOS & Windows).

The install commands and plugin name (`kit-tools@washingbearlabs`) are identical
on both tools; each client automatically resolves the build appropriate for it.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **kit-tools** | Documentation framework for AI-assisted development |

## Installation

### Claude Code

From inside Claude Code:

```
/plugin marketplace add WashingBearLabs/WashingBearLabsMarketplace
/plugin install kit-tools@washingbearlabs
```

### GitHub Copilot CLI

From your terminal:

```
copilot plugin marketplace add WashingBearLabs/WashingBearLabsMarketplace
copilot plugin install kit-tools@washingbearlabs
```

Update later with `copilot plugin update kit-tools`.

## Links

- [kit-tools for Claude Code](https://github.com/WashingBearLabs/KitTools)
- [kit-tools for GitHub Copilot CLI](https://github.com/WashingBearLabs/KitToolsCopilot)
- [WashingBearLabs](https://www.washingbearlabs.com)
