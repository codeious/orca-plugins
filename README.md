# Codeious plugins for Orca

A plugin marketplace for [Orca](https://github.com/stablyai/orca). It is not Orca's official marketplace.

## Add it

In Orca, open **Settings → Plugins**, enable plugins, and add this marketplace:

```
https://github.com/codeious/orca-plugins.git
```

## Plugins

| Plugin | What it does |
|---|---|
| [`codeious.boat-sandbox`](https://github.com/codeious/orca-boat-sandbox) | Runs a workspace in a fresh boat.dev sandbox. macOS and Linux. |

Each entry pins a release tag, so a listing never changes under you. Install a plugin, read the commands Orca shows, and approve them only if you trust them.

## Maintaining

`orca-marketplace.json` lists the plugins. To release a new plugin version, tag the plugin repo and change the entry's `ref` to the new tag.
