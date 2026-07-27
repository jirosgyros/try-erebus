# try-erebus

Public pages for Erebus, a detection validation platform.

## Live

| Page | URL |
|---|---|
| Request a walkthrough (form) | https://jirosgyros.github.io/try-erebus/ |
| Product overview | https://jirosgyros.github.io/try-erebus/overview.html |

The two cross-link: the overview's closing CTA points at the form, and the form
page links back to the overview for anyone who wants the longer read first.

## How it is built

Static and self-contained. Two HTML files with inline CSS and JS, two images, no
build step, no framework, no external requests. The only network call either page
makes is the form POST to Formspree.

```
index.html      request form
overview.html   product overview (logo inlined as a data URI)
logo.png        brand mark
og-image.png    link-unfurl image
```

Served by GitHub Pages from `main` at the repository root.

Contact: [Anthony Jirouschek on LinkedIn](https://www.linkedin.com/in/anthonyjirouschek/)
