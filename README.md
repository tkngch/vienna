# Vienna-Minimal

## Overview

Vienna-Minimal is a stripped-off version of [vienna
theme](https://github.com/keichi/vienna) for [Hugo](http://gohugo.io/).

Notable features are:

- Responsive design with bootstrap
- Source code highlighting with Pygments
- Side bar with author info and list of tags


## Installation

In your hugo site directory, run:

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/tkngch/vienna-minimal
```

## Configuration

You may specify following options in `config.toml` of your site to make use of
this theme's features.

```toml
baseurl = "Your site URL"
languageCode = "en-us"
title = "Your site title"
# Copyright notice. This is displayer in the footer.
copyright = "&copy; Copyright notice"

[params]
    contact = "Your contact link (ex. mailto:foo@example.com)"
    # Short subtitle/tagline. This is displayed in the header.
    subtitle = "Short subtitle/tagline of your blog"
```

## Usage

Use hugo's `-t vienna-minimal` or `--theme=vienna-minimal` option with hugo commands.
Example:

```shell
$ hugo server -t vienna-minimal -w -D
```
