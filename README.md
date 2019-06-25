<!-- {{{1 -->

    File        : README.md
    Maintainer  : Felix C. Stegerman <flx@obfusk.net>
    Date        : 2019-06-25

    Copyright   : Copyright (C) 2019  Felix C. Stegerman
    Version     : v0.0.1
    License     : GPLv3+

<!-- }}}1 -->

## Description

kanji-strokes - 漢字と仮名の筆順 - stroke order for japanese text

## Usage

Download the source code (with git or you can get the .zip).

```bash
$ cd /some/path/to/kanji-strokes
$ python3 -m http.server --bind 127.0.0.1
```

Now go to http://localhost:8000 and input some text; it will be shown
in a stroke order font.

It even works on Android if you run it in Termux.

And of course you can put it on a web server as well if you want.

## License

### KanjiStrokeOrders_v4.001.ttf

MIT-like

https://www.nihilist.org.uk

### *.svg

GFDL & CC-BY-SA

https://en.wikipedia.org/wiki/Hiragana
https://en.wikipedia.org/wiki/Katakana

### index.html

[![GPLv3+](https://www.gnu.org/graphics/gplv3-127x51.png)](https://www.gnu.org/licenses/gpl-3.0.html)

<!-- vim: set tw=70 sw=2 sts=2 et fdm=marker : -->
