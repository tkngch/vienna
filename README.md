# Vienna

This is a stripped-off version of [vienna theme](https://github.com/keichi/vienna).

## Overview

Vienna is a simple and clean blog theme for [Hugo](http://gohugo.io/).
Notable features are:

- Simple and clean design
- Client side source code highlighting
- Social links (Twitter, Facebook, GitHub, LinkedIn, Instagram, Keybase) *Removed*
- Support for tags
- Analytics with Google Analytics or Mixpanel *Removed*
- Responsive design
- Font Awesome icons

## Installation

In your hugo site directory, run:

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/tkngch/vienna
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

Use hugo's `-t vienna` or `--theme=vienna` option with hugo commands.
Example:

```shell
$ hugo server -t vienna -w -D
```
