# [`UTF-8`](https://en.wikipedia.org/wiki/UTF-8) and [unicode.org](https://unicode.org/)

Unicode - _Universal Coded Character Set_, is an [ASCII](https://en.wikipedia.org/wiki/ASCII) superset of roughly 150 thousand characters. UTF-8 - _Unicode Transformation Format 8-bit_, maps binary numbers, or bytes, to Unicode characters.

```sh
# Hardware
8 bits : 1 byte

# UTF-8
1 byte  : 1 character # ASCII
2 bytes : 1 character
3 bytes : 1 character
4 bytes : 1 character

# Font
X characters : 1 glyph
```

The term _Unicode_, from _en-cod-ing_, is not related to programming, and _Unilang_, meaning _lang_ - language and _uni_ - unification or internationalization, would have been a more fitting name.

## What's a character

Characters are elements of [language](https://en.wikipedia.org/wiki/language), and invisible [control characters](https://en.wikipedia.org/wiki/C0_and_C1_control_codes).

- [writing system](https://en.wikipedia.org/wiki/Writing_system) characters
  - `1234` and `abcd`
  - `𓁨𓎆𓏤𓏤𓏤` `𓁨` `𓎆` `𓏤` `𓏤` `𓏤` is `1000013` in ancient egyptian
  - control [`\n` newline](https://en.wikipedia.org/wiki/Newline), [`\b` backspace](https://en.wikipedia.org/wiki/Backspace)
- [signs](https://en.wikipedia.org/wiki/Sign) and symbols
  - `✝` latin cross
  - `︻デ═一` ASCII art
- [Optical Character Recognition](<https://en.wikipedia.org/wiki/Optical_Character_Recognition_(Unicode_block)>)
- [emoji](https://en.wikipedia.org/wiki/Emoji)

see: [unicode characters that are not writing system characters](https://en.wikipedia.org/wiki/Unicode_symbol)

_If some of these error, or [mojibake](https://en.wikipedia.org/wiki/Mojibake), then you're either, not on Unicode 2022 version 15 or later, or you don't have a supporting font loaded._

## Character encoding

Since the 1970s, a [byte](https://en.wikipedia.org/wiki/Byte), or eight digit binary number, is the smallest amount of data that can exist in computer hardware. A character is one or more bytes. Character encodings are software libraries, to encode - _write characters into bytes_, and decode - _read bytes into characters_.

1844 [Morse code](https://en.wikipedia.org/wiki/Morse_code). Latin characters => Ternary interpretation => International Morse code

```sh
SOS
00021112000
... --- ...

# There is no lowercase in Morse
HELLO, WORLD!
000020201002010021112110011222011211120102010021002101011
.... . .-.. .-.. --- --..--   .-- --- .-. .-.. -.. -.-.--
```

## Glyph rendering

A [font, font family, or typeface](https://en.wikipedia.org/wiki/Typeface), displays characters as glyphs.

- [fonts.google.com](https://fonts.google.com/)
- [Microsoft Typography](https://learn.microsoft.com/en-us/typography/)
- [fonts.adobe.com](https://fonts.adobe.com/)
<!-- https://www.ibm.com/plex/ -->

A font can have multiple [alternate glyphs](<https://en.wikipedia.org/wiki/Swash_(typography)>) for the same character. This is sometimes used in [handwriting fonts](https://fonts.google.com/?classification=Handwriting). A font can also merge, two or more characters, into a [ligature glyph](<https://en.wikipedia.org/wiki/Ligature_(writing)>). This is used to create [icons on the web](https://fonts.google.com/icons), and [programming ligatures](https://github.com/microsoft/cascadia-code). [Variable fonts are even capable of animations](https://fonts.google.com/knowledge/using_variable_fonts_on_the_web/interactive_animations_with_variable_fonts).

## Patch notes

[Unicode 2022](https://unicode.org/versions/Unicode15.0.0/) or version 15, includes, [one](https://en.wikipedia.org/wiki/Kawi_script), [two](https://en.wikipedia.org/wiki/Mundari_language) writing systems, [control characters for egyptian hieroglyphs](https://www.unicode.org/L2/L2021/21248-egyptian-controls.pdf), [8 astrology symbols](https://www.unicode.org/charts/PDF/Unicode-15.0/U150-1F700.pdf#page=5), [4000 chinse-japanese-korean characters](https://www.unicode.org/charts/PDF/Unicode-15.0/U150-31350.pdf), [some emojis](https://unicode.org/emoji/charts-15.0/emoji-released.html), [and more](https://www.unicode.org/charts/PDF/Unicode-15.0/).
