# SummErOK's Claude Code plugins

English | [简体中文](README.zh-CN.md)

A plugin marketplace for Claude Code. Add it once, then install any plugin listed below.

```
/plugin marketplace add SummErOK/claude-plugins
```

| Plugin | What it does | Install |
|---|---|---|
| [cc-doc-review](https://github.com/SummErOK/CC-Doc-Review) | Select text in Claude-generated Markdown/HTML, comment, and send the comments back to the session; Claude edits and resolves them. | `/plugin install cc-doc-review@summerok` |

Each plugin lives in its own repository; this repository only holds the catalog (`.claude-plugin/marketplace.json`). Run `/plugin marketplace update summerok` to pick up newly listed plugins.

## Naming

- Plugin repositories are named `CC-<Name>`; plugins are named `cc-<name>`.
- Install commands read `plugin@marketplace`, so every plugin here installs as `cc-<name>@summerok`.

## License

MIT
