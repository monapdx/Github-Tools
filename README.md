# GitHub Tools Suite

<img src="https://raw.githubusercontent.com/monapdx/Github-Tools/refs/heads/main/logo.png" width="454">
A collection of lightweight, browser-based tools for common GitHub workflows: README cleanup, links, badges, issue forms, YAML, and topics.

No install or build step. Open an HTML file locally or host the folder on **GitHub Pages**.

---

## What this is

Each tool is a **standalone static page** (plus shared stylesheets) you can open in any modern browser:

- README table of contents and anchors
- Shields.io-style badge buttons and snippets
- Deep links for repos, issues, templates, files, diffs, and more
- Topic visualization for a GitHub user
- Visual YAML form schema editing with preview
- GitHub issue form YAML, `config.yml`, deep links, README snippets, and optional starter ZIP (via JSZip from a CDN)
- README / profile markdown blocks via the dashboard-style builder

The landing page is [`index.html`](index.html), which lists every tool and links to the same files below.

---

## Tools included

| Tool | File | What it does |
|------|------|----------------|
| README TOC + Anchor Generator | [`github-anchor-generator.html`](github-anchor-generator.html) | Paste or upload a README; get a TOC and per-heading anchor snippets. |
| GitHub Button Generator | [`github-button-generator.html`](github-button-generator.html) | Configure Shields.io badges; copy Markdown, HTML, URL, or a plain link. |
| GitHub Link Generator | [`github-link-generator.html`](github-link-generator.html) | Pick a URL pattern and fill fields for issues, files, compare views, etc. |
| GitHub Topic Cloud | [`github-topic-cloud.html`](github-topic-cloud.html) | See topic frequency across a user’s public repos. |
| YAML Form Builder | [`yaml-form-builder.html`](yaml-form-builder.html) | Build YAML form definitions with a visual editor and live preview. |
| GitHub Issue Form Builder | [`issue-template-generator.html`](issue-template-generator.html) | Build issue form YAML, `config.yml`, deep link, README snippet, SVG button; download a starter ZIP. |
| GitHub Markdown Builder | [`github_dashboard_builder.html`](github_dashboard_builder.html) | Arrange blocks and export markdown for READMEs, profiles, and similar `.md` content. |

Quick links (GitHub Pages, same paths as this repo):

- [README TOC + Anchor Generator](https://monapdx.github.io/Github-Tools/github-anchor-generator.html)
- [GitHub Button Generator](https://monapdx.github.io/Github-Tools/github-button-generator.html)
- [GitHub Link Generator](https://monapdx.github.io/Github-Tools/github-link-generator.html)
- [GitHub Topic Cloud](https://monapdx.github.io/Github-Tools/github-topic-cloud.html)
- [YAML Form Builder](https://monapdx.github.io/Github-Tools/yaml-form-builder.html)
- [GitHub Issue Form Builder](https://monapdx.github.io/Github-Tools/issue-template-generator.html)
- [GitHub Markdown Builder](https://monapdx.github.io/Github-Tools/github_dashboard_builder.html)

---

## Live demo

[Open the suite on GitHub Pages](https://monapdx.github.io/Github-Tools) — start from `index.html` or jump to any tool above.

---

## How to use

1. Clone or download this repository.
2. Open `index.html` or any tool `.html` file in your browser, **or**
3. Enable GitHub Pages on the repo and open the hosted `index.html`.

All logic runs **in the browser**. There is no backend. Shared UI uses [`github-tools-common.css`](github-tools-common.css) and [`github-tools-neo.css`](github-tools-neo.css). The issue form builder loads **JSZip from a CDN** only when you download the ZIP.

---

## Tech stack

- HTML, CSS, vanilla JavaScript
- GitHub Pages–friendly static assets

---

## Contributing

Ideas, fixes, and new small tools are welcome—for example accessibility improvements, mobile layout tweaks, or clearer copy.

---

## License

MIT — use it, remix it, build on it.

---

## Possible extensions

- README visual preview (beyond markdown block assembly)
- Curated issue-template snippets or examples
- Other one-file generators that stay easy to host and audit

---

If this repo is useful, starring it helps others discover it.
