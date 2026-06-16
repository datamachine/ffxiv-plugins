# FFXIV Plugins

Shared Dalamud plugin repository for:

- **[FFXIV Todo](https://github.com/datamachine/ffxiv-todo)** — Track non-MSQ content completion across all expansions
- **[FFXIV Telegram](https://github.com/datamachine/ffxiv-telegram)** — Bridge FFXIV chat to a private Telegram bot

## Install

Add this URL in Dalamud:

```
https://datamachine.net/ffxiv-plugins/pluginmaster.json
```

1. In-game, open `/xlplugins`
2. Settings → Experimental → Custom Plugin Repositories
3. Paste the URL above
4. Save, refresh, install

## How it works

Each plugin's CI pushes release `.zip` files and updates `pluginmaster.json` when a `v*` tag is pushed. GitHub Pages serves this repo at `datamachine.net`.
