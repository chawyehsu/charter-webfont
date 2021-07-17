charter-webfont
===============

> A webfont package for the Charter font

[![demo][demo-badge]][demo-url] [![npm][npm-badge]][npm-url] [![lcense][license-badge]][license-url] [![npm][download-badge]][npm-url] [![jsdelivr][jsdelivr-badge]][jsdelivr-url]

For more information about the font, see [Charter | Butterick's Practical Typography][charter-url] and [Bitstream Charter - Wikipedia][charter-wiki].

## Usage

#### Use jsDelivr

Put the jsDelivr `<link>` into your html head, then set your font-family to use `Charter`. For example:

```html
<html>
<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/charter-webfont@4/charter.min.css" />
  <style>
    body {
      font-family: "Charter", sans-serif;
    }
  </style>
</head>
<body>
  <!-- blablabla -->
</body>
</html>
```

#### Use NPM

First, install the package via npm or yarn.

```sh
npm install --save charter-webfont
```

Then import the css to your main css style file and set your font-family to use `Charter`.

```css
@import 'node_modules/charter-webfont/charter.css';
body {
  font-family: "Charter", sans-serif;
}
```

## License

**charter-webfont** © [Chawye Hsu](https://github.com/chawyehsu). Released under the [MIT](LICENSE) License.  
See [LICENSE.fonts.txt](LICENSE.fonts.txt) for the Charter typeface's license.

> [Blog](https://chawyehsu.com) · GitHub [@chawyehsu](https://github.com/chawyehsu) · Twitter [@chawyehsu](https://twitter.com/chawyehsu)


[demo-badge]: https://img.shields.io/badge/online-demo-blue.svg?style=flat-square
[demo-url]: https://chawyehsu.github.io/charter-webfont
[npm-badge]: https://img.shields.io/npm/v/charter-webfont.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/charter-webfont
[license-badge]: https://img.shields.io/npm/l/charter-webfont.svg?style=flat-square
[license-url]: LICENSE
[download-badge]: https://img.shields.io/npm/dt/charter-webfont.svg?style=flat-square
[jsdelivr-badge]: https://data.jsdelivr.com/v1/package/npm/charter-webfont/badge
[jsdelivr-url]: https://www.jsdelivr.com/package/npm/charter-webfont
[charter-url]: https://practicaltypography.com/charter.html
[charter-wiki]: https://en.wikipedia.org/wiki/Bitstream_Charter
