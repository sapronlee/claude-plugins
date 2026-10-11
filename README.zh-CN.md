# SummErOK 的 Claude Code 插件

[English](README.md) | 简体中文

这是一个 Claude Code 插件市场。添加一次，就能安装下面列出的任意插件。每个插件都能单独使用，也能一起用。

```
/plugin marketplace add SummErOK/claude-plugins
```

| 插件 | 用途 | 安装 |
|---|---|---|
| [cc-doc-review](https://github.com/SummErOK/CC-Doc-Review) | 在 Claude 生成的 Markdown / HTML 里选中文字写评论，发回会话，Claude 修改后逐条标为已解决。 | `/plugin install cc-doc-review@summerok` |
| [cc-gauge](https://github.com/SummErOK/CC-Gauge) | 在输入框上方一眼看清 5h、7d 额度、上下文窗口和缓存命中率。仿照 Jetson Chan 的 [CC-Usage-Band](https://github.com/JetsonChan/CC-Usage-Band) 改写。 | `/plugin install cc-gauge@summerok` |

每个插件在各自的仓库里，本仓库只放插件目录（`.claude-plugin/marketplace.json`）。有新插件上架后，运行 `/plugin marketplace update summerok` 即可看到。

## 命名规则

- 插件仓库叫 `CC-<名字>`，插件叫 `cc-<名字>`。
- 安装命令的格式是「插件名@插件市场名」，所以这里的插件都按 `cc-<名字>@summerok` 安装。

## 许可证

MIT
