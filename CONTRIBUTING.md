# Contributing to Awesome AI Tools

Thanks for helping this list grow. There are two ways to contribute: **recommend a tool** (no git needed) or **open a pull request**.

## 1. Recommend a tool (easiest)

Open a [New tool issue](https://github.com/ikaijua/Awesome-AITools/issues/new/choose) and fill in the template. That is the fastest path if you don't want to touch the tables yourself.

Before submitting, please search the README for the tool name and check its category — duplicates cost maintainer time and get closed.

## 2. Open a pull request

### Entry format

Both READMEs use a strict 4-column table.

English (`README.md`):

```markdown
| Name | Description | Links | Fees |
| --- | --- | --- | --- |
| Tool Name | 🌟 One or two factual sentences: what it is, who makes it, current flagship version, and what it is best at. [Intro](docs/<slug>/README.md) | 1. [URL](https://example.com)<br>2. [Github](https://github.com/org/repo) | Free/Paid |
```

Chinese (`README-CN.md`) mirrors it exactly with `| 名称 | 说明 | 链接 | 费用 |`.

### Field rules

- **Name** — the product name only. No taglines, no emoji other than the markers below.
- **Description** — factual and current. Name the current flagship model/version and, where it matters, the pricing. If a tool is clearly the best pick in its category, add `🌟`; if it is freshly released or a developer preview, add `🌱`. Both markers are used sparingly — most entries get neither.
- **Links** — official site first, GitHub second. Open-source projects should also carry a stars badge: `![GitHub Repo stars](https://img.shields.io/github/stars/org/repo?style=social)`.
- **Fees** — one of `Free`, `Paid`, `Free/Paid`, `Free Trial`.

### Before you submit

- [ ] The entry is added or updated in **both** `README.md` and `README-CN.md` — a change in only one language is a bug.
- [ ] You ran `python3 scripts/format_readmes.py` (it normalizes table separators and headers; run it after any table edit).
- [ ] Links resolve — `lychee .` locally, or let the `link-check` CI workflow confirm it.
- [ ] `CHANGELOG.md` is updated **only** when a tool is added, removed, renamed, or refreshed to a new flagship version. Typo fixes, link repairs, and reordering do not need an entry.
- [ ] Deep-dive content goes to **GitHub Discussions** (one EN + one CN post), not a new page under `docs/`. `docs/` is for stable reference material only; anything that changes often — features, pricing — belongs in a discussion.

Full conventions, including the marker rules and changelog policy, live in [`AGENTS.md`](AGENTS.md).

## What does *not* get merged

- Tools with no working link, or link farms / SEO aggregators.
- Anything that is really an ad rather than a tool.
- Duplicate entries under a slightly different name.

## License

By contributing, you agree that your contribution is released under the same terms as the rest of the repository: **[CC BY 4.0](LICENSE)**. You keep authorship; anyone may reuse, translate, or mirror the content as long as this repository is credited.

If you are submitting a large body of original writing and want different attribution handling, say so in the pull request and we will work it out.

## Sponsors

Interested in sponsoring the project? See the "Become Sponsors" section in the README.
