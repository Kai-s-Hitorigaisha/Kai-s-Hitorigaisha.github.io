# Contributing to Kai-s-Hitorigaisha.github.io

Thanks for helping improve the Kai's Hitorigaisha landing page! This repo
is the organization's website only — for the Hitorigaisha OS project
itself (vision, roadmap, and eventually code), head to
[Kai-s-Hitorigaisha/Hitorigaisha-OS](https://github.com/Kai-s-Hitorigaisha/Hitorigaisha-OS).

## What we welcome

* 🐛 **Display bugs** — layout breakage, light/dark scheme issues,
  horizontal scroll on mobile, broken links
* 📝 **Copy fixes** — typos, grammar, clarity
* ♿ **Accessibility** — contrast, semantics, reduced-motion handling

## What we will decline

* Frameworks, bundlers, npm, or any build step — this site is plain
  HTML + CSS on purpose (see [AGENTS.md](AGENTS.md))
* Webfonts, analytics, or any external request
* JavaScript, unless the feature is impossible without it and the page
  still works with JS off
* Brand changes — the name, logo, and attribution strings are fixed;
  the aesthetic is a departure board, not a game village

## Getting started

```sh
git clone https://github.com/Kai-s-Hitorigaisha/Kai-s-Hitorigaisha.github.io.git
cd Kai-s-Hitorigaisha.github.io
python3 -m http.server 8080   # then open http://localhost:8080
```

Nothing to install, nothing to build.

## Before opening a PR

1. Open the page in a browser.
2. Check light + dark scheme, 375px + 1280px widths.
3. No horizontal scroll, no console errors, no external requests.
4. All links resolve.

## Code style

* Tabs for indentation in HTML/CSS (match the existing files).
* Conventions and aesthetic rules: [AGENTS.md](AGENTS.md).
* Keep changes surgical — touch only what your fix requires.

## Code of Conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md).
