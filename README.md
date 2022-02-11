# Material for MkDocs (HigorLoren Template)

Create a branded static site from a set of Markdown files to host the documentation of your Open Source or commercial project, using Material for MkDocs and some tweaks made by [@HigorLoren](https://github.com/HigorLoren).

_For MkDocs full documentation visit [mkdocs.org](https://www.mkdocs.org)._

## Tweaks

- Dark theme inspired by Github
- Add switch for dark theme
- Hide "Made with Material for MkDocs Insiders"
- Enable:
  - Search suggest
  - Code annotate
  - Code highlight
  - Links in line number
  - Highlighting of inline code blocks
  - Embed content
  - Superfences (admonitions, tabs, lists, etc...)
  - Rendering of keyboard keys
  - Others...

## Installation

Prerequisites: `Python3`

```shell
pip install mkdocs
pip install mkdocs-material
```

## Material Design for MkDocs

- [Getting started](https://squidfunk.github.io/mkdocs-material/getting-started)
- [Setting up](https://squidfunk.github.io/mkdocs-material/setup)
- [Components](https://squidfunk.github.io/mkdocs-material/reference)

## Commands

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

## Project layout

  ```text
  mkdocs.yml       # The configuration file.
  docs/
      index.md     # The documentation homepage.
      assets       # Folder for images, GIFs, videos and other assets.
      stylesheets  # Stylesheets to override the Material Style.
      ...          # Other markdown pages or folders.
  ```
