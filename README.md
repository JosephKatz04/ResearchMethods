# Lab Methods

This repository is a simple GitHub Pages site for dry lab and wet lab methods.

## How to Add a Method

Create a new Markdown file inside `_methods`.

For a wet lab page, use a path like:

```text
_methods/wet-lab/my-new-method.md
```

For a dry lab page, use a path like:

```text
_methods/dry-lab/my-new-method.md
```

Start the file with front matter:

```yaml
---
title: My New Method
category: wet-lab
summary: Short one-line description.
---
```

Then write the page in Markdown below the front matter.

## GitHub Pages

In the repository settings on GitHub, enable Pages and choose the main branch as the source. GitHub Pages will build the Markdown files with Jekyll automatically.

