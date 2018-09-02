# Open bases Jekyll Theme

This is a starter template for an open bases jekyll theme, based on these two
previous arts:

 - [alexcarpenter/material-jekyll-theme](http://alexcarpenter.github.io/material-jekyll-theme)
 - [squidfunk/mkdocs-material](https://github.com/squidfunk/mkdocs-material)

The goal is that the documentation, although being hosted in a different repository,
looks like the main [Open Bases](https://openbases.github.io) documentation.
In that any repository can render documentation alongside code in the "docs" folder
(or `github-pages` branch if you prefer) it's a reasonable strategy to, for each
repository, copy this template into a folder called "docs" and customize the 
[_config.yml](_config.yml) and documentation in the [pages](pages) folder 
as appropriate.

## Usage

### 1. Get the code

You can clone the repository right to where you want to host the docs:

```bash
git clone https://github.com/openbases/openbases-jekyll-theme.git docs
cd docs
```

### 2. Customize

You likely will want to use this theme to build directly on Github Pages for your
[Open Bases](https://openbases.github.io) component. This means editing the 
[_config.yml](_config.yml) and documentation in the [pages](pages) folder 
as appropriate.

### 3. Options

+ Theme
 - Green
  - Blue
  - Orange
  - Purple
  - Grey
+ Fixed Navigation
  - True
  - False

### N. Serve

Depending on how you installed jekyll:

```bash
jekyll serve
# or
bundle exec jekyll serve
```
