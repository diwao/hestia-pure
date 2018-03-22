# Hestia Pure
Hestia Pure is a simple hugo theme, based Pure.

![screenshot](https://raw.githubusercontent.com/diwao/hestia-pure/master/static/image/theme/screenshot.png)

## Installation & Usage
Clone this repository to your hugo theme directory.

```
$ git clone https://github.com/diwao/hestia-pure.git themes/
$ hugo server --theme=hestia-pure --buildDrafts --watch
```

## Configuration
In this theme you can add variables to your site config file. The following is the example config:

```
baseurl = "https://diwao.com/"
languageCode = "ja"
title = “diwao’s diary“
theme = 'hestia-pure'

[author]
 author = 'diwao'
 profile = 'I am a frontend engineer working in Sendai City, Japan.'
 image = 'image/theme/profile.jpg'

[Params]
 localeOgp = "ja"
 description = "This site is diwao's blog."
 keywords = "Sendai,Mac,iPhone,Web"
 twitter = "otaman517"
 github = "diwao"
 facebook = "diwaocom"
 googleanalytics = "UA-12345678-9"
 googlecustomsearch = "xxxxxxxxx"
```

## License
MIT License

## Author
Daisuke Iwao
