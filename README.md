> [!NOTE]
> Consider to use the [reveal-md template](https://github.com/litec-tmpl/tmpl-reveal-md) if you are not going to setup presentations with github pages.

# reveal.js-template

A template to generate [reveal.js](https://revealjs.com/) markdown presentation repositories with reveal.js as submodule.

This template uses reveal.js version 5.1.0 (see [reveal.js (github)](https://github.com/hakimel/reveal.js) for latest reveal.js tag).
See [how to host reveal.js on github-pages](https://martinomensio.medium.com/how-to-host-reveal-js-slides-on-github-pages-and-have-a-tidy-repository-1a363944c38d) on how to update to a newer version.

## Demo

Have a look at the demo github pages of this template repo: <https://litec-tmpl.github.io/tmpl-reveal.js/>.

## Setup

1. Create a new github repo which uses this template.
   - start with a public repo and change this to a private after complete setup
2. Activate github pages within this repository (see `Settings -> Pages`) - most of the time using the main branch is ok.
3. If you clone the repo locally:
   1. Get the submodule files with `git submodule update --init --recursive`.
   2. Checkout the latest reveal.js commit from master with `git submodule update --remote`.
   3. For testing purposes run a local server - for example with `vscode` and `live server` plugin.
4. Add own markdown files (sadly without yaml header!) and adapt `index.html` accordingly.
5. Upload (commit/push) changes to github.
6. Have a look at [`index.html`](./index.html) and fix the `@TODO`'s.

For a detailed explanation see [pachanero-revealjs-template](https://github.com/pacharanero/create-new-revealjs-template).

## Sources

- [reveal.js](https://revealjs.com/)
- [reveal.js (github)](https://github.com/hakimel/reveal.js)
- [how to host reveal.js on github-pages](https://martinomensio.medium.com/how-to-host-reveal-js-slides-on-github-pages-and-have-a-tidy-repository-1a363944c38d)
- [pacharanero-revealjs-template](https://github.com/pacharanero/create-new-revealjs-template)
