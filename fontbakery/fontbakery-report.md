## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Voskresensky-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- u1CF30 (U+1CF30)</p>
<pre><code>- u1CF31 (U+1CF31)

- u1CF32 (U+1CF32)

- u1CF36 (U+1CF36)

- u1CF38 (U+1CF38)

- u1CF39 (U+1CF39)

- u1CF3A (U+1CF3A)

- u1CF3B (U+1CF3B)

- u1CF3C (U+1CF3C)

- u1CF3D (U+1CF3D)

- uniE001 (U+E001)

- uniE003 (U+E003)

- uniE005 (U+E005)

- uniEE50 (U+EE50)

- uniEE51 (U+EE51)

- uniEE52 (U+EE52)

- uniEE55 (U+EE55)

- uniEE56 (U+EE56)

- uniEE57 (U+EE57)

- uniEE58 (U+EE58)

- uniEE59 (U+EE59)

- uniEE5A (U+EE5A)

- uniEE5B (U+EE5B)

- uniF4E0 (U+F4E0)

- uniF4E1 (U+F4E1)

- uniF4E2 (U+F4E2)

- uniF4E3 (U+F4E3)

- uniF4E6 (U+F4E6)

- uniF4E7 (U+F4E7)

- uniF4E8 (U+F4E8)

- uniF4EC (U+F4EC)

- uniF4ED (U+F4ED)

- uniF4F3 (U+F4F3)
</code></pre>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[20] Voskresensky-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#case-mapping">case_mapping</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0481: CYRILLIC SMALL LETTER KOPPA</td>
<td align="left">U+0480: CYRILLIC CAPITAL LETTER KOPPA</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Does font file include unacceptable control character glyphs? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#control-chars">control_chars</a></summary>
    <div>







* 🔥 **FAIL** <p>The following unacceptable control characters were identified:
uni0013, uni001E, uni0008, uni0014, uni001F, uni0002, uni0006, uni0007, uni0019, uni0010, uni0001, uni000E, uni0012, uni0018, uni0015, uni000C, uni001C, uni0003, uni000F, uni0004, uni0017, uni0011, uni000A, uni000B, uni0016, uni001B, uni001D, uni0005, uni0009, uni001A</p>
 [code: unacceptable]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1185, but got 1080 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 893, but got 462 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ҁ</td>
<td align="left">cu_Cyrl (Church Slavic)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-license-OFL-copyright">googlefonts/license/OFL_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 2025 voskresensky project authors (<a href="https://github.com/slavonic/voskresensky">https://github.com/slavonic/voskresensky</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00AE (REGISTERED SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0304 (COMBINING MACRON)


- 0x030A (COMBINING RING ABOVE)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2022 (BULLET)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
u1CF33 (U+1CF33), u1CF34 (U+1CF34), u1CF35 (U+1CF35), u1CF37 (U+1CF37), u1CF3E (U+1CF3E), u1CF3F (U+1CF3F), u1CF40 (U+1CF40), u1CF41 (U+1CF41), u1CF42 (U+1CF42), u1CF43 (U+1CF43), u1CF44 (U+1CF44), u1CF45 (U+1CF45), u1CF46 (U+1CF46) and uni034F (U+034F)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
uni0483.salt1 (U+E013), uni0483.salt2 (U+E014), uni0483.salt3 (U+E015), uni0487.salt (U+E01F), uni2DE0 (U+2DE0), uni2DE1 (U+2DE1), uni2DE2 (U+2DE2), uni2DE3 (U+2DE3), uni2DE4 (U+2DE4), uni2DE5 (U+2DE5), uni2DE6 (U+2DE6), uni2DE7 (U+2DE7), uni2DE8 (U+2DE8), uni2DE9 (U+2DE9), uni2DEA (U+2DEA), uni2DEB (U+2DEB), uni2DEC (U+2DEC), uni2DED (U+2DED), uni2DEE (U+2DEE), uni2DEF (U+2DEF), uni2DF0 (U+2DF0), uni2DF1 (U+2DF1), uni2DF3 (U+2DF3), uni2DF4 (U+2DF4), uni2DF6 (U+2DF6), uni2DF7 (U+2DF7), uni2DFA (U+2DFA), uni2DFB (U+2DFB), uni2DFD (U+2DFD), uniA66F (U+A66F), uniA67C (U+A67C), uniA67D (U+A67D), uniF4E4 (U+F4E4), uniF4E5 (U+F4E5), uniF4E9 (U+F4E9), uniF4EA (U+F4EA), uniF4EB (U+F4EB), uniF4EE (U+F4EE), uniF4EF (U+F4EF), uniF4F0 (U+F4F0), uniF4F1 (U+F4F1), uniF4F2 (U+F4F2), uniF4F4 (U+F4F4), uniF4F6 (U+F4F6), uniF4F7 (U+F4F7), uniF4FA (U+F4FA), uniF4FB (U+F4FB) and uniF4FD (U+F4FD)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni0002	Contours detected: 5	Expected: 0

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: uni0400	Contours detected: 6	Expected: 2

- Glyph name: uni0401	Contours detected: 7	Expected: 3

- Glyph name: uni0402	Contours detected: 6	Expected: 1

- Glyph name: uni0403	Contours detected: 4	Expected: 2

- Glyph name: uni0404	Contours detected: 5	Expected: 1

- Glyph name: uni0405	Contours detected: 4	Expected: 1

- Glyph name: uni0406	Contours detected: 2	Expected: 1

- Glyph name: uni0407	Contours detected: 4	Expected: 3

- Glyph name: uni0409	Contours detected: 5	Expected: 2

- Glyph name: uni040A	Contours detected: 5	Expected: 2

- Glyph name: uni040B	Contours detected: 6	Expected: 1

- Glyph name: uni040C	Contours detected: 7	Expected: 2

- Glyph name: uni040D	Contours detected: 4	Expected: 2

- Glyph name: uni040E	Contours detected: 4	Expected: 2

- Glyph name: uni040F	Contours detected: 4	Expected: 1

- Glyph name: uni0410	Contours detected: 5	Expected: 2

- Glyph name: uni0411	Contours detected: 5	Expected: 2

- Glyph name: uni0412	Contours detected: 5	Expected: 3

- Glyph name: uni0413	Contours detected: 3	Expected: 1

- Glyph name: uni0414	Contours detected: 6	Expected: 2

- Glyph name: uni0415	Contours detected: 5	Expected: 1

- Glyph name: uni0416	Contours detected: 7	Expected: 1

- Glyph name: uni0417	Contours detected: 4	Expected: 1

- Glyph name: uni0418	Contours detected: 3	Expected: 1

- Glyph name: uni0419	Contours detected: 4	Expected: 2

- Glyph name: uni041A	Contours detected: 6	Expected: 1

- Glyph name: uni041B	Contours detected: 3	Expected: 1

- Glyph name: uni041C	Contours detected: 4	Expected: 1

- Glyph name: uni041D	Contours detected: 3	Expected: 1

- Glyph name: uni041E	Contours detected: 4	Expected: 2

- Glyph name: uni041F	Contours detected: 3	Expected: 1

- Glyph name: uni0420	Contours detected: 3	Expected: 1 or 2

- Glyph name: uni0421	Contours detected: 4	Expected: 1

- Glyph name: uni0422	Contours detected: 4	Expected: 1

- Glyph name: uni0423	Contours detected: 3	Expected: 1

- Glyph name: uni0424	Contours detected: 7	Expected: 3

- Glyph name: uni0425	Contours detected: 4	Expected: 1

- Glyph name: uni0426	Contours detected: 4	Expected: 1

- Glyph name: uni0427	Contours detected: 4	Expected: 1

- Glyph name: uni0428	Contours detected: 4	Expected: 1

- Glyph name: uni0429	Contours detected: 5	Expected: 1

- Glyph name: uni042A	Contours detected: 5	Expected: 2

- Glyph name: uni042B	Contours detected: 6	Expected: 3

- Glyph name: uni042C	Contours detected: 4	Expected: 2

- Glyph name: uni042D	Contours detected: 5	Expected: 1

- Glyph name: uni042E	Contours detected: 4	Expected: 2

- Glyph name: uni042F	Contours detected: 4	Expected: 2

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni043A	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni0460	Contours detected: 4	Expected: 1

- Glyph name: uni0462	Contours detected: 7	Expected: 2

- Glyph name: uni0464	Contours detected: 6	Expected: 1

- Glyph name: uni0466	Contours detected: 5	Expected: 2

- Glyph name: uni0468	Contours detected: 6	Expected: 2

- Glyph name: uni046A	Contours detected: 6	Expected: 2

- Glyph name: uni046C	Contours detected: 7	Expected: 2

- Glyph name: uni046E	Contours detected: 5	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0470	Contours detected: 4	Expected: 1

- Glyph name: uni0472	Contours detected: 7	Expected: 3

- Glyph name: uni0474	Contours detected: 3	Expected: 1

- Glyph name: uni0476	Contours detected: 5	Expected: 3

- Glyph name: uni0478	Contours detected: 6	Expected: 3

- Glyph name: uni047A	Contours detected: 4	Expected: 2

- Glyph name: uni047B	Contours detected: 4	Expected: 2

- Glyph name: uni047C	Contours detected: 6	Expected: 3

- Glyph name: uni047E	Contours detected: 8	Expected: 2

- Glyph name: uni0490	Contours detected: 3	Expected: 1

- Glyph name: uni04A4	Contours detected: 4	Expected: 1

- Glyph name: uni2116	Contours detected: 6	Expected: 3 or 4

- Glyph name: element	Contours detected: 2	Expected: 1

- Glyph name: suchthat	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: element	Contours detected: 2	Expected: 1

- Glyph name: suchthat	Contours detected: 2	Expected: 1

- Glyph name: uni0002	Contours detected: 5	Expected: 0

- Glyph name: uni0400	Contours detected: 6	Expected: 2

- Glyph name: uni0401	Contours detected: 7	Expected: 3

- Glyph name: uni0402	Contours detected: 6	Expected: 1

- Glyph name: uni0403	Contours detected: 4	Expected: 2

- Glyph name: uni0404	Contours detected: 5	Expected: 1

- Glyph name: uni0405	Contours detected: 4	Expected: 1

- Glyph name: uni0406	Contours detected: 2	Expected: 1

- Glyph name: uni0407	Contours detected: 4	Expected: 3

- Glyph name: uni0409	Contours detected: 5	Expected: 2

- Glyph name: uni040A	Contours detected: 5	Expected: 2

- Glyph name: uni040B	Contours detected: 6	Expected: 1

- Glyph name: uni040C	Contours detected: 7	Expected: 2

- Glyph name: uni040D	Contours detected: 4	Expected: 2

- Glyph name: uni040E	Contours detected: 4	Expected: 2

- Glyph name: uni040F	Contours detected: 4	Expected: 1

- Glyph name: uni0410	Contours detected: 5	Expected: 2

- Glyph name: uni0411	Contours detected: 5	Expected: 2

- Glyph name: uni0412	Contours detected: 5	Expected: 3

- Glyph name: uni0413	Contours detected: 3	Expected: 1

- Glyph name: uni0414	Contours detected: 6	Expected: 2

- Glyph name: uni0415	Contours detected: 5	Expected: 1

- Glyph name: uni0416	Contours detected: 7	Expected: 1

- Glyph name: uni0417	Contours detected: 4	Expected: 1

- Glyph name: uni0418	Contours detected: 3	Expected: 1

- Glyph name: uni0419	Contours detected: 4	Expected: 2

- Glyph name: uni041A	Contours detected: 6	Expected: 1

- Glyph name: uni041B	Contours detected: 3	Expected: 1

- Glyph name: uni041C	Contours detected: 4	Expected: 1

- Glyph name: uni041D	Contours detected: 3	Expected: 1

- Glyph name: uni041E	Contours detected: 4	Expected: 2

- Glyph name: uni041F	Contours detected: 3	Expected: 1

- Glyph name: uni0420	Contours detected: 3	Expected: 1 or 2

- Glyph name: uni0421	Contours detected: 4	Expected: 1

- Glyph name: uni0422	Contours detected: 4	Expected: 1

- Glyph name: uni0423	Contours detected: 3	Expected: 1

- Glyph name: uni0424	Contours detected: 7	Expected: 3

- Glyph name: uni0425	Contours detected: 4	Expected: 1

- Glyph name: uni0426	Contours detected: 4	Expected: 1

- Glyph name: uni0427	Contours detected: 4	Expected: 1

- Glyph name: uni0428	Contours detected: 4	Expected: 1

- Glyph name: uni0429	Contours detected: 5	Expected: 1

- Glyph name: uni042A	Contours detected: 5	Expected: 2

- Glyph name: uni042B	Contours detected: 6	Expected: 3

- Glyph name: uni042C	Contours detected: 4	Expected: 2

- Glyph name: uni042D	Contours detected: 5	Expected: 1

- Glyph name: uni042E	Contours detected: 4	Expected: 2

- Glyph name: uni042F	Contours detected: 4	Expected: 2

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni043A	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni0460	Contours detected: 4	Expected: 1

- Glyph name: uni0462	Contours detected: 7	Expected: 2

- Glyph name: uni0464	Contours detected: 6	Expected: 1

- Glyph name: uni0466	Contours detected: 5	Expected: 2

- Glyph name: uni0468	Contours detected: 6	Expected: 2

- Glyph name: uni046A	Contours detected: 6	Expected: 2

- Glyph name: uni046C	Contours detected: 7	Expected: 2

- Glyph name: uni046E	Contours detected: 5	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0470	Contours detected: 4	Expected: 1

- Glyph name: uni0472	Contours detected: 7	Expected: 3

- Glyph name: uni0474	Contours detected: 3	Expected: 1

- Glyph name: uni0476	Contours detected: 5	Expected: 3

- Glyph name: uni0478	Contours detected: 6	Expected: 3

- Glyph name: uni047A	Contours detected: 4	Expected: 2

- Glyph name: uni047B	Contours detected: 4	Expected: 2

- Glyph name: uni047C	Contours detected: 6	Expected: 3

- Glyph name: uni047E	Contours detected: 8	Expected: 2

- Glyph name: uni0490	Contours detected: 3	Expected: 1

- Glyph name: uni04A4	Contours detected: 4	Expected: 1

- Glyph name: uni2116	Contours detected: 6	Expected: 3 or 4

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 664 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 800:
plus</p>
<p>Width = 739:
less, greater</p>
<p>Width = 850:
equal</p>
<p>Width = 658:
logicalnot</p>
<p>Width = 452:
uni2214, uni2213</p>
<p>Width = 609:
uni223B</p>
<p>Width = 604:
similar</p>
<p>Width = 717:
uni223D</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+0001 : try adding symbols</li>
<li>U+0002 : try adding symbols</li>
<li>U+0003 : try adding symbols</li>
<li>U+0004 : try adding symbols</li>
<li>U+0005 : try adding symbols</li>
<li>U+0006 : try adding symbols</li>
<li>U+0007 : try adding symbols</li>
<li>U+0008 : try adding symbols</li>
<li>U+0009 : try adding symbols</li>
<li>U+000A : try adding symbols</li>
<li>U+000B : try adding symbols</li>
<li>U+000C : try adding symbols</li>
<li>U+000E : try adding symbols</li>
<li>U+000F : try adding symbols</li>
<li>U+0010 : try adding symbols</li>
<li>U+0011 : try adding symbols</li>
<li>U+0012 : try adding symbols</li>
<li>U+0013 : try adding symbols</li>
<li>U+0014 : try adding symbols</li>
<li>U+0015 : try adding symbols</li>
<li>U+0016 : try adding symbols</li>
<li>U+0017 : try adding symbols</li>
<li>U+0018 : try adding symbols</li>
<li>U+0019 : try adding symbols</li>
<li>U+001A : try adding symbols</li>
<li>U+001B : try adding symbols</li>
<li>U+001C : try adding symbols</li>
<li>U+001D : try adding one of: symbols, balinese</li>
<li>U+001E : try adding symbols</li>
<li>U+001F : try adding symbols</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, malayalam, tai-le, coptic, tifinagh, syriac, duployan, old-permic, todhri, hebrew</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+10FB GEORGIAN PARAGRAPH SEPARATOR: try adding one of: glagolitic, georgian</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: bhaiksuki, manichaean, newa, saurashtra, meetei-mayek, phags-pa, sogdian, balinese, syriac, khudawadi, rejang, tai-tham, bengali, avestan, gurmukhi, myanmar, sinhala, grantha, tagalog, psalter-pahlavi, pahawh-hmong, limbu, chakma, tai-viet, hatran, syloti-nagri, masaram-gondi, khojki, tifinagh, lao, kaithi, siddham, cham, hanunoo, brahmi, mahajani, hanifi-rohingya, tibetan, gujarati, mongolian, kharoshthi, tagbanwa, oriya, tai-le, tamil, tirhuta, zanabazar-square, kayah-li, takri, lepcha, devanagari, duployan, modi, kannada, yi, mandaic, khmer, batak, telugu, arabic, dogra, gunjala-gondi, javanese, buginese, malayalam, new-tai-lue, sundanese, warang-citi, thai, sharada, nko, buhid, thaana, hebrew</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: bhaiksuki, manichaean, newa, old-hungarian, meetei-mayek, phags-pa, saurashtra, sogdian, balinese, syriac, khudawadi, rejang, tai-tham, bengali, avestan, gurmukhi, myanmar, sinhala, grantha, tagalog, psalter-pahlavi, pahawh-hmong, limbu, chakma, tai-viet, syloti-nagri, masaram-gondi, khojki, tifinagh, lao, kaithi, siddham, cham, hanunoo, brahmi, mahajani, hanifi-rohingya, tibetan, gujarati, mongolian, kharoshthi, tagbanwa, oriya, tai-le, tamil, tirhuta, zanabazar-square, kayah-li, takri, lepcha, devanagari, duployan, modi, kannada, yi, mandaic, khmer, batak, telugu, arabic, dogra, gunjala-gondi, javanese, buginese, malayalam, new-tai-lue, sundanese, warang-citi, thai, sharada, nko, buhid, thaana, hebrew</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205D TRICOLON: try adding one of: meroitic-hieroglyphs, meroitic, old-hungarian, carian</li>
<li>U+2208 ELEMENT OF: try adding math</li>
<li>U+220B CONTAINS AS MEMBER: try adding math</li>
<li>U+2213 MINUS-OR-PLUS SIGN: try adding math</li>
<li>U+2214 DOT PLUS: try adding math</li>
<li>U+223B HOMOTHETIC: try adding math</li>
<li>U+223C TILDE OPERATOR: try adding math</li>
<li>U+223D REVERSED TILDE: try adding math</li>
<li>U+2282 SUBSET OF: try adding math</li>
<li>U+2283 SUPERSET OF: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: symbols, caucasian-albanian, coptic, syriac, myanmar, sinhala, khojki, tifinagh, siddham, osage, elbasan, tagbanwa, tai-le, tamil, duployan, old-permic, mende-kikakui, yi, mandaic, batak, marchen, javanese, malayalam, new-tai-lue, warang-citi, sundanese, bhaiksuki, manichaean, khudawadi, gurmukhi, grantha, tagalog, music, pahawh-hmong, hanunoo, kharoshthi, devanagari, canadian-aboriginal, math, thai, saurashtra, meetei-mayek, balinese, tai-tham, rejang, limbu, masaram-gondi, cham, mahajani, brahmi, tibetan, bassa-vah, wancho, oriya, zanabazar-square, kayah-li, soyombo, adlam, takri, ahom, kannada, telugu, sharada, nko, armenian, thaana, newa, phags-pa, sogdian, miao, bengali, psalter-pahlavi, chakma, tai-viet, syloti-nagri, lao, kaithi, hanifi-rohingya, gujarati, mongolian, tirhuta, lepcha, modi, khmer, dogra, gunjala-gondi, buginese, buhid, hebrew</li>
<li>U+261E WHITE RIGHT POINTING INDEX: try adding symbols</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+2627 CHI RHO: try adding symbols</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+2795 HEAVY PLUS SIGN: not included in any glyphset definition</li>
<li>U+2E0F PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E43 DASH WITH LEFT UPTURN: try adding glagolitic</li>
<li>U+2E49 DOUBLE STACKED COMMA: not included in any glyphset definition</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E013 : not included in any glyphset definition</li>
<li>U+E014 : not included in any glyphset definition</li>
<li>U+E015 : not included in any glyphset definition</li>
<li>U+E01F : not included in any glyphset definition</li>
<li>U+E2F1 : not included in any glyphset definition</li>
<li>U+E38F : not included in any glyphset definition</li>
<li>U+E464 : not included in any glyphset definition</li>
<li>U+E465 : not included in any glyphset definition</li>
<li>U+E473 : not included in any glyphset definition</li>
<li>U+E474 : not included in any glyphset definition</li>
<li>U+E500 : not included in any glyphset definition</li>
<li>U+E501 : not included in any glyphset definition</li>
<li>U+E925 : not included in any glyphset definition</li>
<li>U+EA1B : not included in any glyphset definition</li>
<li>U+EA57 : not included in any glyphset definition</li>
<li>U+EA80 : not included in any glyphset definition</li>
<li>U+EA99 : not included in any glyphset definition</li>
<li>U+EA9C : not included in any glyphset definition</li>
<li>U+EA9F : not included in any glyphset definition</li>
<li>U+EAC5 : not included in any glyphset definition</li>
<li>U+EAFA : not included in any glyphset definition</li>
<li>U+EAFD : not included in any glyphset definition</li>
<li>U+EB01 : not included in any glyphset definition</li>
<li>U+EB0D : not included in any glyphset definition</li>
<li>U+EB51 : not included in any glyphset definition</li>
<li>U+EB52 : not included in any glyphset definition</li>
<li>U+EB53 : not included in any glyphset definition</li>
<li>U+EB54 : not included in any glyphset definition</li>
<li>U+EB55 : not included in any glyphset definition</li>
<li>U+EB56 : not included in any glyphset definition</li>
<li>U+EB57 : not included in any glyphset definition</li>
<li>U+EB5F : not included in any glyphset definition</li>
<li>U+EC22 : not included in any glyphset definition</li>
<li>U+EE50 : not included in any glyphset definition</li>
<li>U+EE51 : not included in any glyphset definition</li>
<li>U+EE52 : not included in any glyphset definition</li>
<li>U+EE53 : not included in any glyphset definition</li>
<li>U+EE54 : not included in any glyphset definition</li>
<li>U+EE55 : not included in any glyphset definition</li>
<li>U+EE56 : not included in any glyphset definition</li>
<li>U+EE57 : not included in any glyphset definition</li>
<li>U+EE58 : not included in any glyphset definition</li>
<li>U+EE59 : not included in any glyphset definition</li>
<li>U+EE5A : not included in any glyphset definition</li>
<li>U+EE5B : not included in any glyphset definition</li>
<li>U+EE5C : not included in any glyphset definition</li>
<li>U+EE5D : not included in any glyphset definition</li>
<li>U+EE5E : not included in any glyphset definition</li>
<li>U+EE70 : not included in any glyphset definition</li>
<li>U+EE71 : not included in any glyphset definition</li>
<li>U+EE72 : not included in any glyphset definition</li>
<li>U+EE73 : not included in any glyphset definition</li>
<li>U+EE74 : not included in any glyphset definition</li>
<li>U+EE75 : not included in any glyphset definition</li>
<li>U+EE76 : not included in any glyphset definition</li>
<li>U+EE77 : not included in any glyphset definition</li>
<li>U+EE78 : not included in any glyphset definition</li>
<li>U+EE79 : not included in any glyphset definition</li>
<li>U+EE7A : not included in any glyphset definition</li>
<li>U+EE7B : not included in any glyphset definition</li>
<li>U+EE7C : not included in any glyphset definition</li>
<li>U+EE7D : not included in any glyphset definition</li>
<li>U+EE7E : not included in any glyphset definition</li>
<li>U+EE7F : not included in any glyphset definition</li>
<li>U+EE80 : not included in any glyphset definition</li>
<li>U+EE81 : not included in any glyphset definition</li>
<li>U+EE82 : not included in any glyphset definition</li>
<li>U+EE83 : not included in any glyphset definition</li>
<li>U+EE84 : not included in any glyphset definition</li>
<li>U+EE85 : not included in any glyphset definition</li>
<li>U+EE86 : not included in any glyphset definition</li>
<li>U+EE87 : not included in any glyphset definition</li>
<li>U+EE88 : not included in any glyphset definition</li>
<li>U+EE89 : not included in any glyphset definition</li>
<li>U+EE8A : not included in any glyphset definition</li>
<li>U+EE8B : not included in any glyphset definition</li>
<li>U+EE8C : not included in any glyphset definition</li>
<li>U+EE8D : not included in any glyphset definition</li>
<li>U+EE8E : not included in any glyphset definition</li>
<li>U+EE8F : not included in any glyphset definition</li>
<li>U+EE90 : not included in any glyphset definition</li>
<li>U+EE91 : not included in any glyphset definition</li>
<li>U+EE92 : not included in any glyphset definition</li>
<li>U+EE93 : not included in any glyphset definition</li>
<li>U+EE94 : not included in any glyphset definition</li>
<li>U+EE95 : not included in any glyphset definition</li>
<li>U+EE96 : not included in any glyphset definition</li>
<li>U+EE97 : not included in any glyphset definition</li>
<li>U+EE98 : not included in any glyphset definition</li>
<li>U+EE99 : not included in any glyphset definition</li>
<li>U+EE9A : not included in any glyphset definition</li>
<li>U+EE9B : not included in any glyphset definition</li>
<li>U+EE9C : not included in any glyphset definition</li>
<li>U+EE9D : not included in any glyphset definition</li>
<li>U+EE9E : not included in any glyphset definition</li>
<li>U+EE9F : not included in any glyphset definition</li>
<li>U+EEA0 : not included in any glyphset definition</li>
<li>U+EEA1 : not included in any glyphset definition</li>
<li>U+EEA2 : not included in any glyphset definition</li>
<li>U+EEA3 : not included in any glyphset definition</li>
<li>U+EEA4 : not included in any glyphset definition</li>
<li>U+EEA5 : not included in any glyphset definition</li>
<li>U+EEA6 : not included in any glyphset definition</li>
<li>U+EEA7 : not included in any glyphset definition</li>
<li>U+EEA8 : not included in any glyphset definition</li>
<li>U+EEAA : not included in any glyphset definition</li>
<li>U+EEAB : not included in any glyphset definition</li>
<li>U+EEAC : not included in any glyphset definition</li>
<li>U+EEAD : not included in any glyphset definition</li>
<li>U+EEAE : not included in any glyphset definition</li>
<li>U+EEAF : not included in any glyphset definition</li>
<li>U+EEB0 : not included in any glyphset definition</li>
<li>U+EEB1 : not included in any glyphset definition</li>
<li>U+EEB2 : not included in any glyphset definition</li>
<li>U+EEB3 : not included in any glyphset definition</li>
<li>U+EEB4 : not included in any glyphset definition</li>
<li>U+EEB5 : not included in any glyphset definition</li>
<li>U+EEB6 : not included in any glyphset definition</li>
<li>U+EEB7 : not included in any glyphset definition</li>
<li>U+EEB8 : not included in any glyphset definition</li>
<li>U+EEB9 : not included in any glyphset definition</li>
<li>U+EEBA : not included in any glyphset definition</li>
<li>U+EEBB : not included in any glyphset definition</li>
<li>U+EEBC : not included in any glyphset definition</li>
<li>U+EEBD : not included in any glyphset definition</li>
<li>U+EEBE : not included in any glyphset definition</li>
<li>U+EEBF : not included in any glyphset definition</li>
<li>U+F4E0 : not included in any glyphset definition</li>
<li>U+F4E1 : not included in any glyphset definition</li>
<li>U+F4E2 : not included in any glyphset definition</li>
<li>U+F4E3 : not included in any glyphset definition</li>
<li>U+F4E4 : not included in any glyphset definition</li>
<li>U+F4E5 : not included in any glyphset definition</li>
<li>U+F4E6 : not included in any glyphset definition</li>
<li>U+F4E7 : not included in any glyphset definition</li>
<li>U+F4E8 : not included in any glyphset definition</li>
<li>U+F4E9 : not included in any glyphset definition</li>
<li>U+F4EA : not included in any glyphset definition</li>
<li>U+F4EB : not included in any glyphset definition</li>
<li>U+F4EC : not included in any glyphset definition</li>
<li>U+F4ED : not included in any glyphset definition</li>
<li>U+F4EE : not included in any glyphset definition</li>
<li>U+F4EF : not included in any glyphset definition</li>
<li>U+F4F0 : not included in any glyphset definition</li>
<li>U+F4F1 : not included in any glyphset definition</li>
<li>U+F4F2 : not included in any glyphset definition</li>
<li>U+F4F3 : not included in any glyphset definition</li>
<li>U+F4F4 : not included in any glyphset definition</li>
<li>U+F4F6 : not included in any glyphset definition</li>
<li>U+F4F7 : not included in any glyphset definition</li>
<li>U+F4FA : not included in any glyphset definition</li>
<li>U+F4FB : not included in any glyphset definition</li>
<li>U+F4FD : not included in any glyphset definition</li>
<li>U+F680 : not included in any glyphset definition</li>
<li>U+F681 : not included in any glyphset definition</li>
<li>U+F682 : not included in any glyphset definition</li>
<li>U+F683 : not included in any glyphset definition</li>
<li>U+F684 : not included in any glyphset definition</li>
<li>U+F685 : not included in any glyphset definition</li>
<li>U+F686 : not included in any glyphset definition</li>
<li>U+F687 : not included in any glyphset definition</li>
<li>U+F688 : not included in any glyphset definition</li>
<li>U+F0149 : not included in any glyphset definition</li>
<li>U+F014E : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>latin-ext</code>, <code>znamenny</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̋ j̀ j́ j̃ j̈ j̑ і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ì í ĩ ĭ i̇ ï ȉ ȋ i̾ i҃ i҄ i҅ i҆ i҇ iⷠ iⷡ iⷢ iⷣ iⷤ iⷥ</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni0402 (U+0402): B&lt;&lt;150.0,561.0&gt;-&lt;153.0,591.0&gt;-&lt;163.0,591.0&gt;&gt;/L&lt;&lt;163.0,591.0&gt;--&lt;66.0,595.0&gt;&gt; = 2.3613746581755626

* uni0404 (U+0404): B&lt;&lt;105.0,169.0&gt;-&lt;127.0,89.0&gt;-&lt;153.0,21.0&gt;&gt;/B&lt;&lt;153.0,21.0&gt;-&lt;152.0,28.0&gt;-&lt;152.0,35.0&gt;&gt; = 12.794399390765186

* uni0405 (U+0405): L&lt;&lt;134.0,495.0&gt;--&lt;134.0,506.0&gt;&gt;/L&lt;&lt;134.0,506.0&gt;--&lt;125.0,469.0&gt;&gt; = 13.67130713219584

* uni0407 (U+0407): B&lt;&lt;102.0,-69.0&gt;-&lt;98.0,-95.0&gt;-&lt;91.0,-94.0&gt;&gt;/B&lt;&lt;91.0,-94.0&gt;-&lt;102.0,-96.0&gt;-&lt;118.0,-96.0&gt;&gt; = 2.174744114610005

* uni040B (U+040B): B&lt;&lt;151.0,561.0&gt;-&lt;152.0,591.0&gt;-&lt;163.0,591.0&gt;&gt;/L&lt;&lt;163.0,591.0&gt;--&lt;66.0,595.0&gt;&gt; = 2.3613746581755626

* uni041E (U+041E): B&lt;&lt;494.0,23.0&gt;-&lt;494.0,3.0&gt;-&lt;490.0,-16.0&gt;&gt;/B&lt;&lt;490.0,-16.0&gt;-&lt;508.0,28.0&gt;-&lt;517.5,88.0&gt;&gt; = 10.36036561758435

* uni0421 (U+0421): B&lt;&lt;116.0,465.0&gt;-&lt;116.0,468.0&gt;-&lt;116.0,472.0&gt;&gt;/L&lt;&lt;116.0,472.0&gt;--&lt;110.0,448.0&gt;&gt; = 14.036243467926484

* uni042B (U+042B): B&lt;&lt;762.0,-69.0&gt;-&lt;758.0,-95.0&gt;-&lt;751.0,-94.0&gt;&gt;/B&lt;&lt;751.0,-94.0&gt;-&lt;762.0,-96.0&gt;-&lt;778.0,-96.0&gt;&gt; = 2.174744114610005

* uni0432 (U+0432): B&lt;&lt;93.5,297.0&gt;-&lt;87.0,360.0&gt;-&lt;81.0,416.0&gt;&gt;/B&lt;&lt;81.0,416.0&gt;-&lt;81.0,414.0&gt;-&lt;81.0,417.0&gt;&gt; = 6.115503566285384

* uni0440 (U+0440): B&lt;&lt;154.5,-643.0&gt;-&lt;153.0,-695.0&gt;-&lt;149.0,-749.0&gt;&gt;/B&lt;&lt;149.0,-749.0&gt;-&lt;145.0,-659.0&gt;-&lt;143.5,-562.5&gt;&gt; = 6.781199178871924

* uni0462 (U+0462): B&lt;&lt;151.0,561.0&gt;-&lt;152.0,591.0&gt;-&lt;163.0,591.0&gt;&gt;/L&lt;&lt;163.0,591.0&gt;--&lt;66.0,595.0&gt;&gt; = 2.3613746581755626

* uni0468 (U+0468): B&lt;&lt;275.0,565.0&gt;-&lt;284.0,594.0&gt;-&lt;294.0,595.0&gt;&gt;/B&lt;&lt;294.0,595.0&gt;-&lt;278.0,597.0&gt;-&lt;262.0,597.0&gt;&gt; = 12.835609486401424

* uni0468 (U+0468): B&lt;&lt;800.0,598.5&gt;-&lt;803.0,605.0&gt;-&lt;811.0,606.0&gt;&gt;/B&lt;&lt;811.0,606.0&gt;-&lt;806.0,606.0&gt;-&lt;800.0,605.5&gt;&gt; = 7.125016348901757

* uni046C (U+046C): B&lt;&lt;245.0,565.0&gt;-&lt;254.0,594.0&gt;-&lt;264.0,595.0&gt;&gt;/B&lt;&lt;264.0,595.0&gt;-&lt;248.0,597.0&gt;-&lt;232.0,597.0&gt;&gt; = 12.835609486401424

* uni046C (U+046C): B&lt;&lt;78.0,-83.5&gt;-&lt;70.0,-102.0&gt;-&lt;60.0,-102.0&gt;&gt;/B&lt;&lt;60.0,-102.0&gt;-&lt;88.0,-106.0&gt;-&lt;116.0,-108.0&gt;&gt; = 8.13010235415596

* uni0472 (U+0472): B&lt;&lt;247.5,426.5&gt;-&lt;241.0,398.0&gt;-&lt;235.0,376.0&gt;&gt;/B&lt;&lt;235.0,376.0&gt;-&lt;252.0,420.0&gt;-&lt;277.0,451.0&gt;&gt; = 5.86960044301464

* uni1C88 (U+1C88): B&lt;&lt;199.0,218.0&gt;-&lt;196.0,231.0&gt;-&lt;195.0,264.0&gt;&gt;/B&lt;&lt;195.0,264.0&gt;-&lt;194.0,240.0&gt;-&lt;193.0,228.5&gt;&gt; = 4.121648619317139

* uni2713 (U+2713): L&lt;&lt;213.0,42.0&gt;--&lt;213.0,30.0&gt;&gt;/B&lt;&lt;213.0,30.0&gt;-&lt;226.0,94.0&gt;-&lt;247.0,152.5&gt;&gt; = 11.481991354748077

* uniA641 (U+A641): B&lt;&lt;528.0,-509.0&gt;-&lt;489.0,-699.0&gt;-&lt;440.0,-881.0&gt;&gt;/B&lt;&lt;440.0,-881.0&gt;-&lt;466.0,-759.0&gt;-&lt;489.0,-623.5&gt;&gt; = 3.0378920629542385

* uniA643 (U+A643): B&lt;&lt;528.0,-509.0&gt;-&lt;489.0,-699.0&gt;-&lt;440.0,-881.0&gt;&gt;/B&lt;&lt;440.0,-881.0&gt;-&lt;466.0,-759.0&gt;-&lt;489.0,-623.5&gt;&gt; = 3.0378920629542385

* uniA644 (U+A644): L&lt;&lt;427.0,469.0&gt;--&lt;418.0,506.0&gt;&gt;/B&lt;&lt;418.0,506.0&gt;-&lt;418.0,501.0&gt;-&lt;418.0,495.0&gt;&gt; = 13.67130713219584

* uniA648 (U+A648): B&lt;&lt;141.0,421.0&gt;-&lt;142.0,451.0&gt;-&lt;153.0,451.0&gt;&gt;/L&lt;&lt;153.0,451.0&gt;--&lt;56.0,455.0&gt;&gt; = 2.3613746581755626

* uniA650 (U+A650): B&lt;&lt;862.0,-69.0&gt;-&lt;858.0,-95.0&gt;-&lt;851.0,-94.0&gt;&gt;/B&lt;&lt;851.0,-94.0&gt;-&lt;860.0,-96.0&gt;-&lt;865.5,-96.0&gt;&gt; = 4.398705354995426

* uniA652 (U+A652): B&lt;&lt;119.0,-69.0&gt;-&lt;115.0,-95.0&gt;-&lt;108.0,-94.0&gt;&gt;/B&lt;&lt;108.0,-94.0&gt;-&lt;119.0,-96.0&gt;-&lt;135.0,-96.0&gt;&gt; = 2.174744114610005

* uniA657 (U+A657): B&lt;&lt;134.0,23.0&gt;-&lt;133.0,23.0&gt;-&lt;132.0,24.0&gt;&gt;/B&lt;&lt;132.0,24.0&gt;-&lt;137.0,20.0&gt;-&lt;144.5,13.5&gt;&gt; = 6.34019174590985

* uniA658 (U+A658): B&lt;&lt;171.0,38.0&gt;-&lt;167.0,56.0&gt;-&lt;167.0,62.0&gt;&gt;/B&lt;&lt;167.0,62.0&gt;-&lt;165.0,42.0&gt;-&lt;153.5,17.5&gt;&gt; = 5.710593137499633

* uniA658 (U+A658): B&lt;&lt;499.0,576.0&gt;-&lt;499.0,597.0&gt;-&lt;513.0,599.0&gt;&gt;/B&lt;&lt;513.0,599.0&gt;-&lt;497.0,598.0&gt;-&lt;478.0,598.0&gt;&gt; = 4.553767979158505

* uniA658.salt (U+E500): B&lt;&lt;171.0,38.0&gt;-&lt;167.0,56.0&gt;-&lt;167.0,62.0&gt;&gt;/B&lt;&lt;167.0,62.0&gt;-&lt;165.0,42.0&gt;-&lt;153.5,17.5&gt;&gt; = 5.710593137499633

* uniA658.salt (U+E500): B&lt;&lt;499.0,576.0&gt;-&lt;499.0,597.0&gt;-&lt;513.0,599.0&gt;&gt;/B&lt;&lt;513.0,599.0&gt;-&lt;497.0,598.0&gt;-&lt;478.0,598.0&gt;&gt; = 4.553767979158505

* uniA65C (U+A65C): B&lt;&lt;255.0,565.0&gt;-&lt;264.0,594.0&gt;-&lt;274.0,595.0&gt;&gt;/B&lt;&lt;274.0,595.0&gt;-&lt;257.0,596.0&gt;-&lt;241.0,596.5&gt;&gt; = 9.077053800929454

* uniA65C (U+A65C): B&lt;&lt;465.0,38.0&gt;-&lt;461.0,56.0&gt;-&lt;461.0,62.0&gt;&gt;/B&lt;&lt;461.0,62.0&gt;-&lt;459.0,42.0&gt;-&lt;447.5,17.5&gt;&gt; = 5.710593137499633

* uniA65C (U+A65C): B&lt;&lt;793.0,576.0&gt;-&lt;793.0,597.0&gt;-&lt;807.0,599.0&gt;&gt;/B&lt;&lt;807.0,599.0&gt;-&lt;791.0,598.0&gt;-&lt;772.0,598.0&gt;&gt; = 4.553767979158505
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u1CF85 (U+1CF85): L&lt;&lt;100.0,-170.0&gt;--&lt;101.0,93.0&gt;&gt;

* u1CF85 (U+1CF85): L&lt;&lt;189.0,93.0&gt;--&lt;188.0,-170.0&gt;&gt;

* uF014E (U+F014E): L&lt;&lt;20.0,-67.0&gt;--&lt;216.0,-66.0&gt;&gt;

* uni0471 (U+0471): L&lt;&lt;177.0,-280.0&gt;--&lt;178.0,-92.0&gt;&gt;

* uni0471 (U+0471): L&lt;&lt;178.0,-92.0&gt;--&lt;177.0,119.0&gt;&gt;

* uni047E (U+047E): L&lt;&lt;757.0,-121.0&gt;--&lt;641.0,-122.0&gt;&gt;

* uniA659 (U+A659): L&lt;&lt;143.0,479.0&gt;--&lt;304.0,478.0&gt;&gt;

* uniA659 (U+A659): L&lt;&lt;472.0,2.0&gt;--&lt;191.0,0.0&gt;&gt;

* uniA659.salt (U+E501): L&lt;&lt;148.0,473.0&gt;--&lt;313.0,472.0&gt;&gt;

* uniA659.salt (U+E501): L&lt;&lt;488.0,2.0&gt;--&lt;197.0,0.0&gt;&gt;

* uniA65D (U+A65D): L&lt;&lt;333.0,479.0&gt;--&lt;494.0,478.0&gt;&gt;

* uniA65D (U+A65D): L&lt;&lt;662.0,2.0&gt;--&lt;381.0,0.0&gt;&gt;

* uniEE8D (U+EE8D): L&lt;&lt;100.0,-170.0&gt;--&lt;101.0,93.0&gt;&gt;

* uniEE8D (U+EE8D): L&lt;&lt;189.0,93.0&gt;--&lt;188.0,-170.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.542x (1542)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 8 | 13 | 109 | 6 | 100 | 0 | 
| 0% | 0% | 3% | 6% | 46% | 3% | 42% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
