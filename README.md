
# Build of this site

[![CI to build github pages](https://github.com/guillaume-gambs/gsquash.fr/workflows/CI%20to%20build%20github%20pages/badge.svg)](https://github.com/guillaume-gambs/gsquash.fr/actions?query=branch%3Amaster)

## Presentation

[![HUGO](https://raw.githubusercontent.com/gohugoio/gohugoioTheme/master/static/images/hugo-logo-wide.svg?sanitize=true)](https://raw.githubusercontent.com/gohugoio/gohugoioTheme/master/static/images/hugo-logo-wide.svg?sanitize=true)

This project is to share informations with other player of squash in grenoble. This wesite is accessible on [gsquash.fr](https://www.gsquash.fr)

We are happy to share with you the code in all transparency

## Website generation

[Hugo](https://gohugo.io) is used to generate the static site from the Markdown files in the [content](content) directory. You can find more information on how to write the pages here :

- [Documentation du template dot](http://demo.themefisher.com/dot-hugo/installation/install/) (doc most useful)
- [Documentation Hugo](https://gohugo.io/content-management/organization/)
- [Utilisation de Mermaid](https://learn.netlify.com/en/shortcodes/mermaid/)

Le site _Github Pages_ is rebuild on each _push_ on `master`. It is accessile on [dot](http://demo.themefisher.com/dot-hugo/installation/install/) or with the link in About section in the sidebar.

### Remarques

The theme use, [dot](https://github.com/themefisher/dot/)

## Update

After cloning the repo locally, you need to synchronize the Git sub-modules:

```console
git submodule update --init --recursive
```

To build and launch the site locally you just have to execute the following command :

```console
hugo server -D
```

All modified files are detected and recompiled. The site is automatically refreshed and can be accessed to the address [local address](http://localhost:1313/docs/).

## ORIGINAL README


A Fast and Flexible Static Site Generator built with love by [bep](https://github.com/bep), [spf13](http://spf13.com/) and [friends](https://github.com/gohugoio/hugo/graphs/contributors) in [Go][].

[Website](https://gohugo.io) |
[Forum](https://discourse.gohugo.io) |
[Documentation](https://gohugo.io/getting-started/) |
[Installation Guide](https://gohugo.io/getting-started/installing/) |
[Contribution Guide](CONTRIBUTING.md) |
[Twitter](https://twitter.com/gohugoio)

[![GoDoc](https://godoc.org/github.com/gohugoio/hugo?status.svg)](https://godoc.org/github.com/gohugoio/hugo)
[![Linux and macOS Build Status](https://api.travis-ci.org/gohugoio/hugo.svg?branch=master&label=Windows+and+Linux+and+macOS+build "Windows, Linux and macOS Build Status")](https://travis-ci.org/gohugoio/hugo)
[![Go Report Card](https://goreportcard.com/badge/github.com/gohugoio/hugo)](https://goreportcard.com/report/github.com/gohugoio/hugo)

For more info see [original repository](https://github.com/gohugoio/hugo)
