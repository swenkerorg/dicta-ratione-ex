# @swenkerorg/dicta-ratione-ex

A tool for showing timestamp.

[![npm][npm-image]][npm-url]
[![GitHub Actions][github-actions-image-url]][github-actions-url]
[![standard][standard-image]][standard-url]
[![downloads][downloads-img]][npm-url]

[npm-image]: https://img.shields.io/npm/v/@swenkerorg/dicta-ratione-ex.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/@swenkerorg/dicta-ratione-ex
[github-actions-image-url]: https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fhenryhuang%2F@swenkerorg/dicta-ratione-ex%2Fbadge%3Fref%3Dmain&style=flat
[github-actions-url]: https://actions-badge.atrox.dev/henryhuang/@swenkerorg/dicta-ratione-ex/goto?ref=main
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[standard-url]: http://standardjs.com/
[downloads-img]: https://img.shields.io/npm/dm/@swenkerorg/dicta-ratione-ex.svg?style=flat-square

## Install

```

$ npm install @swenkerorg/dicta-ratione-ex -g

```

## Usage

### For command line

```
Usage: tsn [options]

Options:
  -d, --date_string       the date string
  -f, --format            the date string format, defined see
                          http://momentjs.com/docs/#/parsing/string-format/
  -s, --show_date_string  show date string                      [default: false]
  -h, --help              Show help                                    [boolean]
  -v, --version           Show version number                          [boolean]

Examples:
  tsn
  tsn -d 20161121
  tsn -d 2016-11-21 -f YYYY-MM-DD
```

### For Node API

```

let tsng = require('@swenkerorg/dicta-ratione-ex');

let ts = tsng(options);

```

options default:

```
{
    date_string: THE_DATE_NOW,
    format: '',
    show_date_string: false
}
```

## License

[MIT](LICENSE)

