# Hugridway

Hugridway is a [hugo](https://github.com/spf13/hugo) theme that allows for easy generation of rich, grid-styled blogs. It is a derivative work, built on top of the original [hugrid](https://github.com/aerohub/hugrid) and [hemingway2](https://gitlab.com/beli3ver/hemingway2).

## Getting Started

Clone this repository to your hugo site themes directory. If you don't know what this means, take a look at Hugo's [quickstart guide](https://gohugo.io/overview/quickstart/).

```
cd themes && git clone https://github.com/uncommonhacks/hugridway.git
```

## Configuration 
Directions for rendering the site and site-wide parameters are set in the config file. Hugo supports `.toml`, `.yaml`, and `.json`; the included [exampleSite](https://github.com/uncommonhacks/hugridway/tree/master/exampleSite) includes a [`config.toml`](https://github.com/uncommonhacks/hugridway/blob/master/exampleSite/config.toml):

```toml
languageCode = "en-us"
title = "Site title"
baseURL = "http://baseUrl.org/"
theme = "hugridway"

contentdir = "content"
layoutdir = "layouts"
publishdir = "docs"
```

An exhaustive list of configurations options is included in the [wiki](https://github.com/uncommonhacks/hugridway/wiki).


## Building

To run an instance of your site locally on localhost, run:

```
$ hugo server -w
```

To build the site, simply run `hugo`.

## License

Hugridway is licensed under the [MIT License](LICENSE.md).

