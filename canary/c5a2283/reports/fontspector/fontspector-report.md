## FontSpector report

fontspector version: 1.9.0



## Checks with FATAL results

These must be addressed first.


<details><summary>[1] fonts/ttf/GalleDEVCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>💥 <b>ERROR</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- 💥 **ERROR** Error: Error reading font file: the GPOS table is missing 
  
  

</div>
</details>


</div>
</details>







## All other checks




<details><summary>[5] fonts/ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent (family/win_ascent_and_descent)</summary>
    <div>








- 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 333, but got 184 instead. The lowest point is in glyph 'nyaa._csinh'. [code: descent]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts (googlefonts/font_copyright)</summary>
    <div>








- 🔥 **FAIL** GalleDEVCANARY-Regular.ttf: Name Table entry: Copyright notices should match a pattern similar to:

"Copyright 2020 The Familyname Project Authors (git url)"

But instead we have got:

"copyright (c) 2015–2018 mooniak (http://mooniak.com)  copyright (c) 2016–2018 janaka cb attanayake (janakacb@gmail.com) " [code: bad-notice-format]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** fonts/ttf/GalleDEVCANARY-Regular.ttf missing required codepoints:

* 0x0024: DOLLAR SIGN
* 0x0025: PERCENT SIGN
* 0x0026: AMPERSAND
* 0x0040: COMMERCIAL AT
* 0x0041: LATIN CAPITAL LETTER A
* 0x0042: LATIN CAPITAL LETTER B
* 0x0043: LATIN CAPITAL LETTER C
* 0x0044: LATIN CAPITAL LETTER D
* 0x0045: LATIN CAPITAL LETTER E
* 0x0046: LATIN CAPITAL LETTER F
* 0x0047: LATIN CAPITAL LETTER G
* 0x0048: LATIN CAPITAL LETTER H
* 0x0049: LATIN CAPITAL LETTER I
* 0x004A: LATIN CAPITAL LETTER J
* 0x004B: LATIN CAPITAL LETTER K
* 0x004C: LATIN CAPITAL LETTER L
* 0x004D: LATIN CAPITAL LETTER M
* 0x004E: LATIN CAPITAL LETTER N
* 0x004F: LATIN CAPITAL LETTER O
* 0x0050: LATIN CAPITAL LETTER P
* 0x0051: LATIN CAPITAL LETTER Q
* 0x0052: LATIN CAPITAL LETTER R
* 0x0053: LATIN CAPITAL LETTER S
* 0x0054: LATIN CAPITAL LETTER T
* 0x0055: LATIN CAPITAL LETTER U
* 0x0056: LATIN CAPITAL LETTER V
* 0x0057: LATIN CAPITAL LETTER W
* 0x0058: LATIN CAPITAL LETTER X
* 0x0059: LATIN CAPITAL LETTER Y
* 0x005A: LATIN CAPITAL LETTER Z
* 0x0060: GRAVE ACCENT
* 0x0061: LATIN SMALL LETTER A
* 0x0062: LATIN SMALL LETTER B
* 0x0063: LATIN SMALL LETTER C
* 0x0064: LATIN SMALL LETTER D
* 0x0065: LATIN SMALL LETTER E
* 0x0066: LATIN SMALL LETTER F
* 0x0067: LATIN SMALL LETTER G
* 0x0068: LATIN SMALL LETTER H
* 0x0069: LATIN SMALL LETTER I
* 0x006A: LATIN SMALL LETTER J
* 0x006B: LATIN SMALL LETTER K
* 0x006C: LATIN SMALL LETTER L
* 0x006D: LATIN SMALL LETTER M
* 0x006E: LATIN SMALL LETTER N
* 0x006F: LATIN SMALL LETTER O
* 0x0070: LATIN SMALL LETTER P
* 0x0071: LATIN SMALL LETTER Q
* 0x0072: LATIN SMALL LETTER R
* 0x0073: LATIN SMALL LETTER S
* 0x0074: LATIN SMALL LETTER T
* 0x0075: LATIN SMALL LETTER U
* 0x0076: LATIN SMALL LETTER V
* 0x0077: LATIN SMALL LETTER W
* 0x0078: LATIN SMALL LETTER X
* 0x0079: LATIN SMALL LETTER Y
* 0x007A: LATIN SMALL LETTER Z
* 0x00A1: INVERTED EXCLAMATION MARK
* 0x00A2: CENT SIGN
* 0x00A3: POUND SIGN
* 0x00A5: YEN SIGN
* 0x00A7: SECTION SIGN
* 0x00A8: DIAERESIS
* 0x00A9: COPYRIGHT SIGN
* 0x00AA: FEMININE ORDINAL INDICATOR
* 0x00AB: LEFT-POINTING DOUBLE ANGLE QUOTATION MARK
* 0x00AE: REGISTERED SIGN
* 0x00AF: MACRON
* 0x00B0: DEGREE SIGN
* 0x00B4: ACUTE ACCENT
* 0x00B6: PILCROW SIGN
* 0x00B7: MIDDLE DOT
* 0x00B8: CEDILLA
* 0x00BA: MASCULINE ORDINAL INDICATOR
* 0x00BB: RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK
* 0x00BF: INVERTED QUESTION MARK
* 0x00C0: LATIN CAPITAL LETTER A WITH GRAVE
* 0x00C1: LATIN CAPITAL LETTER A WITH ACUTE
* 0x00C2: LATIN CAPITAL LETTER A WITH CIRCUMFLEX
* 0x00C3: LATIN CAPITAL LETTER A WITH TILDE
* 0x00C4: LATIN CAPITAL LETTER A WITH DIAERESIS
* 0x00C5: LATIN CAPITAL LETTER A WITH RING ABOVE
* 0x00C6: LATIN CAPITAL LETTER AE
* 0x00C7: LATIN CAPITAL LETTER C WITH CEDILLA
* 0x00C8: LATIN CAPITAL LETTER E WITH GRAVE
* 0x00C9: LATIN CAPITAL LETTER E WITH ACUTE
* 0x00CA: LATIN CAPITAL LETTER E WITH CIRCUMFLEX
* 0x00CB: LATIN CAPITAL LETTER E WITH DIAERESIS
* 0x00CC: LATIN CAPITAL LETTER I WITH GRAVE
* 0x00CD: LATIN CAPITAL LETTER I WITH ACUTE
* 0x00CE: LATIN CAPITAL LETTER I WITH CIRCUMFLEX
* 0x00CF: LATIN CAPITAL LETTER I WITH DIAERESIS
* 0x00D0: LATIN CAPITAL LETTER ETH
* 0x00D1: LATIN CAPITAL LETTER N WITH TILDE
* 0x00D2: LATIN CAPITAL LETTER O WITH GRAVE
* 0x00D3: LATIN CAPITAL LETTER O WITH ACUTE
* 0x00D4: LATIN CAPITAL LETTER O WITH CIRCUMFLEX
* 0x00D5: LATIN CAPITAL LETTER O WITH TILDE
* 0x00D6: LATIN CAPITAL LETTER O WITH DIAERESIS
* 0x00D7: MULTIPLICATION SIGN
* 0x00D8: LATIN CAPITAL LETTER O WITH STROKE
* 0x00D9: LATIN CAPITAL LETTER U WITH GRAVE
* 0x00DA: LATIN CAPITAL LETTER U WITH ACUTE
* 0x00DB: LATIN CAPITAL LETTER U WITH CIRCUMFLEX
* 0x00DC: LATIN CAPITAL LETTER U WITH DIAERESIS
* 0x00DD: LATIN CAPITAL LETTER Y WITH ACUTE
* 0x00DE: LATIN CAPITAL LETTER THORN
* 0x00DF: LATIN SMALL LETTER SHARP S
* 0x00E0: LATIN SMALL LETTER A WITH GRAVE
* 0x00E1: LATIN SMALL LETTER A WITH ACUTE
* 0x00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX
* 0x00E3: LATIN SMALL LETTER A WITH TILDE
* 0x00E4: LATIN SMALL LETTER A WITH DIAERESIS
* 0x00E5: LATIN SMALL LETTER A WITH RING ABOVE
* 0x00E6: LATIN SMALL LETTER AE
* 0x00E7: LATIN SMALL LETTER C WITH CEDILLA
* 0x00E8: LATIN SMALL LETTER E WITH GRAVE
* 0x00E9: LATIN SMALL LETTER E WITH ACUTE
* 0x00EA: LATIN SMALL LETTER E WITH CIRCUMFLEX
* 0x00EB: LATIN SMALL LETTER E WITH DIAERESIS
* 0x00EC: LATIN SMALL LETTER I WITH GRAVE
* 0x00ED: LATIN SMALL LETTER I WITH ACUTE
* 0x00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX
* 0x00EF: LATIN SMALL LETTER I WITH DIAERESIS
* 0x00F0: LATIN SMALL LETTER ETH
* 0x00F1: LATIN SMALL LETTER N WITH TILDE
* 0x00F2: LATIN SMALL LETTER O WITH GRAVE
* 0x00F3: LATIN SMALL LETTER O WITH ACUTE
* 0x00F4: LATIN SMALL LETTER O WITH CIRCUMFLEX
* 0x00F5: LATIN SMALL LETTER O WITH TILDE
* 0x00F6: LATIN SMALL LETTER O WITH DIAERESIS
* 0x00F7: DIVISION SIGN
* 0x00F8: LATIN SMALL LETTER O WITH STROKE
* 0x00F9: LATIN SMALL LETTER U WITH GRAVE
* 0x00FA: LATIN SMALL LETTER U WITH ACUTE
* 0x00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX
* 0x00FC: LATIN SMALL LETTER U WITH DIAERESIS
* 0x00FD: LATIN SMALL LETTER Y WITH ACUTE
* 0x00FE: LATIN SMALL LETTER THORN
* 0x00FF: LATIN SMALL LETTER Y WITH DIAERESIS
* 0x0100: LATIN CAPITAL LETTER A WITH MACRON
* 0x0101: LATIN SMALL LETTER A WITH MACRON
* 0x0102: LATIN CAPITAL LETTER A WITH BREVE
* 0x0103: LATIN SMALL LETTER A WITH BREVE
* 0x0104: LATIN CAPITAL LETTER A WITH OGONEK
* 0x0105: LATIN SMALL LETTER A WITH OGONEK
* 0x0106: LATIN CAPITAL LETTER C WITH ACUTE
* 0x0107: LATIN SMALL LETTER C WITH ACUTE
* 0x010A: LATIN CAPITAL LETTER C WITH DOT ABOVE
* 0x010B: LATIN SMALL LETTER C WITH DOT ABOVE
* 0x010C: LATIN CAPITAL LETTER C WITH CARON
* 0x010D: LATIN SMALL LETTER C WITH CARON
* 0x010E: LATIN CAPITAL LETTER D WITH CARON
* 0x010F: LATIN SMALL LETTER D WITH CARON
* 0x0110: LATIN CAPITAL LETTER D WITH STROKE
* 0x0111: LATIN SMALL LETTER D WITH STROKE
* 0x0112: LATIN CAPITAL LETTER E WITH MACRON
* 0x0113: LATIN SMALL LETTER E WITH MACRON
* 0x0116: LATIN CAPITAL LETTER E WITH DOT ABOVE
* 0x0117: LATIN SMALL LETTER E WITH DOT ABOVE
* 0x0118: LATIN CAPITAL LETTER E WITH OGONEK
* 0x0119: LATIN SMALL LETTER E WITH OGONEK
* 0x011A: LATIN CAPITAL LETTER E WITH CARON
* 0x011B: LATIN SMALL LETTER E WITH CARON
* 0x011E: LATIN CAPITAL LETTER G WITH BREVE
* 0x011F: LATIN SMALL LETTER G WITH BREVE
* 0x0120: LATIN CAPITAL LETTER G WITH DOT ABOVE
* 0x0121: LATIN SMALL LETTER G WITH DOT ABOVE
* 0x0122: LATIN CAPITAL LETTER G WITH CEDILLA
* 0x0123: LATIN SMALL LETTER G WITH CEDILLA
* 0x0126: LATIN CAPITAL LETTER H WITH STROKE
* 0x0127: LATIN SMALL LETTER H WITH STROKE
* 0x012A: LATIN CAPITAL LETTER I WITH MACRON
* 0x012B: LATIN SMALL LETTER I WITH MACRON
* 0x012E: LATIN CAPITAL LETTER I WITH OGONEK
* 0x012F: LATIN SMALL LETTER I WITH OGONEK
* 0x0130: LATIN CAPITAL LETTER I WITH DOT ABOVE
* 0x0131: LATIN SMALL LETTER DOTLESS I
* 0x0136: LATIN CAPITAL LETTER K WITH CEDILLA
* 0x0137: LATIN SMALL LETTER K WITH CEDILLA
* 0x0139: LATIN CAPITAL LETTER L WITH ACUTE
* 0x013A: LATIN SMALL LETTER L WITH ACUTE
* 0x013B: LATIN CAPITAL LETTER L WITH CEDILLA
* 0x013C: LATIN SMALL LETTER L WITH CEDILLA
* 0x013D: LATIN CAPITAL LETTER L WITH CARON
* 0x013E: LATIN SMALL LETTER L WITH CARON
* 0x0141: LATIN CAPITAL LETTER L WITH STROKE
* 0x0142: LATIN SMALL LETTER L WITH STROKE
* 0x0143: LATIN CAPITAL LETTER N WITH ACUTE
* 0x0144: LATIN SMALL LETTER N WITH ACUTE
* 0x0145: LATIN CAPITAL LETTER N WITH CEDILLA
* 0x0146: LATIN SMALL LETTER N WITH CEDILLA
* 0x0147: LATIN CAPITAL LETTER N WITH CARON
* 0x0148: LATIN SMALL LETTER N WITH CARON
* 0x0150: LATIN CAPITAL LETTER O WITH DOUBLE ACUTE
* 0x0151: LATIN SMALL LETTER O WITH DOUBLE ACUTE
* 0x0152: LATIN CAPITAL LIGATURE OE
* 0x0153: LATIN SMALL LIGATURE OE
* 0x0154: LATIN CAPITAL LETTER R WITH ACUTE
* 0x0155: LATIN SMALL LETTER R WITH ACUTE
* 0x0158: LATIN CAPITAL LETTER R WITH CARON
* 0x0159: LATIN SMALL LETTER R WITH CARON
* 0x015A: LATIN CAPITAL LETTER S WITH ACUTE
* 0x015B: LATIN SMALL LETTER S WITH ACUTE
* 0x015E: LATIN CAPITAL LETTER S WITH CEDILLA
* 0x015F: LATIN SMALL LETTER S WITH CEDILLA
* 0x0160: LATIN CAPITAL LETTER S WITH CARON
* 0x0161: LATIN SMALL LETTER S WITH CARON
* 0x0164: LATIN CAPITAL LETTER T WITH CARON
* 0x0165: LATIN SMALL LETTER T WITH CARON
* 0x016A: LATIN CAPITAL LETTER U WITH MACRON
* 0x016B: LATIN SMALL LETTER U WITH MACRON
* 0x016E: LATIN CAPITAL LETTER U WITH RING ABOVE
* 0x016F: LATIN SMALL LETTER U WITH RING ABOVE
* 0x0170: LATIN CAPITAL LETTER U WITH DOUBLE ACUTE
* 0x0171: LATIN SMALL LETTER U WITH DOUBLE ACUTE
* 0x0172: LATIN CAPITAL LETTER U WITH OGONEK
* 0x0173: LATIN SMALL LETTER U WITH OGONEK
* 0x0174: LATIN CAPITAL LETTER W WITH CIRCUMFLEX
* 0x0175: LATIN SMALL LETTER W WITH CIRCUMFLEX
* 0x0176: LATIN CAPITAL LETTER Y WITH CIRCUMFLEX
* 0x0177: LATIN SMALL LETTER Y WITH CIRCUMFLEX
* 0x0178: LATIN CAPITAL LETTER Y WITH DIAERESIS
* 0x0179: LATIN CAPITAL LETTER Z WITH ACUTE
* 0x017A: LATIN SMALL LETTER Z WITH ACUTE
* 0x017B: LATIN CAPITAL LETTER Z WITH DOT ABOVE
* 0x017C: LATIN SMALL LETTER Z WITH DOT ABOVE
* 0x017D: LATIN CAPITAL LETTER Z WITH CARON
* 0x017E: LATIN SMALL LETTER Z WITH CARON
* 0x0218: LATIN CAPITAL LETTER S WITH COMMA BELOW
* 0x0219: LATIN SMALL LETTER S WITH COMMA BELOW
* 0x021A: LATIN CAPITAL LETTER T WITH COMMA BELOW
* 0x021B: LATIN SMALL LETTER T WITH COMMA BELOW
* 0x0237: LATIN SMALL LETTER DOTLESS J
* 0x02C6: MODIFIER LETTER CIRCUMFLEX ACCENT
* 0x02C7: CARON
* 0x02D8: BREVE
* 0x02D9: DOT ABOVE
* 0x02DA: RING ABOVE
* 0x02DB: OGONEK
* 0x02DC: SMALL TILDE
* 0x02DD: DOUBLE ACUTE ACCENT
* 0x0300: COMBINING GRAVE ACCENT
* 0x0301: COMBINING ACUTE ACCENT
* 0x0302: COMBINING CIRCUMFLEX ACCENT
* 0x0303: COMBINING TILDE
* 0x0304: COMBINING MACRON
* 0x0306: COMBINING BREVE
* 0x0307: COMBINING DOT ABOVE
* 0x0308: COMBINING DIAERESIS
* 0x030A: COMBINING RING ABOVE
* 0x030B: COMBINING DOUBLE ACUTE ACCENT
* 0x030C: COMBINING CARON
* 0x0326: COMBINING COMMA BELOW
* 0x0327: COMBINING CEDILLA
* 0x0328: COMBINING OGONEK
* 0x1E80: LATIN CAPITAL LETTER W WITH GRAVE
* 0x1E81: LATIN SMALL LETTER W WITH GRAVE
* 0x1E82: LATIN CAPITAL LETTER W WITH ACUTE
* 0x1E83: LATIN SMALL LETTER W WITH ACUTE
* 0x1E84: LATIN CAPITAL LETTER W WITH DIAERESIS
* 0x1E85: LATIN SMALL LETTER W WITH DIAERESIS
* 0x1E9E: LATIN CAPITAL LETTER SHARP S
* 0x1EF2: LATIN CAPITAL LETTER Y WITH GRAVE
* 0x1EF3: LATIN SMALL LETTER Y WITH GRAVE
* 0x2013: EN DASH
* 0x2014: EM DASH
* 0x2018: LEFT SINGLE QUOTATION MARK
* 0x2019: RIGHT SINGLE QUOTATION MARK
* 0x201A: SINGLE LOW-9 QUOTATION MARK
* 0x201C: LEFT DOUBLE QUOTATION MARK
* 0x201D: RIGHT DOUBLE QUOTATION MARK
* 0x201E: DOUBLE LOW-9 QUOTATION MARK
* 0x2022: BULLET
* 0x2039: SINGLE LEFT-POINTING ANGLE QUOTATION MARK
* 0x203A: SINGLE RIGHT-POINTING ANGLE QUOTATION MARK
* 0x20AC: EURO SIGN
* 0x2122: TRADE MARK SIGN
* 0x2212: MINUS SIGN [code: missing-codepoints]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** fonts/ttf/GalleDEVCANARY-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+0021 EXCLAMATION MARK: try adding one of: masaram-gondi, mongolian, thaana, cham, gunjala-gondi, khmer, adlam, syriac, math, latin
* U+0022 QUOTATION MARK: try adding one of: cham, latin, masaram-gondi, wancho, math, khmer, mongolian, adlam
* U+0023 NUMBER SIGN: try adding one of: khmer, symbols, math, latin, adlam
* U+0027 APOSTROPHE: try adding one of: adlam, masaram-gondi, warang-citi, wancho, khmer, latin, cham, gunjala-gondi, math
* U+0028 LEFT PARENTHESIS: try adding one of: masaram-gondi, math, cham, khmer, wancho, adlam, syriac, thaana, gunjala-gondi, mongolian, latin
* U+0029 RIGHT PARENTHESIS: try adding one of: thaana, wancho, math, masaram-gondi, syriac, adlam, cham, khmer, mongolian, latin, gunjala-gondi
* U+002A ASTERISK: try adding one of: symbols, math, adlam, khmer, latin, syriac, gunjala-gondi, masaram-gondi
* U+002B PLUS SIGN: try adding one of: adlam, gunjala-gondi, khmer, latin, math, syriac, masaram-gondi
* U+002C COMMA: try adding one of: math, gunjala-gondi, wancho, masaram-gondi, coptic, nushu, adlam, latin, cham, thaana, khmer
* U+002D HYPHEN-MINUS: try adding one of: khmer, math, kaithi, adlam, coptic, kayah-li, masaram-gondi, mongolian, armenian, syriac, lisu, sora-sompeng, sundanese, wancho, hebrew, cham, nushu, gunjala-gondi, kharoshthi, latin
* U+002E FULL STOP: try adding one of: gunjala-gondi, adlam, khmer, wancho, avestan, nushu, cham, thaana, coptic, syriac, masaram-gondi, math, latin
* U+002F SOLIDUS: try adding one of: math, cham, syriac, adlam, khmer, wancho, masaram-gondi, latin, gunjala-gondi
* U+0030 DIGIT ZERO: try adding one of: khmer, nushu, latin, symbols, math
* U+0031 DIGIT ONE: try adding one of: khmer, symbols, math, latin, nushu
* U+0032 DIGIT TWO: try adding one of: khmer, latin, nushu, symbols, math
* U+0033 DIGIT THREE: try adding one of: khmer, math, latin, symbols, nushu
* U+0034 DIGIT FOUR: try adding one of: khmer, latin, nushu, symbols, math
* U+0035 DIGIT FIVE: try adding one of: symbols, nushu, khmer, latin, math
* U+0036 DIGIT SIX: try adding one of: khmer, symbols, latin, math, nushu
* U+0037 DIGIT SEVEN: try adding one of: math, khmer, nushu, symbols, latin
* U+0038 DIGIT EIGHT: try adding one of: khmer, math, latin, nushu, symbols
* U+0039 DIGIT NINE: try adding one of: latin, khmer, symbols, math, nushu
* U+003A COLON: try adding one of: latin, masaram-gondi, syriac, khmer, cham, gunjala-gondi, adlam, coptic, math, meroitic, thaana
* U+003B SEMICOLON: try adding one of: cham, thaana, adlam, coptic, latin, masaram-gondi, khmer, math
* U+003C LESS-THAN SIGN: try adding one of: masaram-gondi, khmer, math, adlam, gunjala-gondi, latin
* U+003D EQUALS SIGN: try adding one of: latin, math, khmer, gunjala-gondi, adlam, masaram-gondi, syriac
* U+003E GREATER-THAN SIGN: try adding one of: masaram-gondi, adlam, gunjala-gondi, khmer, latin, math
* U+003F QUESTION MARK: try adding one of: masaram-gondi, khmer, cham, latin, balinese, adlam, mongolian, math, gunjala-gondi
* U+005B LEFT SQUARE BRACKET: try adding one of: adlam, khmer, wancho, math, syriac, latin
* U+005C REVERSE SOLIDUS: try adding one of: adlam, khmer, math, syriac, wancho, latin
* U+005D RIGHT SQUARE BRACKET: try adding one of: khmer, latin, syriac, wancho, adlam, math
* U+005E CIRCUMFLEX ACCENT: try adding one of: khmer, math, adlam, latin
* U+005F LOW LINE: try adding one of: adlam, khmer, math, latin
* U+007B LEFT CURLY BRACKET: try adding one of: adlam, math, wancho, latin, khmer
* U+007C VERTICAL LINE: try adding one of: khmer, adlam, math, latin
* U+007D RIGHT CURLY BRACKET: try adding one of: math, khmer, latin, adlam, wancho
* U+007E TILDE: try adding one of: khmer, latin, math
* U+2026 HORIZONTAL ELLIPSIS: try adding one of: masaram-gondi, meroitic, gunjala-gondi, adlam, latin, phags-pa, syriac

Or you can add the above codepoints to one of the subsets supported by the font: sinhala [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>


<details><summary>[28] fonts/ttf/GalleDEVCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. (name/trailing_spaces)</summary>
    <div>








- 🔥 **FAIL** Name table record 3/1/1033/COPYRIGHT_NOTICE has trailing spaces that must be removed:
`Copyright (c) 2015–2018 mooniak (http://mooniak.com)  Copyright (c) 2016–2018 Janaka CB Attanayake (janakacb@gmail.com) ` [code: trailing-space]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Are there duplicate characters in the NAME table? (name/repeating_characters)</summary>
    <div>








- 🔥 **FAIL** Name table record 3/1/1033/COPYRIGHT_NOTICE has repeated characters ` `:
`Copyright (c) 2015–2018 mooniak (http://mooniak.com)  Copyright (c) 2016–2018 Janaka CB Attanayake (janakacb@gmail.com) ` [code: repeated-characters-fail]
  
  

  

  

  

  

  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. (os2_metrics_match_hhea)</summary>
    <div>








- 🔥 **FAIL** OS/2 sTypoAscender (553) and hhea ascent (1016) must be equal. [code: ascender]
  
  


- 🔥 **FAIL** OS/2 sTypoLineGap (463) and hhea lineGap (0) must be equal. [code: lineGap]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** No GF glyphset was found to be supported >80%, so language shaping support couldn't get checked. [code: no-glyphset-supported]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Directory name in GFonts repo structure must
    match NameID 1 of the regular. (googlefonts/repo/dirname_matches_nameid_1)</summary>
    <div>








- 🔥 **FAIL** Family name on the name table ('Galle DEV CANARY') does not match directory name in the repo structure ('ttf'). Expected 'galledevcanary'. [code: mismatch]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? (googlefonts/name/version_format)</summary>
    <div>








- 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000.

The "Version" prefix is a recommendation given by the OpenType spec.

Current version string is: "Version 0.060; [c5a2283]-dev" [code: bad-version-strings]
  
  


- 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000.

The "Version" prefix is a recommendation given by the OpenType spec.

Current version string is: "Version 0.060; [c5a2283]-dev" [code: bad-version-strings]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. (googlefonts/render_own_name)</summary>
    <div>








- 🔥 **FAIL** .notdef glyphs were found when attempting to render Galle DEV CANARY [code: render-own-name]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (googlefonts/use_typo_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) was NOT set. [code: missing-os2-fsselection-bit7]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema (googlefonts/vertical_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.sTypoLineGap is 463; it should be 0 [code: bad-OS/2.sTypoLineGap]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. (opentype/GDEF_non_mark_chars)</summary>
    <div>








- ⚠️ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:

* U+0D82 (uni0D82)
* U+0D83 (uni0D83) [code: non-mark-chars]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. (opentype/GDEF_spacing_marks)</summary>
    <div>








- ⚠️ **WARN** The following glyphs seem to be spacing (because they have width > 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:

* uni0D82
* uni0D83 [code: spacing-mark-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check base characters have non-zero advance width. (base_has_width)</summary>
    <div>








- ⚠️ **WARN** U+200C ZERO WIDTH NON-JOINER has non-zero advance width: 58 [code: non-zero-advance]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni0D93 (U+0D93): found 3, expected one of: [4, 5, 6]
* uni0DA1 (U+0DA1): found 2, expected one of: [3, 4, 5]
* uni0D89 (U+0D89): found 1, expected one of: [2, 3, 4]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking Vertical Metric linegaps. (linegaps)</summary>
    <div>








- ⚠️ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 285 among a set of 4  math glyphs.
The following math glyphs have a different width, though:
width=244: equal, plus [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. (stylisticset_description)</summary>
    <div>








- ⚠️ **WARN** The stylistic set ss01 lacks a description string in the name table [code: missing-description]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* NULL
* notdef
* null
* anusvarayasinh
* chRIsinh
* chRIisinh
* chRasinh
* ddhRIsinh
* ddhRIisinh
* ddhRasinh
* drIsinh
* drIisinh
* drasinh
* fRIsinh
* fRIisinh
* kAasinh
* kunddaliya
* sinMatraAea
* mbsinh
* nAasinh
* nDRIsinh
* nDRIisinh
* ndRasinh
* nddasinh
* ngUsinh
* ngUusinh
* nnAasinh
* nngAasinh
* nyaa._csinh
* phRIsinh
* phRIisinh
* phRasinh
* ssRIsinh
* ssRIisinh
* tAasinh
* thRIsinh
* thRIisinh
* thRasinh
* tthRIsinh
* tthRIisinh
* tthRasinh
* visargayasinh
* gNaasinh
* bU_rephasinh
* bUu_rephasinh
* ba_rephasinh
* sinBhAa.virama
* bhRsinh
* bhU_rephasinh
* bhUu_rephasinh
* bha_rephasinh
* cU_rephasinh
* cUu_rephasinh
* ca_rephasinh
* chRsinh
* chU_rephasinh
* chUu_rephasinh
* cha_rephasinh
* dRasinh.alt
* dU_rephasinh
* dUu_rephasinh
* da_rephasinh
* ddU_rephasinh
* ddUu_rephasinh
* dda_rephasinh
* ddsinh.alt
* ddhRsinh
* ddhU_rephasinh
* ddhUu_rephasinh
* ddha_rephasinh
* dhU_rephasinh
* dhUu_rephasinh
* dha_rephasinh
* sinFAa.virama
* fU_rephasinh
* fUu_rephasinh
* fa_rephasinh
* sinGAa.virama
* gU_rephasinh
* gUu_rephasinh
* ga_rephasinh
* ghU_rephasinh
* ghUu_rephasinh
* gha_rephasinh
* sinHAa.virama
* hU_rephasinh
* hUu_rephasinh
* ha_rephasinh
* jU_rephasinh
* jUu_rephasinh
* ja_rephasinh
* jhU_rephasinh
* jhUu_rephasinh
* jha_rephasinh
* jnya_rephasinh
* sinKAa.virama
* kRsinh
* kU_rephasinh
* kUu_rephasinh
* ka_rephasinh
* khU_rephasinh
* khUu_rephasinh
* kha_rephasinh
* ma_rephasinh
* isignsinh.alt
* isignsinh.alt1
* isignsinh.alt2
* isignsinh.alt4
* iisignsinh.alt
* iisignsinh.alt1
* iisignsinh.alt2
* iisignsinh.alt3
* usignsinh.alt
* usignsinh.alt1
* usignsinh.alt2
* usignsinh.alt3
* usignsinh.alt5
* uusignsinh.alt
* uusignsinh.alt1
* uusignsinh.alt2
* uusignsinh.alt3
* uusignsinh.alt5
* mba_rephasinh
* sinNAa.virama
* na_rephasinh
* nda_rephasinh
* nyja_rephasinh
* nga_rephasinh
* sinNnAa.virama
* nna_rephasinh
* nndda_rephasinh
* sinNngAa.virama
* nnga_rephasinh
* nya_rephasinh
* pU_rephasinh
* pUu_rephasinh
* pa_rephasinh
* phRsinh
* phU_rephasinh
* phUu_rephasinh
* pha_rephasinh
* rasignsinh.long
* rasignsinh.medium
* rasignsinh.short
* sU_rephasinh
* sUu_rephasinh
* sa_rephasinh
* shU_rephasinh
* shUu_rephasinh
* sha_rephasinh
* ssU_rephasinh
* ssUu_rephasinh
* ssa_rephasinh
* sinTAa.virama
* tU_rephasinh
* tUu_rephasinh
* ta_rephasinh
* thRsinh
* thU_rephasinh
* thUu_rephasinh
* tha_rephasinh
* ttU_rephasinh
* ttUu_rephasinh
* tta_rephasinh
* tthRsinh
* tthU_rephasinh
* tthUu_rephasinh
* ttha_rephasinh
* vU_rephasinh
* vUu_rephasinh
* va_rephasinh
* viramasinh.alt
* yU_rephasinh
* yUu_rephasinh
* ya_rephasinh
* yasign_usign_rephasinh
* yasign_uusign_rephasinh
* yasign_rephasinh
* mooniak [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* sinBhAa.virama
* aasign_viramasinh
* sinGAa.virama
* rAaesinh
* sinFAa.virama
* sinHAa.virama
* uni0DDD (U+0DDD) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* u111E7 (U+111E7): from (452.0, -7.0) to (451.0, -7.0) is colinear with segment from (451.0, -7.0) to (400.0, -7.0)
* u111E8 (U+111E8): from (199.0, -114.0) to (199.0, -114.0) is colinear with segment from (199.0, -114.0) to (199.0, -114.0)
* bIisinh: from (293.0, 414.0) to (296.0, 414.0) is colinear with segment from (296.0, 414.0) to (296.0, 414.0)
* bRIisinh: from (293.0, 414.0) to (296.0, 414.0) is colinear with segment from (296.0, 414.0) to (296.0, 414.0)
* gRIsinh: from (371.0, 298.0) to (371.0, 298.0) is colinear with segment from (371.0, 298.0) to (371.0, 298.0)
* kIisinh: from (326.0, 331.0) to (326.0, 331.0) is colinear with segment from (326.0, 331.0) to (328.0, 331.0)
* khUusinh: from (448.0, 100.0) to (448.0, 99.0) is colinear with segment from (448.0, 99.0) to (448.0, -248.0)
* nIsinh: from (340.0, 330.0) to (341.0, 330.0) is colinear with segment from (341.0, 330.0) to (341.0, 330.0)
* rAaesinh: from (210.0, 593.0) to (211.0, 590.0) is colinear with segment from (211.0, 590.0) to (234.0, 536.0)
* sIsinh: from (360.0, 285.0) to (360.0, 287.0) is colinear with segment from (360.0, 287.0) to (360.0, 290.0)
* sIsinh: from (360.0, 287.0) to (360.0, 290.0) is colinear with segment from (360.0, 290.0) to (360.0, 291.0)
* sRIsinh: from (381.0, 285.0) to (381.0, 287.0) is colinear with segment from (381.0, 287.0) to (381.0, 290.0)
* sRIsinh: from (381.0, 287.0) to (381.0, 290.0) is colinear with segment from (381.0, 290.0) to (381.0, 291.0)
* yIsinh: from (364.0, 320.0) to (364.0, 322.0) is colinear with segment from (364.0, 322.0) to (364.0, 324.0)
* yIisinh: from (364.0, 316.0) to (364.0, 318.0) is colinear with segment from (364.0, 318.0) to (364.0, 319.0)
* dhU_rephasinh: from (149.0, 512.0) to (152.0, 512.0) is colinear with segment from (152.0, 512.0) to (153.0, 512.0)
* dhU_rephasinh: from (152.0, 512.0) to (153.0, 512.0) is colinear with segment from (153.0, 512.0) to (158.0, 512.0)
* dhUu_rephasinh: from (149.0, 512.0) to (152.0, 512.0) is colinear with segment from (152.0, 512.0) to (153.0, 512.0)
* dhUu_rephasinh: from (152.0, 512.0) to (153.0, 512.0) is colinear with segment from (153.0, 512.0) to (158.0, 512.0)
* dha_rephasinh: from (149.0, 512.0) to (152.0, 512.0) is colinear with segment from (152.0, 512.0) to (153.0, 512.0)
* dha_rephasinh: from (152.0, 512.0) to (153.0, 512.0) is colinear with segment from (153.0, 512.0) to (158.0, 512.0)
* khU_rephasinh: from (152.0, 512.0) to (155.0, 512.0) is colinear with segment from (155.0, 512.0) to (159.0, 512.0)
* khUu_rephasinh: from (453.0, 100.0) to (453.0, 99.0) is colinear with segment from (453.0, 99.0) to (453.0, -248.0)
* khUu_rephasinh: from (152.0, 512.0) to (155.0, 512.0) is colinear with segment from (155.0, 512.0) to (159.0, 512.0)
* kha_rephasinh: from (152.0, 512.0) to (155.0, 512.0) is colinear with segment from (155.0, 512.0) to (159.0, 512.0)
* nndda_rephasinh: from (236.0, 512.0) to (237.0, 512.0) is colinear with segment from (237.0, 512.0) to (238.0, 512.0)
* nndda_rephasinh: from (237.0, 512.0) to (238.0, 512.0) is colinear with segment from (238.0, 512.0) to (238.0, 512.0)
* nndda_rephasinh: from (238.0, 512.0) to (238.0, 512.0) is colinear with segment from (238.0, 512.0) to (238.0, 512.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0DA9 (U+0DA9): Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* uni0DAA (U+0DAA): Quad(QuadBez { p0: (77.5, 224.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* uni0D9D (U+0D9D): Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* uni0D8A (U+0D8A): Quad(QuadBez { p0: (144.5, 377.5), p1: (113.0, 338.0), p2: (96.0, 312.0) })/Quad(QuadBez { p0: (96.0, 312.0), p1: (110.0, 326.0), p2: (134.5, 337.5) }) = 11.821488340607257 degrees
* uni0DB3 (U+0DB3): Quad(QuadBez { p0: (285.0, 298.5), p1: (297.0, 292.0), p2: (300.0, 289.0) })/Quad(QuadBez { p0: (300.0, 289.0), p1: (295.0, 297.0), p2: (295.0, 307.0) }) = 12.994616791916483 degrees
* uni0DC2 (U+0DC2): Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* bhUsinh: Quad(QuadBez { p0: (83.5, 235.0), p1: (97.0, 246.0), p2: (106.0, 246.0) })/Quad(QuadBez { p0: (106.0, 246.0), p1: (100.0, 247.0), p2: (94.5, 247.0) }) = 9.462322208025574 degrees
* bhUusinh: Quad(QuadBez { p0: (83.5, 235.0), p1: (97.0, 246.0), p2: (106.0, 246.0) })/Quad(QuadBez { p0: (106.0, 246.0), p1: (100.0, 247.0), p2: (94.5, 247.0) }) = 9.462322208025574 degrees
* dRIsinh: Quad(QuadBez { p0: (211.5, 298.5), p1: (224.0, 292.0), p2: (227.0, 289.0) })/Quad(QuadBez { p0: (227.0, 289.0), p1: (222.0, 297.0), p2: (222.0, 305.0) }) = 12.994616791916483 degrees
* dRIisinh: Quad(QuadBez { p0: (211.5, 298.5), p1: (224.0, 292.0), p2: (227.0, 289.0) })/Quad(QuadBez { p0: (227.0, 289.0), p1: (222.0, 297.0), p2: (222.0, 305.0) }) = 12.994616791916483 degrees
* dRasinh: Quad(QuadBez { p0: (211.5, 298.5), p1: (224.0, 292.0), p2: (227.0, 289.0) })/Quad(QuadBez { p0: (227.0, 289.0), p1: (222.0, 297.0), p2: (222.0, 305.0) }) = 12.994616791916483 degrees
* ddIsinh: Quad(QuadBez { p0: (71.5, 233.5), p1: (92.0, 246.0), p2: (106.0, 246.0) })/Quad(QuadBez { p0: (106.0, 246.0), p1: (100.0, 247.0), p2: (95.0, 247.0) }) = 9.462322208025613 degrees
* ddIisinh: Quad(QuadBez { p0: (359.0, 415.0), p1: (355.0, 405.0), p2: (346.0, 396.0) })/Quad(QuadBez { p0: (346.0, 396.0), p1: (383.0, 419.0), p2: (383.0, 465.0) }) = 13.134022306396298 degrees
* ddIisinh: Quad(QuadBez { p0: (71.5, 233.5), p1: (92.0, 246.0), p2: (106.0, 246.0) })/Quad(QuadBez { p0: (106.0, 246.0), p1: (100.0, 247.0), p2: (95.0, 247.0) }) = 9.462322208025613 degrees
* ddRIsinh: Quad(QuadBez { p0: (71.5, 233.5), p1: (92.0, 246.0), p2: (106.0, 246.0) })/Quad(QuadBez { p0: (106.0, 246.0), p1: (100.0, 247.0), p2: (95.0, 247.0) }) = 9.462322208025613 degrees
* ddRIisinh: Quad(QuadBez { p0: (359.0, 415.0), p1: (355.0, 405.0), p2: (346.0, 396.0) })/Quad(QuadBez { p0: (346.0, 396.0), p1: (383.0, 419.0), p2: (383.0, 465.0) }) = 13.134022306396298 degrees
* ddRIisinh: Quad(QuadBez { p0: (71.5, 233.5), p1: (92.0, 246.0), p2: (106.0, 246.0) })/Quad(QuadBez { p0: (106.0, 246.0), p1: (100.0, 247.0), p2: (95.0, 247.0) }) = 9.462322208025613 degrees
* ddRasinh: Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* ddUsinh: Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* ddUusinh: Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* ddhIsinh: Quad(QuadBez { p0: (77.5, 225.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhIisinh: Quad(QuadBez { p0: (77.5, 225.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhRIsinh: Quad(QuadBez { p0: (77.5, 224.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhRIisinh: Quad(QuadBez { p0: (77.5, 224.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhRasinh: Quad(QuadBez { p0: (77.5, 224.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhUsinh: Quad(QuadBez { p0: (77.5, 224.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhUusinh: Quad(QuadBez { p0: (77.5, 224.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* gUusinh: Quad(QuadBez { p0: (356.0, 1.0), p1: (338.0, -2.0), p2: (323.0, 0.0) })/Quad(QuadBez { p0: (323.0, 0.0), p1: (334.0, -4.0), p2: (346.0, -7.5) }) = 12.388463153308553 degrees
* ghIsinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghIisinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghRIsinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghRIisinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghRasinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghUsinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghUusinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ndIsinh: Quad(QuadBez { p0: (285.0, 298.5), p1: (297.0, 292.0), p2: (300.0, 289.0) })/Quad(QuadBez { p0: (300.0, 289.0), p1: (295.0, 297.0), p2: (295.0, 307.0) }) = 12.994616791916483 degrees
* ndIisinh: Quad(QuadBez { p0: (285.0, 298.5), p1: (297.0, 292.0), p2: (300.0, 289.0) })/Quad(QuadBez { p0: (300.0, 289.0), p1: (295.0, 297.0), p2: (295.0, 307.0) }) = 12.994616791916483 degrees
* ndUsinh: Quad(QuadBez { p0: (285.0, 298.5), p1: (297.0, 292.0), p2: (300.0, 289.0) })/Quad(QuadBez { p0: (300.0, 289.0), p1: (292.0, 301.0), p2: (298.0, 317.0) }) = 11.309932474020162 degrees
* ndUusinh: Quad(QuadBez { p0: (285.0, 298.5), p1: (297.0, 292.0), p2: (300.0, 289.0) })/Quad(QuadBez { p0: (300.0, 289.0), p1: (292.0, 301.0), p2: (298.0, 317.0) }) = 11.309932474020162 degrees
* nnAasinh: Quad(QuadBez { p0: (615.5, 318.5), p1: (632.0, 302.0), p2: (635.0, 279.0) })/Quad(QuadBez { p0: (635.0, 279.0), p1: (637.0, 302.0), p2: (654.5, 317.5) }) = 12.401148699282784 degrees
* nnIsinh: Quad(QuadBez { p0: (393.0, 246.0), p1: (393.0, 233.0), p2: (396.0, 213.0) })/Line(Line { p0: (396.0, 213.0), p1: (396.0, 214.0) }) = 8.530765609948139 degrees
* nnIsinh: Line(Line { p0: (396.0, 213.0), p1: (396.0, 214.0) })/Quad(QuadBez { p0: (396.0, 214.0), p1: (398.0, 205.0), p2: (399.0, 195.5) }) = 12.528807709151492 degrees
* nnIisinh: Quad(QuadBez { p0: (393.0, 246.0), p1: (393.0, 233.0), p2: (396.0, 213.0) })/Line(Line { p0: (396.0, 213.0), p1: (396.0, 214.0) }) = 8.530765609948139 degrees
* nnIisinh: Line(Line { p0: (396.0, 213.0), p1: (396.0, 214.0) })/Quad(QuadBez { p0: (396.0, 214.0), p1: (398.0, 205.0), p2: (399.0, 195.5) }) = 12.528807709151492 degrees
* nnddIisinh: Quad(QuadBez { p0: (453.0, 415.0), p1: (449.0, 405.0), p2: (440.0, 396.0) })/Quad(QuadBez { p0: (440.0, 396.0), p1: (477.0, 419.0), p2: (477.0, 465.0) }) = 13.134022306396298 degrees
* nngUusinh: Quad(QuadBez { p0: (406.5, -0.5), p1: (399.0, 0.0), p2: (393.0, 1.0) })/Quad(QuadBez { p0: (393.0, 1.0), p1: (404.0, -3.0), p2: (416.5, -6.5) }) = 10.52078431387435 degrees
* nyaa._csinh: Quad(QuadBez { p0: (559.5, 451.5), p1: (490.0, 423.0), p2: (421.0, 361.0) })/Quad(QuadBez { p0: (421.0, 361.0), p1: (466.0, 386.0), p2: (512.0, 386.0) }) = 12.886698326827016 degrees
* rAaesinh: Quad(QuadBez { p0: (189.5, 597.0), p1: (190.0, 597.0), p2: (188.0, 596.0) })/Quad(QuadBez { p0: (188.0, 596.0), p1: (197.0, 602.0), p2: (204.0, 599.0) }) = 7.125016348901859 degrees
* rIsinh: Quad(QuadBez { p0: (132.0, 357.5), p1: (101.0, 330.0), p2: (87.0, 314.0) })/Quad(QuadBez { p0: (87.0, 314.0), p1: (108.0, 333.0), p2: (136.0, 345.5) }) = 6.676480060402135 degrees
* rIisinh: Quad(QuadBez { p0: (135.0, 357.5), p1: (104.0, 330.0), p2: (90.0, 314.0) })/Quad(QuadBez { p0: (90.0, 314.0), p1: (111.0, 333.0), p2: (139.0, 345.5) }) = 6.676480060402135 degrees
* ssIsinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* ssIisinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* ssRIsinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* ssRIisinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* ssRasinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* ssUsinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* ssUusinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* bhU_rephasinh: Quad(QuadBez { p0: (83.5, 235.0), p1: (97.0, 246.0), p2: (106.0, 246.0) })/Quad(QuadBez { p0: (106.0, 246.0), p1: (100.0, 247.0), p2: (94.5, 247.0) }) = 9.462322208025574 degrees
* bhUu_rephasinh: Quad(QuadBez { p0: (83.5, 235.0), p1: (97.0, 246.0), p2: (106.0, 246.0) })/Quad(QuadBez { p0: (106.0, 246.0), p1: (100.0, 247.0), p2: (94.5, 247.0) }) = 9.462322208025574 degrees
* chsinh: Quad(QuadBez { p0: (334.0, 293.0), p1: (334.0, 276.0), p2: (308.0, 267.0) })/Quad(QuadBez { p0: (308.0, 267.0), p1: (318.0, 269.0), p2: (333.0, 266.5) }) = 7.7835595264653525 degrees
* chRsinh: Quad(QuadBez { p0: (334.0, 293.0), p1: (334.0, 276.0), p2: (308.0, 267.0) })/Quad(QuadBez { p0: (308.0, 267.0), p1: (318.0, 269.0), p2: (333.0, 266.5) }) = 7.7835595264653525 degrees
* chU_rephasinh: Quad(QuadBez { p0: (362.5, 221.0), p1: (349.0, 246.0), p2: (326.0, 254.0) })/Quad(QuadBez { p0: (326.0, 254.0), p1: (337.0, 247.0), p2: (341.0, 236.0) }) = 13.2921842650378 degrees
* chU_rephasinh: Quad(QuadBez { p0: (326.5, 295.5), p1: (319.0, 286.0), p2: (302.0, 279.0) })/Quad(QuadBez { p0: (302.0, 279.0), p1: (313.0, 281.0), p2: (330.0, 279.0) }) = 12.075288583193561 degrees
* chUu_rephasinh: Quad(QuadBez { p0: (362.5, 221.0), p1: (349.0, 246.0), p2: (326.0, 254.0) })/Quad(QuadBez { p0: (326.0, 254.0), p1: (337.0, 247.0), p2: (341.0, 236.0) }) = 13.2921842650378 degrees
* chUu_rephasinh: Quad(QuadBez { p0: (326.5, 295.5), p1: (319.0, 286.0), p2: (302.0, 279.0) })/Quad(QuadBez { p0: (302.0, 279.0), p1: (313.0, 281.0), p2: (330.0, 279.0) }) = 12.075288583193561 degrees
* cha_rephasinh: Quad(QuadBez { p0: (362.5, 221.0), p1: (349.0, 246.0), p2: (326.0, 254.0) })/Quad(QuadBez { p0: (326.0, 254.0), p1: (337.0, 247.0), p2: (341.0, 236.0) }) = 13.2921842650378 degrees
* cha_rephasinh: Quad(QuadBez { p0: (326.5, 295.5), p1: (319.0, 286.0), p2: (302.0, 279.0) })/Quad(QuadBez { p0: (302.0, 279.0), p1: (313.0, 281.0), p2: (330.0, 279.0) }) = 12.075288583193561 degrees
* dRsinh: Quad(QuadBez { p0: (211.5, 298.5), p1: (224.0, 292.0), p2: (227.0, 289.0) })/Quad(QuadBez { p0: (227.0, 289.0), p1: (222.0, 297.0), p2: (222.0, 305.0) }) = 12.994616791916483 degrees
* ddsinh: Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* ddRsinh: Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* ddU_rephasinh: Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* ddUu_rephasinh: Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* dda_rephasinh: Quad(QuadBez { p0: (71.5, 230.5), p1: (92.0, 243.0), p2: (106.0, 243.0) })/Quad(QuadBez { p0: (106.0, 243.0), p1: (100.0, 244.0), p2: (95.0, 244.0) }) = 9.462322208025613 degrees
* ddhsinh: Quad(QuadBez { p0: (77.5, 224.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhRsinh: Quad(QuadBez { p0: (77.5, 224.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhU_rephasinh: Quad(QuadBez { p0: (77.5, 225.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddhUu_rephasinh: Quad(QuadBez { p0: (77.5, 225.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* ddha_rephasinh: Quad(QuadBez { p0: (77.5, 225.0), p1: (99.0, 237.0), p2: (114.0, 237.0) })/Quad(QuadBez { p0: (114.0, 237.0), p1: (107.0, 238.0), p2: (101.0, 238.0) }) = 8.130102354156005 degrees
* gUu_rephasinh: Quad(QuadBez { p0: (356.0, 1.0), p1: (338.0, -2.0), p2: (323.0, 0.0) })/Quad(QuadBez { p0: (323.0, 0.0), p1: (334.0, -4.0), p2: (346.0, -7.5) }) = 12.388463153308553 degrees
* ghsinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghRsinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghU_rephasinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* ghUu_rephasinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* gha_rephasinh: Quad(QuadBez { p0: (71.5, 236.0), p1: (92.0, 250.0), p2: (106.0, 250.0) })/Quad(QuadBez { p0: (106.0, 250.0), p1: (100.0, 251.0), p2: (95.0, 251.0) }) = 9.462322208025613 degrees
* uusignsinh.alt: Quad(QuadBez { p0: (-284.0, -83.0), p1: (-281.0, -83.0), p2: (-278.0, -84.0) })/Quad(QuadBez { p0: (-278.0, -84.0), p1: (-284.0, -82.0), p2: (-298.5, -75.0) }) = 0.0000012074182697257333 degrees
* ndsinh: Quad(QuadBez { p0: (285.0, 298.5), p1: (297.0, 292.0), p2: (300.0, 289.0) })/Quad(QuadBez { p0: (300.0, 289.0), p1: (295.0, 297.0), p2: (295.0, 307.0) }) = 12.994616791916483 degrees
* nda_rephasinh: Quad(QuadBez { p0: (324.0, 298.5), p1: (336.0, 292.0), p2: (339.0, 289.0) })/Quad(QuadBez { p0: (339.0, 289.0), p1: (334.0, 297.0), p2: (334.0, 307.0) }) = 12.994616791916483 degrees
* sinNnAa.virama: Quad(QuadBez { p0: (615.5, 318.5), p1: (632.0, 302.0), p2: (635.0, 279.0) })/Quad(QuadBez { p0: (635.0, 279.0), p1: (637.0, 298.0), p2: (649.0, 312.0) }) = 13.440413928666997 degrees
* nna_rephasinh: Quad(QuadBez { p0: (393.0, 246.0), p1: (393.0, 233.0), p2: (396.0, 210.0) })/Line(Line { p0: (396.0, 210.0), p1: (396.0, 212.0) }) = 7.431407971172489 degrees
* nna_rephasinh: Line(Line { p0: (396.0, 210.0), p1: (396.0, 212.0) })/Quad(QuadBez { p0: (396.0, 212.0), p1: (399.0, 193.0), p2: (399.0, 173.0) }) = 8.972626614896358 degrees
* rsinh: Quad(QuadBez { p0: (132.0, 357.5), p1: (101.0, 330.0), p2: (87.0, 314.0) })/Quad(QuadBez { p0: (87.0, 314.0), p1: (108.0, 334.0), p2: (136.0, 346.0) }) = 5.2112558615867774 degrees
* sssinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* ssRsinh: Quad(QuadBez { p0: (344.0, 269.0), p1: (334.0, 259.0), p2: (320.0, 257.0) })/Quad(QuadBez { p0: (320.0, 257.0), p1: (366.0, 257.0), p2: (392.5, 224.5) }) = 8.130102354156005 degrees
* ssU_rephasinh: Quad(QuadBez { p0: (373.0, 269.0), p1: (363.0, 259.0), p2: (349.0, 257.0) })/Quad(QuadBez { p0: (349.0, 257.0), p1: (395.0, 257.0), p2: (421.5, 224.5) }) = 8.130102354156005 degrees
* ssUu_rephasinh: Quad(QuadBez { p0: (373.0, 269.0), p1: (363.0, 259.0), p2: (349.0, 257.0) })/Quad(QuadBez { p0: (349.0, 257.0), p1: (395.0, 257.0), p2: (421.5, 224.5) }) = 8.130102354156005 degrees
* ssa_rephasinh: Quad(QuadBez { p0: (373.0, 269.0), p1: (363.0, 259.0), p2: (349.0, 257.0) })/Quad(QuadBez { p0: (349.0, 257.0), p1: (395.0, 257.0), p2: (421.5, 224.5) }) = 8.130102354156005 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* u111E8 (U+111E8): Line(Line { p0: (199.0, -114.0), p1: (199.0, -114.0) }) has the same coordinates as a previous segment.
* u111EF (U+111EF): Quad(QuadBez { p0: (489.5, 18.0), p1: (489.0, 19.0), p2: (490.0, 16.0) }) has the same coordinates as a previous segment.
* gRIsinh: Line(Line { p0: (371.0, 298.0), p1: (371.0, 298.0) }) has the same coordinates as a previous segment.
* rAaesinh: Quad(QuadBez { p0: (189.5, 597.0), p1: (190.0, 597.0), p2: (188.0, 596.0) }) has the same coordinates as a previous segment.
* nndda_rephasinh: Line(Line { p0: (238.0, 512.0), p1: (238.0, 512.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* dhU_rephasinh: Line(Line { p0: (382.0, -208.0), p1: (383.0, 19.0) }) (angle: 89.75 degrees, expected: 90.00 degrees)
* dhU_rephasinh: Line(Line { p0: (413.0, 55.0), p1: (411.0, -235.0) }) (angle: -90.40 degrees, expected: -90.00 degrees)
* rsinh: Line(Line { p0: (37.0, 406.0), p1: (38.0, 533.0) }) (angle: 89.55 degrees, expected: 90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'MNIK' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>






### Summary

| 💥 ERROR | 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|---|
| 1 | 14 | 22 | 11 | 83 | 86 | 
| 0% | 6% | 10% | 5% | 38% | 40% | 



