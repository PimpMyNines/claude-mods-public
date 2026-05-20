# claude-mods-public

Public marketplace mirror for **PimpMyNines/claude-mods**.

This repository contains only the marketplace catalog and `.mcpb` release assets. It is generated automatically — do not edit by hand, and do not file issues here. For source code, issues, and contributions, the home is the private monorepo (request access from the PimpMyNines team).

## Install on Claude Code

```bash
/plugin marketplace add PimpMyNines/claude-mods-public
/plugin install personal-finance@catylai-marketplace
```

The marketplace identifier (`catylai-marketplace`) is intentionally the same as the brand prefix on each plugin's npm package (`@catylai/<name>`).

## Install on Claude Desktop

1. Visit [Releases](https://github.com/PimpMyNines/claude-mods-public/releases).
2. Download the `.mcpb` you want.
3. Drag it into **Claude Desktop → Settings → Connectors → Custom → Install**.
4. Fill in any required user config when prompted.

No auto-update is available for custom `.mcpb` extensions today — re-download from Releases when a new version ships.

## What's published here

All `@catylai/*` plugins on npm, plus `.mcpb` builds of every connector. Versioning is driven from the upstream monorepo's tags:

| Tag pattern | What it triggers |
|---|---|
| `plugin-<name>-v<version>` | npm publish + this repo's `marketplace.json` regenerated |
| `mcpb-<name>-v<version>` | `.mcpb` GitHub Release created on this repo |
