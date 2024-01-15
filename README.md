# Augmented Far Eastern Script
[中文介绍](README_CN.md) *施工中

**Fanmade** typeface, greetings from Kugane.
![Title](preview/Title.svg)
> Reads 「クガネへ　よこそう」

## Glyphs Preview

![Glyphs](preview/Glyphs.svg)
> Excerpt from lyrics of [_Wayward Daughter (月下彼岸花 ～蛮神ツクヨミ討滅戦～)_](https://jp.finalfantasyxiv.com/blog/002393.html)

Currently supports:
- Hiragana/Katakana (identical)
- Numbers (0-9)
- Basic punctuations (personal design)
- and more (…?)

By default, this typeface features proportional glyphs in both horizontal and vertical typesetting. Due to the scripture design, it is highly recommended to use vertical typesetting. Most glyphs in this typeface have `vert` alternatives. 

## Opentype Features Support

Below are the currently supported Opentype features. 

### Standard Ligature `liga` (default on)

![liga](preview/liga.svg)
There's a set of ligatures that looks like double vowels kana in the official glyph table. I'm still not sure about how it is supposed to be used but here we go.

Note that not all double vowels are supposed to be combined, based on the meanings of the phrase. Therefore, please be cautious as in most popular design software, `liga` is on by default. I chose to use this feature table to differentiate from the `dlig` below.

### Discretionary Ligature `dlig` (default off)

![dlig](preview/dlig.svg)
There's a set of ligatures such as より, こと, さぶらい, ドマ, etc. in the official glyph table.

### Full-width `fwid` (default off)

By toggle this on, all kana in horizontal typesetting will be substituted with full-width alternatives. This is **NOT** recommended for use.
> In the source file, these are actually the original glyphs traced from the official glyph table. So basically, these are just the backup for current glyphs and serve as ref for font development.

### Vertical support `vert`, `vkna`, `vrt2` (automatic)

![Vertical](preview/Vertical.svg)
> Excerpt from lyrics of [_Sunrise (千年の暁 ～朱雀征魂戦～)_](https://jp.finalfantasyxiv.com/blog/002537.html)

These features should be automatically applied when using a modern design software.

### Stylistic Alternates `salt` (default off)

Currently only features a different personal design of full-width brackets `【】`, with vertical support.

### Stylistic Set 1 `ss01`: Alternative vertical punctuation layout form (default off)

A personal attempt to implement an alternative layout of vertical punctuation (直排行间标点). This style of punctuation application may be seen in antique Chinese books. Will move `、，。` to the side, i.e. between the rows. (colored in red in [vertical support preview](#vertical-support-vert-vkna-vrt2-automatic))

### Stylistic Set 2 `ss02`: Center-align vertical sutegana (default off)

Personally I feel that the sutegana in this specific typeface could be center-aligned in vertical typesetting, based on the style of the script. That's why this set exists.

## Source

- _Far Eastern Script_ from [_Encyclopaedia Eorzea II_](https://sqex.to/giPAn)

## Notice

Original design from [FINAL FANTASY XIV by SQUARE ENIX CO., LTD.](https://www.finalfantasyxiv.com/) Please do not use this fanmade font for any type of commercial use.

## Footnote

Please feel free to post any issues and/or suggestions here.