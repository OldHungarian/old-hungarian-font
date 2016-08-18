Old Hungarian support fonts
===========================

This is a FontForge compatible support font package supporting the
[Old Hungarian unicode block](http://www.unicode.org/charts/PDF/U10C80.pdf) added in Unicode version 8.0.

To build, simply open up the font file in FontForge and export it into your faviourite font type. Binaries
are also available from [oldhungarian.eu](oldhungarian.eu)

Note that when generating .ttf files in FontForge, for compatiblity reason please enable only the following options:

* TrueType Hints
* PS Glyph names
* OpenType

Do not use Apple as output as it doesn't support the ligatures properly.

Also note that the release contains two types of fonts, one has only the Old Hungarian glyphs, the other one also contains
supporting punctuation glyphs from the Lato font package. Use the full font package in case your applications doesn't properly
support fallbacks for punctuations, and use the slim version for other applications and the web.

Note: to generate the slim version of the font, simply delete all of the glyphs in the `U-0000`-`U-2E2E` range (except `U-200D`)
before generating the TTF.

The release ZIP was generated using https://www.web-font-generator.com/

Supported glyphs
================

The font supports all basic characters from the Old Hungarian block (U+10C80 - U+10CFF), and also some of the
more common ligatures. The list of supported glyphs can be found in [GLYPHS.md](GLYPHS.md)

It also includes the two punctuation used in Old Hungarian: U+2E41 and U+2E42

Licence
=======

The font is licenced as CC-BY-SA 3.0, and it is based on the following CC-BY-SA 3.0 licenced sources made by the
Rovas Foundation:

- https://upload.wikimedia.org/wikipedia/commons/c/c7/Szekely_Hungarian_Rovas_alphabet_Szekely_magyar_rovas_ABC.svg
- https://upload.wikimedia.org/wikipedia/commons/e/ee/1-1000_Rov%C3%A1ssz%C3%A1mok.svg
