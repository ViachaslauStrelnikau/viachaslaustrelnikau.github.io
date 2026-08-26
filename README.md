# viachaslaustrelnikau.github.io

Personal CV site of Viachaslau Strelnikau — Backend / Full-Stack Developer (Java, Spring).

**Live site: <https://viachaslaustrelnikau.github.io/>**

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The CV page — self-contained, no build step and no external assets |
| `Viachaslau_Strelnikau_CV_EN.docx` | Source CV, linked from the page's download button |
| `_config.yml` | Site title and description |

## How it works

`index.html` has no Jekyll front matter, so GitHub Pages serves it verbatim.
Everything is inlined — the CSS, the favicon, the GitHub mark — so the page has
no external requests and works offline.

It follows the visitor's light/dark preference via `prefers-color-scheme`,
stacks to a single column on narrow screens, and carries print rules so
`Ctrl+P` produces a clean A4 PDF with the action buttons hidden.

## Updating

The page content mirrors `Viachaslau_Strelnikau_CV_EN.docx`. When the CV
changes, replace the `.docx` and apply the same edits to `index.html`.

## Elsewhere

- GitHub — <https://github.com/ViachaslauStrelnikau>
- GitLab — <https://gitlab.com/viachaslau.strelnikau>
- LinkedIn — <https://www.linkedin.com/in/vvs85>
