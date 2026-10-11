# SummErOK's Claude Code plugins

English | [简体中文](README.zh-CN.md)

A plugin marketplace for Claude Code. Add it once, then install any plugin listed below. The plugins work on their own or together.

```
/plugin marketplace add SummErOK/claude-plugins
```

| Plugin | What it does | Install |
|---|---|---|
| [cc-doc-review](https://github.com/SummErOK/CC-Doc-Review) | Select text in Claude-generated Markdown/HTML, comment, and send the comments back to the session; Claude edits and resolves them. | `/plugin install cc-doc-review@summerok` |
| [cc-gauge](https://github.com/SummErOK/CC-Gauge) | Your 5h and 7d limits, context window and cache hit rate, one glance above the prompt. Based on [CC-Usage-Band](https://github.com/JetsonChan/CC-Usage-Band) by Jetson Chan. | `/plugin install cc-gauge@summerok` |

Each plugin lives in its own repository; this repository only holds the catalog (`.claude-plugin/marketplace.json`). Run `/plugin marketplace update summerok` to pick up newly listed plugins.

## Naming

- Plugin repositories are named `CC-<Name>`; plugins are named `cc-<name>`.
- Install commands read `plugin@marketplace`, so every plugin here installs as `cc-<name>@summerok`.

## License

MIT
