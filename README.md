# Kawkab Mono
Kawkab Mono (كوكب مونو) is a monospaced Arabic typeface. It's designed for code and text-editing in particular, and whenever having a fixed-pitch font is necessary, such as when composing tabular data using text. There's a dearth in monospaced Arabic fonts and Kawkab comes to fill a void in this niche.

Visit [Kawkab Mono's website](http://makkuk.com/kawkab-mono) for a demo and further details.

## Source Code
The source code is available in `.glyphs` which can be opened with the [Glyphs](https://www.glyphsapp.com/) app. Prior to v0.500, the source code was also available in `.ufo` format, and is no longer provided because of various bugs with the tools I'm using to export to UFO. To convert from `.glyphs` to `.ufo`, try [glyphs2ufo](https://github.com/googlei18n/glyphs2ufo).

## Contributing
A few things you could help with:

1. Refine existing outlines.
2. Add missing Arabic glyphs, including ligatures. Full list of Arabic characters:
	- [Arabic 0600–06FF](http://unicode.org/charts/PDF/U0600.pdf)
	- [Arabic Supplement 0750–077F](http://unicode.org/charts/PDF/U0750.pdf)
	- [Arabic Extended-A 08A0–08FF](http://unicode.org/charts/PDF/U08A0.pdf)
	- [Arabic Presentation Forms-A FB50–FDFF](http://unicode.org/charts/PDF/UFB50.pdf)
	- [Arabic Presentation Forms-B FE70–FEFF](http://unicode.org/charts/PDF/UFE70.pdf)
	- [Arabic Mathematical Alphabetic Symbols 1EE00–1EEFF](http://www.unicode.org/charts/PDF/U1EE00.pdf)

## Designing ligatures
The width of ligatures should either be the width of a single glyph, or the width of a single glyph multiplied by the number of characters that make up that ligature. This is to adhere to the fixed-width definition, or at least an "eventually fixed-width" philosophy.

## Opening the UFO in Glyphs App
Make sure to disable Automatic Alignment in Preferences -> User Settings before opening the UFO bundle. Otherwise, certain components will be misplaced.

## License
Kawkab Mono is available under the [SIL Open Font License v1.1](http://scripts.sil.org/OFL). See the accompanying OFL.txt file for details.

