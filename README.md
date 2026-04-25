# Pragmatic - Hugo theme
Pragmatic — a no-nonsense Hugo theme.

## Demo

*Coming soon*

## Installation
In your Hugo website directory, create a new folder named theme and clone the repo
```bash
$ mkdir themes
$ cd themes
$ git clone https://github.com/jackalbyte/hugo-pragmatic.git
```
Edit the `config.toml` file with `theme="pragmatic"`
For more information read the official [setup guide](https://gohugo.io/installation/) of Hugo.

## Config Options

### Site Params

```toml
[params]
  Subtitle    = "My site subtitle"
  description = "Site description"
  favicon     = "/favicon.ico"
  og_image    = "/og.png"
  mode        = "dark"              # color mode
  mainSections = ["posts"]
  excludedTypes = []
  customCSS   = ["css/custom.css"]
  customJS    = ["js/custom.js"]
  useCDN      = false               # load icons from CDN
  katex       = false               # enable KaTeX math
  mathjax     = false               # enable MathJax

  [[params.Social]]
    name = "GitHub"
    url  = "https://github.com/username"
    icon = "simple:github"          # prefix "simple:" for Simple Icons
```

### Page Front Matter

```yaml
hidden: false       # hide from listing
toc: true           # show table of contents
tldr: "Summary"     # TL;DR block
description: ""     # override site description
og_image: ""        # override OG image
tags: []
```
