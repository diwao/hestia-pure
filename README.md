# Hestia Pure

Hestia Pure is a simple Hugo theme built with Pure.css.

![screenshot](https://raw.githubusercontent.com/diwao/hestia-pure/master/static/image/theme/screenshot.png)

## Requirements

- Hugo 0.161.1 or newer
- No external asset build step is required

## Installation

Clone this repository into your Hugo site's `themes` directory:

```sh
git clone https://github.com/diwao/hestia-pure.git themes/hestia-pure
```

Then set the theme in your site configuration:

```toml
theme = "hestia-pure"
```

## Configuration

The recommended configuration shape is:

```toml
baseURL = "https://example.com/"
languageCode = "en-US"
title = "Example Site"
theme = "hestia-pure"

[params]
description = "A short description of your site."
keywords = "hugo,theme,blog"
twitter = "example"
github = "example"
facebook = "example"
googleAnalytics = "G-XXXXXXXXXX"
googleCustomSearch = "xxxxxxxxx"

[params.author]
name = "Your Name"
profile = "A short profile shown in the footer."
image = "image/theme/author.png"
```

For compatibility, the theme still reads the legacy lowercase `googleanalytics` and `googlecustomsearch` parameter names. Author information should use `[params.author]` on current Hugo versions; the legacy top-level `[author]` configuration is no longer supported.

## Development

CSS is maintained directly in `static/css/style.css`.

You can run the bundled example site with:

```sh
hugo server --source exampleSite --themesDir ../.. --theme hestia-pure --logLevel info
```

## License

MIT License

## Author

Daisuke Iwao
