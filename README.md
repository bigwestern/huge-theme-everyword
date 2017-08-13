# Everyword

The intention of this theme is to support a new content type called
epigrams.  The underlying css framework is bulma.

## Getting Started

Clone this repository to your hugo theme directory.

```
mkdir themes
cd themes
git clone https://github.com/beli3ver/hemingway2.git
```

## Configuration

This directory contains an example config file and the content for the demo.
It serves as an example setup for your documentation.

Copy the `config.toml` in the root directory of your website. Overwrite the existing config file if necessary.

__[config.toml](https://github.com/beli3ver/hemingway2/blob/master/exampleSite/config.toml)__:

```toml
languageCode = "en-us"
title = "Every word is a struggle"
baseurl = "http://studiogaudi.com/albert/"
theme = "everyword"
copyright = "&copy; <a href=\"https://github.com/beli3ver\">Albert Hall</a> 2017"
# disqusShortname = "shortname"
# googleAnalytics = ""
description = "Your personal description"
keywords = ["keyword1", "keyword2"]

[taxonomies]
tag = "tags"
category = "categories"

[params]
tagline = "by Albert Hall"

[[params.navlinks]]
url = "/about/"
title = "About"

[[params.navlinks]]
url = "/posts/"
title = "Posts"

[[params.social]]
url = "https://github.com/beli3ver"
fa_icon = "fa-github"

[[params.social]]
url = "https://gitlab.com/beli3ver"
fa_icon = "fa-gitlab"

[[params.social]]
url = "https://twitter.com/malkie16"
fa_icon = "fa-twitter"

[[params.social]]
url = "https://telegram.me/beli3ver"
fa_icon = "fa-telegram"

[[params.social]]
url = "/index.xml"
fa_icon = "fa-rss"
```

## Install and build theme

```
npm install --global gulp-cli
npm install
gulp
```
