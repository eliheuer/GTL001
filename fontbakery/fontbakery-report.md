## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[10] GTL001-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2026 (HORIZONTAL ELLIPSIS)


	- 0x002A (ASTERISK)


	- 0x0023 (NUMBER SIGN)


	- 0x002F (SOLIDUS)


	- 0x005C (REVERSE SOLIDUS)


	- 0x007B (LEFT CURLY BRACKET)


	- 0x007D (RIGHT CURLY BRACKET)


	- 0x005B (LEFT SQUARE BRACKET)


	- 0x005D (RIGHT SQUARE BRACKET)


	- 0x201C (LEFT DOUBLE QUOTATION MARK)
 

	- And 245 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2022 eli heuer (https://github.com/eliheuer/gtl001)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 Eli Heuer (https://github.com/eliheuer/GTL001)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (700) and hhea ascent (1200) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 200 font units wide, non-breaking space named (uni00A0) is 300 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL 

	- And CR
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: eight	Contours detected: 1	Expected: 3

	- Glyph name: A	Contours detected: 1	Expected: 2

	- Glyph name: B	Contours detected: 1	Expected: 2 or 3

	- Glyph name: D	Contours detected: 1	Expected: 2

	- Glyph name: O	Contours detected: 1	Expected: 2

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: a	Contours detected: 1	Expected: 2

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: d	Contours detected: 1	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2 

	- And 22 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=239.0,Y=-2.0 (should be at baseline 0?)

	* T (U+0054): X=425.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=425.0,Y=699.0 (should be at ascender 700?)

	* t (U+0074): X=425.0,Y=699.0 (should be at cap-height 700?) 

	* And t (U+0074): X=425.0,Y=699.0 (should be at ascender 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<15.0,20.0>--<16.0,340.0>>

	* C (U+0043): L<<363.0,340.0>--<643.0,339.0>>

	* G (U+0047): L<<351.0,352.0>--<650.0,350.0>>

	* T (U+0054): L<<35.0,700.0>--<425.0,699.0>>

	* ampersand (U+0026): L<<590.0,0.0>--<239.0,-2.0>>

	* b (U+0062): L<<15.0,20.0>--<16.0,340.0>>

	* c (U+0063): L<<363.0,340.0>--<643.0,339.0>>

	* g (U+0067): L<<351.0,352.0>--<650.0,350.0>>

	* t (U+0074): L<<35.0,700.0>--<425.0,699.0>> 

	* And two (U+0032): L<<265.0,501.0>--<25.0,500.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 5 | 120 | 7 | 98 | 0 |
| 0% | 2% | 2% | 51% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
