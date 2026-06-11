![Fōrmulæ banner](banner.png)

# Fōrmulæ

**One visual workspace for computing, composing, and conversing — where every expression is a tree you build by sight, not text you type.**

🌐 **Try it now at [formulae.org](https://formulae.org)**

Fōrmulæ is a web-based environment built around a single idea: information — a formula, a program, a document, a question for an AI — is a **tree-structured expression**, edited visually and rendered as proper mathematical and scientific notation on an HTML canvas. There is no syntax to learn and nothing to install; it runs entirely in the browser.

The same expression can be used three ways:

- **Compute** — evaluate it. Arithmetic, symbolic algebra, logic, lists, strings, control flow… the workspace is a live REPL — except you can return to any earlier question, change it, and recompute.
- **Compose** — display it. Paragraphs, tables, equations, images, links, colors, lists — a Fōrmulæ document is pretty-printed like a page, so a single file is both a runnable program *and* readable documentation.
- **Converse** — send it to an AI. The expression *is* the prompt; the model replies with another Fōrmulæ expression that renders in place. Because notation is structured, both the question and the answer can carry equations, matrices, tables, code, and inline images.

> Fōrmulæ is the only AI notebook where mathematical and scientific notation is a first-class data type in **both the question and the answer**. Connect OpenAI, Anthropic, or Google — or a private, local model via Ollama.

## Repositories

| Repository | Description |
|---|---|
| [formulae-js](https://github.com/formulae-org/formulae-js) | Core web application — engine, canvas renderer, REPL, AI connections |
| [web-content](https://github.com/formulae-org/web-content) | The live website: articles, showcases, examples and reference (`.formulae` files) |
| `package-*-js` | One repository per package (see list below) |

### Packages

Each package lives in its own repository named `package-{name}-js` and adds the expressions for one field — visualization, editing, and (where applicable) evaluation:

`arithmetic` · `complex` · `symbolic` · `logic` · `relation` · `list` ·
`matrix` · `set` · `programming` · `calculus` · `statistics` · `typesetting` ·
`plot` · `chart` · `color` · `graphic-raster` · `diagramming` · `internet` ·
`time` · `chemistry` · `cryptography` · `data` · `bitwise` · `localization` ·
and more.

The web app loads a base set of packages at startup and can load others on demand.

## Getting started

The easiest way to use Fōrmulæ is at [formulae.org](https://formulae.org) — nothing to install. New here? Open a **showcase** straight from the site (e.g. [`?script=showcases/Arithmetic`](https://formulae.org/?script=showcases/Arithmetic)) to see a package at work, or try the AI **Converse** demo at [`?script=examples/AI converse`](https://formulae.org/?script=examples/AI%20converse).

## Contributing

Contributions are welcome — bug reports, new packages, translations, and content (articles, showcases, examples). Please open an issue or pull request in the relevant repository.

For questions or general contact: **contact@formulae.org**

## License

All repositories are released under the
[GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.html).
