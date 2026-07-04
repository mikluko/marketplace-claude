# marketplace-claude

My personal [Claude Code](https://code.claude.com) plugin marketplace.

## Use

```
/plugin marketplace add mikluko/marketplace-claude
/plugin install <plugin>@mikluko
```

## Plugins

- **machine-debian** — Apple `container` machine tooling and the
  `apple-container` skill (macOS containerization).
  Source: [`mikluko/machine-debian`](https://github.com/mikluko/machine-debian).

## Layout

`.claude-plugin/marketplace.json` lists the plugins; each entry points at the
plugin's own repository. The marketplace `name` is `mikluko`, so plugins install
as `<plugin>@mikluko`.
