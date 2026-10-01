# 贡献指南 · Awesome AI Tools

感谢你帮这份清单变得更好。有两种参与方式：**推荐工具**（不需要懂 git）或**提交 Pull Request**。

## 一、推荐工具（最省事）

直接提一个 [「推荐新工具」issue](https://github.com/ikaijua/Awesome-AITools/issues/new/choose) 并按模板填写。如果你不想自己改表格，这是最快的方式。

提交前请先在 README 里搜一下工具名、看看对应分类，避免重复——重复条目会浪费维护者时间并被关闭。

## 二、提交 Pull Request

### 条目格式

两份 README 都使用严格的四列表格。

英文（`README.md`）：

```markdown
| Name | Description | Links | Fees |
| --- | --- | --- | --- |
| Tool Name | 🌟 一两句话的客观描述：它是什么、谁做的、当前旗舰版本、最擅长什么。[Intro](docs/<slug>/README.md) | 1. [URL](https://example.com)<br>2. [Github](https://github.com/org/repo) | Free/Paid |
```

中文（`README-CN.md`）用 `| 名称 | 说明 | 链接 | 费用 |` 完全对应。

### 各字段规范

- **名称** — 只写产品名。不要加标语，除下列标记外不要加 emoji。
- **说明** — 客观且及时。写明当前旗舰模型/版本，必要时写明价格。如果某工具在所属分类里明显是首选，加 `🌟`；如果是刚发布或开发者预览版，加 `🌱`。两个标记都要克制使用——大多数条目不加。
- **链接** — 官网在前，GitHub 在后。开源项目建议附上 star 徽章：`![GitHub Repo stars](https://img.shields.io/github/stars/org/repo?style=social)`。
- **费用** — 只能是 `Free`、`Paid`、`Free/Paid`、`Free Trial` 之一。

### 提交前的自检

- [ ] 条目在 `README.md` 和 `README-CN.md` **两份**里都改了——只改一种语言属于 bug。
- [ ] 已运行 `python3 scripts/format_readmes.py`（它会规范化表格分隔符和表头；任何表格改动后都要跑）。
- [ ] 链接可用——本地跑 `lychee .`，或交给 `link-check` CI 工作流验证。
- [ ] **只有**在新增、删除、重命名工具，或条目刷新到新的旗舰版本时才更新 `CHANGELOG.md`。改错别字、修链接、调整顺序都不需要写变更日志。
- [ ] 深度介绍请发到 **GitHub Discussions**（一篇中文 + 一篇英文），不要在 `docs/` 下新建页面。`docs/` 只放稳定的参考性内容；功能、价格这类频繁变动的信息属于讨论区。

完整约定（含标记规则和变更日志政策）见 [`AGENTS.md`](AGENTS.md)。

## 不会被合并的内容

- 链接失效的工具，以及导航站、SEO 聚合站。
- 实质是广告而不是工具的内容。
- 换个名字重复提交的条目。

## 许可证

提交贡献即表示你同意你的贡献采用与本仓库相同的 **[CC BY 4.0](LICENSE)** 协议发布。你保留署名权；任何人都可以复用、翻译或镜像这些内容，只要注明本仓库出处。

如果你提交的是大篇幅原创内容并希望采用不同的署名方式，请在 PR 里说明，我们再协商。

## 赞助

有兴趣赞助本项目？见 README 中的「赞助项目/赞赏支持」章节。
