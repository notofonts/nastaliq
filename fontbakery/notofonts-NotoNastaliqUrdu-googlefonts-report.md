## FontBakery report

fontbakery version: 0.10.4

<details><summary><b>[1] Experimental checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Arabic_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| ar_Arab (Arabic) | Shaper didn't attach DammaNS to space |
|  ^  | Shaper didn't attach DammatanNS to space |
|  ^  | Shaper didn't attach KasraNS to space |
|  ^  | Shaper didn't attach AlefSuperiorNS to space |
|  ^  | Shaper didn't attach FathatanNS to space |
|  ^  | Shaper didn't attach ShaddaNS to space |
|  ^  | Shaper didn't attach SukunJazmNS to space |
|  ^  | Shaper didn't attach FathaNS to space |
|  ^  | Shaper didn't attach KasratanNS to space |
| fa_Arab (Persian) | Shaper didn't attach DammatanNS to space |
|  ^  | Shaper didn't attach HamzaAboveNS to space |
|  ^  | Shaper didn't attach FathatanNS to space |
|  ^  | Shaper didn't attach ShaddaNS to space |
|  ^  | Shaper didn't attach KasratanNS to space |

 [code: failed-language-shaping]
* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| br_Latn (Breton) | Some base glyphs were missing: CʼH, cʼh |
|  ^  | Shaper produced a .notdef |
| haw_Latn (Hawaiian) | Some base glyphs were missing: ʻ |
|  ^  | Shaper produced a .notdef |
| mh_Latn (Marshallese) | Some base glyphs were missing: Ḷ, ḷ, Ṃ, ṃ, Ṇ, ṇ, Ọ, ọ |
|  ^  | Some mark glyphs were missing: ◌̣ |
|  ^  | Shaper produced a .notdef |
| qu_Latn (Quechua) | Some base glyphs were missing: CHʼ, Kʼ, Pʼ, Qʼ, Tʼ, chʼ, kʼ, pʼ, qʼ, tʼ |
|  ^  | Shaper produced a .notdef |
| scn_Latn (Sicilian) | Some base glyphs were missing: Ḍ, ḍ |
|  ^  | Shaper produced a .notdef |
| teo_Latn (Teso) | Some base glyphs were missing: Ɔ, Ɛ, Ɨ, Ʉ, ɔ, ɛ, ɨ, ʉ, ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ |
|  ^  | Shaper produced a .notdef |

 [code: failed-language-shaping]
* 🔥 **FAIL** GF_Arabic_Plus glyphset:

| Language | FAIL messages |
| :--- | :--- |
| ps_Arab (Pashto) | Shaper didn't attach DammaNS to space |
|  ^  | Shaper didn't attach DammatanNS to space |
|  ^  | Shaper didn't attach KasraNS to space |
|  ^  | Shaper didn't attach AlefSuperiorNS to space |
|  ^  | Shaper didn't attach HamzaAboveNS to space |
|  ^  | Shaper didn't attach FathatanNS to space |
|  ^  | Shaper didn't attach ShaddaNS to space |
|  ^  | Shaper didn't attach SukunJazmNS to space |
|  ^  | Shaper didn't attach FathaNS to space |
|  ^  | Shaper didn't attach KasratanNS to space |
| sd_Arab (Sindhi) | Some base glyphs were missing: ڪ |
|  ^  | Shaper produced a .notdef |

 [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| lg_Latn (Ganda) | No variant glyphs were found for Eng |
| dyo_Latn (Jola-Fonyi) | No variant glyphs were found for Eng |
| ny_Latn (Nyanja) | No variant glyphs were found for Eng |
| wo_Latn (Wolof) | No variant glyphs were found for Eng |

 [code: warning-language-shaping]
* ⚠ **WARN** GF_Arabic_Plus glyphset:

| Language | FAIL messages |
| :--- | :--- |
| ku_Arab (Kurdish (Arabic)) | No exemplar glyphs were defined for language Kurdish (Arabic) |
| ms_Arab (Malay (Arabic)) | No exemplar glyphs were defined for language Malay (Arabic) |

 [code: warning-language-shaping]
</div></details><br></div></details><details><summary><b>[10] NotoNastaliqUrdu[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Dcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Tcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acutecomb" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0306" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030C" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0302" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0308" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0307" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gravecomb" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030B" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030A" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, coptic, canadian-aboriginal, malayalam, old-permic, syriac, tai-le, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0600 ARABIC NUMBER SIGN: try adding arabic
 * U+0601 ARABIC SIGN SANAH: try adding arabic
 * U+0602 ARABIC FOOTNOTE MARKER: try adding arabic
 * U+0603 ARABIC SIGN SAFHA: try adding arabic
 * U+0604 ARABIC SIGN SAMVAT: try adding arabic
 * U+0609 ARABIC-INDIC PER MILLE SIGN: try adding arabic
 * U+060A ARABIC-INDIC PER TEN THOUSAND SIGN: try adding arabic
 * U+060B AFGHANI SIGN: try adding arabic
 * U+060C ARABIC COMMA: try adding one of: yezidi, nko, thaana, syriac, hanifi-rohingya, arabic
 * U+060D ARABIC DATE SEPARATOR: try adding arabic
 * U+060E ARABIC POETIC VERSE SIGN: try adding arabic
 * U+060F ARABIC SIGN MISRA: try adding arabic
 * U+0610 ARABIC SIGN SALLALLAHOU ALAYHE WASSALLAM: try adding arabic
 * U+0611 ARABIC SIGN ALAYHE ASSALLAM: try adding arabic
 * U+0612 ARABIC SIGN RAHMATULLAH ALAYHE: try adding arabic
 * U+0613 ARABIC SIGN RADI ALLAHOU ANHU: try adding arabic
 * U+0614 ARABIC SIGN TAKHALLUS: try adding arabic
 * U+0615 ARABIC SMALL HIGH TAH: try adding arabic
 * U+061B ARABIC SEMICOLON: try adding one of: yezidi, nko, thaana, syriac, hanifi-rohingya, arabic
 * U+061C ARABIC LETTER MARK: try adding arabic
 * U+061E ARABIC TRIPLE DOT PUNCTUATION MARK: try adding arabic
 * U+061F ARABIC QUESTION MARK: try adding one of: yezidi, adlam, nko, thaana, syriac, hanifi-rohingya, arabic
 * U+0620 ARABIC LETTER KASHMIRI YEH: try adding arabic
 * U+0621 ARABIC LETTER HAMZA: try adding one of: syriac, arabic
 * U+0622 ARABIC LETTER ALEF WITH MADDA ABOVE: try adding arabic
 * U+0623 ARABIC LETTER ALEF WITH HAMZA ABOVE: try adding arabic
 * U+0624 ARABIC LETTER WAW WITH HAMZA ABOVE: try adding arabic
 * U+0625 ARABIC LETTER ALEF WITH HAMZA BELOW: try adding arabic
 * U+0626 ARABIC LETTER YEH WITH HAMZA ABOVE: try adding arabic
 * U+0627 ARABIC LETTER ALEF: try adding one of: indic-siyaq-numbers, arabic
 * U+0628 ARABIC LETTER BEH: try adding arabic
 * U+0629 ARABIC LETTER TEH MARBUTA: try adding arabic
 * U+062A ARABIC LETTER TEH: try adding arabic
 * U+062B ARABIC LETTER THEH: try adding arabic
 * U+062C ARABIC LETTER JEEM: try adding arabic
 * U+062D ARABIC LETTER HAH: try adding arabic
 * U+062E ARABIC LETTER KHAH: try adding arabic
 * U+062F ARABIC LETTER DAL: try adding arabic
 * U+0630 ARABIC LETTER THAL: try adding arabic
 * U+0631 ARABIC LETTER REH: try adding arabic
 * U+0632 ARABIC LETTER ZAIN: try adding arabic
 * U+0633 ARABIC LETTER SEEN: try adding arabic
 * U+0634 ARABIC LETTER SHEEN: try adding arabic
 * U+0635 ARABIC LETTER SAD: try adding arabic
 * U+0636 ARABIC LETTER DAD: try adding arabic
 * U+0637 ARABIC LETTER TAH: try adding arabic
 * U+0638 ARABIC LETTER ZAH: try adding arabic
 * U+0639 ARABIC LETTER AIN: try adding arabic
 * U+063A ARABIC LETTER GHAIN: try adding arabic
 * U+063B ARABIC LETTER KEHEH WITH TWO DOTS ABOVE: try adding arabic
 * U+063C ARABIC LETTER KEHEH WITH THREE DOTS BELOW: try adding arabic
 * U+063D ARABIC LETTER FARSI YEH WITH INVERTED V: try adding arabic
 * U+063E ARABIC LETTER FARSI YEH WITH TWO DOTS ABOVE: try adding arabic
 * U+063F ARABIC LETTER FARSI YEH WITH THREE DOTS ABOVE: try adding arabic
 * U+0640 ARABIC TATWEEL: try adding one of: adlam, old-uyghur, sogdian, manichaean, psalter-pahlavi, mandaic, syriac, hanifi-rohingya, arabic
 * U+0641 ARABIC LETTER FEH: try adding arabic
 * U+0642 ARABIC LETTER QAF: try adding arabic
 * U+0643 ARABIC LETTER KAF: try adding arabic
 * U+0644 ARABIC LETTER LAM: try adding arabic
 * U+0645 ARABIC LETTER MEEM: try adding arabic
 * U+0646 ARABIC LETTER NOON: try adding arabic
 * U+0647 ARABIC LETTER HEH: try adding arabic
 * U+0648 ARABIC LETTER WAW: try adding arabic
 * U+0649 ARABIC LETTER ALEF MAKSURA: try adding arabic
 * U+064A ARABIC LETTER YEH: try adding arabic
 * U+064B ARABIC FATHATAN: try adding one of: syriac, arabic
 * U+064C ARABIC DAMMATAN: try adding one of: syriac, arabic
 * U+064D ARABIC KASRATAN: try adding one of: syriac, arabic
 * U+064E ARABIC FATHA: try adding one of: syriac, arabic
 * U+064F ARABIC DAMMA: try adding one of: syriac, arabic
 * U+0650 ARABIC KASRA: try adding one of: syriac, arabic
 * U+0651 ARABIC SHADDA: try adding one of: syriac, arabic
 * U+0652 ARABIC SUKUN: try adding one of: syriac, arabic
 * U+0653 ARABIC MADDAH ABOVE: try adding one of: syriac, arabic
 * U+0654 ARABIC HAMZA ABOVE: try adding one of: syriac, arabic
 * U+0655 ARABIC HAMZA BELOW: try adding one of: syriac, arabic
 * U+0656 ARABIC SUBSCRIPT ALEF: try adding arabic
 * U+0657 ARABIC INVERTED DAMMA: try adding arabic
 * U+0658 ARABIC MARK NOON GHUNNA: try adding arabic
 * U+0659 ARABIC ZWARAKAY: try adding arabic
 * U+065A ARABIC VOWEL SIGN SMALL V ABOVE: try adding arabic
 * U+065B ARABIC VOWEL SIGN INVERTED SMALL V ABOVE: try adding arabic
 * U+065D ARABIC REVERSED DAMMA: try adding arabic
 * U+065E ARABIC FATHA WITH TWO DOTS: try adding arabic
 * U+065F ARABIC WAVY HAMZA BELOW: try adding arabic
 * U+0660 ARABIC-INDIC DIGIT ZERO: try adding one of: indic-siyaq-numbers, thaana, syriac, hanifi-rohingya, arabic
 * U+0661 ARABIC-INDIC DIGIT ONE: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+0662 ARABIC-INDIC DIGIT TWO: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+0663 ARABIC-INDIC DIGIT THREE: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+0664 ARABIC-INDIC DIGIT FOUR: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+0665 ARABIC-INDIC DIGIT FIVE: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+0666 ARABIC-INDIC DIGIT SIX: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+0667 ARABIC-INDIC DIGIT SEVEN: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+0668 ARABIC-INDIC DIGIT EIGHT: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+0669 ARABIC-INDIC DIGIT NINE: try adding one of: indic-siyaq-numbers, thaana, syriac, arabic
 * U+066A ARABIC PERCENT SIGN: try adding one of: thaana, syriac, nko, arabic
 * U+066B ARABIC DECIMAL SEPARATOR: try adding one of: thaana, syriac, arabic
 * U+066C ARABIC THOUSANDS SEPARATOR: try adding one of: thaana, syriac, arabic
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+066E ARABIC LETTER DOTLESS BEH: try adding arabic
 * U+066F ARABIC LETTER DOTLESS QAF: try adding arabic
 * U+0670 ARABIC LETTER SUPERSCRIPT ALEF: try adding one of: syriac, arabic
 * U+0671 ARABIC LETTER ALEF WASLA: try adding arabic
 * U+0672 ARABIC LETTER ALEF WITH WAVY HAMZA ABOVE: try adding arabic
 * U+0673 ARABIC LETTER ALEF WITH WAVY HAMZA BELOW: try adding arabic
 * U+0679 ARABIC LETTER TTEH: try adding arabic
 * U+067A ARABIC LETTER TTEHEH: try adding arabic
 * U+067B ARABIC LETTER BEEH: try adding arabic
 * U+067C ARABIC LETTER TEH WITH RING: try adding arabic
 * U+067D ARABIC LETTER TEH WITH THREE DOTS ABOVE DOWNWARDS: try adding arabic
 * U+067E ARABIC LETTER PEH: try adding arabic
 * U+067F ARABIC LETTER TEHEH: try adding arabic
 * U+0680 ARABIC LETTER BEHEH: try adding arabic
 * U+0681 ARABIC LETTER HAH WITH HAMZA ABOVE: try adding arabic
 * U+0682 ARABIC LETTER HAH WITH TWO DOTS VERTICAL ABOVE: try adding arabic
 * U+0683 ARABIC LETTER NYEH: try adding arabic
 * U+0684 ARABIC LETTER DYEH: try adding arabic
 * U+0685 ARABIC LETTER HAH WITH THREE DOTS ABOVE: try adding arabic
 * U+0686 ARABIC LETTER TCHEH: try adding arabic
 * U+0687 ARABIC LETTER TCHEHEH: try adding arabic
 * U+0688 ARABIC LETTER DDAL: try adding arabic
 * U+0689 ARABIC LETTER DAL WITH RING: try adding arabic
 * U+068A ARABIC LETTER DAL WITH DOT BELOW: try adding arabic
 * U+068B ARABIC LETTER DAL WITH DOT BELOW AND SMALL TAH: try adding arabic
 * U+068C ARABIC LETTER DAHAL: try adding arabic
 * U+068D ARABIC LETTER DDAHAL: try adding arabic
 * U+068E ARABIC LETTER DUL: try adding arabic
 * U+068F ARABIC LETTER DAL WITH THREE DOTS ABOVE DOWNWARDS: try adding arabic
 * U+0690 ARABIC LETTER DAL WITH FOUR DOTS ABOVE: try adding arabic
 * U+0691 ARABIC LETTER RREH: try adding arabic
 * U+0692 ARABIC LETTER REH WITH SMALL V: try adding arabic
 * U+0693 ARABIC LETTER REH WITH RING: try adding arabic
 * U+0694 ARABIC LETTER REH WITH DOT BELOW: try adding arabic
 * U+0695 ARABIC LETTER REH WITH SMALL V BELOW: try adding arabic
 * U+0696 ARABIC LETTER REH WITH DOT BELOW AND DOT ABOVE: try adding arabic
 * U+0697 ARABIC LETTER REH WITH TWO DOTS ABOVE: try adding arabic
 * U+0698 ARABIC LETTER JEH: try adding arabic
 * U+0699 ARABIC LETTER REH WITH FOUR DOTS ABOVE: try adding arabic
 * U+069A ARABIC LETTER SEEN WITH DOT BELOW AND DOT ABOVE: try adding arabic
 * U+069B ARABIC LETTER SEEN WITH THREE DOTS BELOW: try adding arabic
 * U+069C ARABIC LETTER SEEN WITH THREE DOTS BELOW AND THREE DOTS ABOVE: try adding arabic
 * U+069D ARABIC LETTER SAD WITH TWO DOTS BELOW: try adding arabic
 * U+069E ARABIC LETTER SAD WITH THREE DOTS ABOVE: try adding arabic
 * U+069F ARABIC LETTER TAH WITH THREE DOTS ABOVE: try adding arabic
 * U+06A0 ARABIC LETTER AIN WITH THREE DOTS ABOVE: try adding arabic
 * U+06A1 ARABIC LETTER DOTLESS FEH: try adding arabic
 * U+06A3 ARABIC LETTER FEH WITH DOT BELOW: try adding arabic
 * U+06A4 ARABIC LETTER VEH: try adding arabic
 * U+06A5 ARABIC LETTER FEH WITH THREE DOTS BELOW: try adding arabic
 * U+06A6 ARABIC LETTER PEHEH: try adding arabic
 * U+06A7 ARABIC LETTER QAF WITH DOT ABOVE: try adding arabic
 * U+06A8 ARABIC LETTER QAF WITH THREE DOTS ABOVE: try adding arabic
 * U+06A9 ARABIC LETTER KEHEH: try adding arabic
 * U+06AB ARABIC LETTER KAF WITH RING: try adding arabic
 * U+06AC ARABIC LETTER KAF WITH DOT ABOVE: try adding arabic
 * U+06AD ARABIC LETTER NG: try adding arabic
 * U+06AE ARABIC LETTER KAF WITH THREE DOTS BELOW: try adding arabic
 * U+06AF ARABIC LETTER GAF: try adding arabic
 * U+06B0 ARABIC LETTER GAF WITH RING: try adding arabic
 * U+06B1 ARABIC LETTER NGOEH: try adding arabic
 * U+06B2 ARABIC LETTER GAF WITH TWO DOTS BELOW: try adding arabic
 * U+06B3 ARABIC LETTER GUEH: try adding arabic
 * U+06B4 ARABIC LETTER GAF WITH THREE DOTS ABOVE: try adding arabic
 * U+06B5 ARABIC LETTER LAM WITH SMALL V: try adding arabic
 * U+06B6 ARABIC LETTER LAM WITH DOT ABOVE: try adding arabic
 * U+06B7 ARABIC LETTER LAM WITH THREE DOTS ABOVE: try adding arabic
 * U+06B8 ARABIC LETTER LAM WITH THREE DOTS BELOW: try adding arabic
 * U+06B9 ARABIC LETTER NOON WITH DOT BELOW: try adding arabic
 * U+06BA ARABIC LETTER NOON GHUNNA: try adding arabic
 * U+06BB ARABIC LETTER RNOON: try adding arabic
 * U+06BC ARABIC LETTER NOON WITH RING: try adding arabic
 * U+06BD ARABIC LETTER NOON WITH THREE DOTS ABOVE: try adding arabic
 * U+06BE ARABIC LETTER HEH DOACHASHMEE: try adding arabic
 * U+06BF ARABIC LETTER TCHEH WITH DOT ABOVE: try adding arabic
 * U+06C0 ARABIC LETTER HEH WITH YEH ABOVE: try adding arabic
 * U+06C1 ARABIC LETTER HEH GOAL: try adding arabic
 * U+06C2 ARABIC LETTER HEH GOAL WITH HAMZA ABOVE: try adding arabic
 * U+06C3 ARABIC LETTER TEH MARBUTA GOAL: try adding arabic
 * U+06C4 ARABIC LETTER WAW WITH RING: try adding arabic
 * U+06C5 ARABIC LETTER KIRGHIZ OE: try adding arabic
 * U+06C6 ARABIC LETTER OE: try adding arabic
 * U+06C7 ARABIC LETTER U: try adding arabic
 * U+06C8 ARABIC LETTER YU: try adding arabic
 * U+06C9 ARABIC LETTER KIRGHIZ YU: try adding arabic
 * U+06CA ARABIC LETTER WAW WITH TWO DOTS ABOVE: try adding arabic
 * U+06CB ARABIC LETTER VE: try adding arabic
 * U+06CC ARABIC LETTER FARSI YEH: try adding arabic
 * U+06CD ARABIC LETTER YEH WITH TAIL: try adding arabic
 * U+06CE ARABIC LETTER YEH WITH SMALL V: try adding arabic
 * U+06CF ARABIC LETTER WAW WITH DOT ABOVE: try adding arabic
 * U+06D0 ARABIC LETTER E: try adding arabic
 * U+06D1 ARABIC LETTER YEH WITH THREE DOTS BELOW: try adding arabic
 * U+06D2 ARABIC LETTER YEH BARREE: try adding arabic
 * U+06D3 ARABIC LETTER YEH BARREE WITH HAMZA ABOVE: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: yezidi, hanifi-rohingya, arabic
 * U+06D5 ARABIC LETTER AE: try adding arabic
 * U+06DD ARABIC END OF AYAH: try adding arabic
 * U+06DE ARABIC START OF RUB EL HIZB: try adding arabic
 * U+06E0 ARABIC SMALL HIGH UPRIGHT RECTANGULAR ZERO: try adding arabic
 * U+06E1 ARABIC SMALL HIGH DOTLESS HEAD OF KHAH: try adding arabic
 * U+06E9 ARABIC PLACE OF SAJDAH: try adding arabic
 * U+06EE ARABIC LETTER DAL WITH INVERTED V: try adding arabic
 * U+06EF ARABIC LETTER REH WITH INVERTED V: try adding arabic
 * U+06F0 EXTENDED ARABIC-INDIC DIGIT ZERO: try adding one of: indic-siyaq-numbers, arabic
 * U+06F1 EXTENDED ARABIC-INDIC DIGIT ONE: try adding one of: indic-siyaq-numbers, arabic
 * U+06F2 EXTENDED ARABIC-INDIC DIGIT TWO: try adding one of: indic-siyaq-numbers, arabic
 * U+06F3 EXTENDED ARABIC-INDIC DIGIT THREE: try adding one of: indic-siyaq-numbers, arabic
 * U+06F4 EXTENDED ARABIC-INDIC DIGIT FOUR: try adding one of: indic-siyaq-numbers, arabic
 * U+06F5 EXTENDED ARABIC-INDIC DIGIT FIVE: try adding one of: indic-siyaq-numbers, arabic
 * U+06F6 EXTENDED ARABIC-INDIC DIGIT SIX: try adding one of: indic-siyaq-numbers, arabic
 * U+06F7 EXTENDED ARABIC-INDIC DIGIT SEVEN: try adding one of: indic-siyaq-numbers, arabic
 * U+06F8 EXTENDED ARABIC-INDIC DIGIT EIGHT: try adding one of: indic-siyaq-numbers, arabic
 * U+06F9 EXTENDED ARABIC-INDIC DIGIT NINE: try adding one of: indic-siyaq-numbers, arabic
 * U+06FF ARABIC LETTER HEH WITH INVERTED V: try adding arabic
 * U+0750 ARABIC LETTER BEH WITH THREE DOTS HORIZONTALLY BELOW: try adding arabic
 * U+0751 ARABIC LETTER BEH WITH DOT BELOW AND THREE DOTS ABOVE: try adding arabic
 * U+0752 ARABIC LETTER BEH WITH THREE DOTS POINTING UPWARDS BELOW: try adding arabic
 * U+0753 ARABIC LETTER BEH WITH THREE DOTS POINTING UPWARDS BELOW AND TWO DOTS ABOVE: try adding arabic
 * U+0754 ARABIC LETTER BEH WITH TWO DOTS BELOW AND DOT ABOVE: try adding arabic
 * U+0755 ARABIC LETTER BEH WITH INVERTED SMALL V BELOW: try adding arabic
 * U+0756 ARABIC LETTER BEH WITH SMALL V: try adding arabic
 * U+0757 ARABIC LETTER HAH WITH TWO DOTS ABOVE: try adding arabic
 * U+0758 ARABIC LETTER HAH WITH THREE DOTS POINTING UPWARDS BELOW: try adding arabic
 * U+0759 ARABIC LETTER DAL WITH TWO DOTS VERTICALLY BELOW AND SMALL TAH: try adding arabic
 * U+075A ARABIC LETTER DAL WITH INVERTED SMALL V BELOW: try adding arabic
 * U+075B ARABIC LETTER REH WITH STROKE: try adding arabic
 * U+075C ARABIC LETTER SEEN WITH FOUR DOTS ABOVE: try adding arabic
 * U+075D ARABIC LETTER AIN WITH TWO DOTS ABOVE: try adding arabic
 * U+075E ARABIC LETTER AIN WITH THREE DOTS POINTING DOWNWARDS ABOVE: try adding arabic
 * U+075F ARABIC LETTER AIN WITH TWO DOTS VERTICALLY ABOVE: try adding arabic
 * U+0760 ARABIC LETTER FEH WITH TWO DOTS BELOW: try adding arabic
 * U+0761 ARABIC LETTER FEH WITH THREE DOTS POINTING UPWARDS BELOW: try adding arabic
 * U+0762 ARABIC LETTER KEHEH WITH DOT ABOVE: try adding arabic
 * U+0763 ARABIC LETTER KEHEH WITH THREE DOTS ABOVE: try adding arabic
 * U+0764 ARABIC LETTER KEHEH WITH THREE DOTS POINTING UPWARDS BELOW: try adding arabic
 * U+0765 ARABIC LETTER MEEM WITH DOT ABOVE: try adding arabic
 * U+0766 ARABIC LETTER MEEM WITH DOT BELOW: try adding arabic
 * U+0767 ARABIC LETTER NOON WITH TWO DOTS BELOW: try adding arabic
 * U+0768 ARABIC LETTER NOON WITH SMALL TAH: try adding arabic
 * U+0769 ARABIC LETTER NOON WITH SMALL V: try adding arabic
 * U+076A ARABIC LETTER LAM WITH BAR: try adding arabic
 * U+076B ARABIC LETTER REH WITH TWO DOTS VERTICALLY ABOVE: try adding arabic
 * U+076C ARABIC LETTER REH WITH HAMZA ABOVE: try adding arabic
 * U+076D ARABIC LETTER SEEN WITH TWO DOTS VERTICALLY ABOVE: try adding arabic
 * U+076E ARABIC LETTER HAH WITH SMALL ARABIC LETTER TAH BELOW: try adding arabic
 * U+076F ARABIC LETTER HAH WITH SMALL ARABIC LETTER TAH AND TWO DOTS: try adding arabic
 * U+0770 ARABIC LETTER SEEN WITH SMALL ARABIC LETTER TAH AND TWO DOTS: try adding arabic
 * U+0771 ARABIC LETTER REH WITH SMALL ARABIC LETTER TAH AND TWO DOTS: try adding arabic
 * U+0772 ARABIC LETTER HAH WITH SMALL ARABIC LETTER TAH ABOVE: try adding arabic
 * U+0773 ARABIC LETTER ALEF WITH EXTENDED ARABIC-INDIC DIGIT TWO ABOVE: try adding arabic
 * U+0774 ARABIC LETTER ALEF WITH EXTENDED ARABIC-INDIC DIGIT THREE ABOVE: try adding arabic
 * U+0775 ARABIC LETTER FARSI YEH WITH EXTENDED ARABIC-INDIC DIGIT TWO ABOVE: try adding arabic
 * U+0776 ARABIC LETTER FARSI YEH WITH EXTENDED ARABIC-INDIC DIGIT THREE ABOVE: try adding arabic
 * U+0777 ARABIC LETTER FARSI YEH WITH EXTENDED ARABIC-INDIC DIGIT FOUR BELOW: try adding arabic
 * U+0778 ARABIC LETTER WAW WITH EXTENDED ARABIC-INDIC DIGIT TWO ABOVE: try adding arabic
 * U+0779 ARABIC LETTER WAW WITH EXTENDED ARABIC-INDIC DIGIT THREE ABOVE: try adding arabic
 * U+077A ARABIC LETTER YEH BARREE WITH EXTENDED ARABIC-INDIC DIGIT TWO ABOVE: try adding arabic
 * U+077B ARABIC LETTER YEH BARREE WITH EXTENDED ARABIC-INDIC DIGIT THREE ABOVE: try adding arabic
 * U+077C ARABIC LETTER HAH WITH EXTENDED ARABIC-INDIC DIGIT FOUR BELOW: try adding arabic
 * U+077D ARABIC LETTER SEEN WITH EXTENDED ARABIC-INDIC DIGIT FOUR ABOVE: try adding arabic
 * U+08A0 ARABIC LETTER BEH WITH SMALL V BELOW: try adding arabic
 * U+08A1 ARABIC LETTER BEH WITH HAMZA ABOVE: try adding arabic
 * U+08A2 ARABIC LETTER JEEM WITH TWO DOTS ABOVE: try adding arabic
 * U+08A3 ARABIC LETTER TAH WITH TWO DOTS ABOVE: try adding arabic
 * U+08A4 ARABIC LETTER FEH WITH DOT BELOW AND THREE DOTS ABOVE: try adding arabic
 * U+08A5 ARABIC LETTER QAF WITH DOT BELOW: try adding arabic
 * U+08A6 ARABIC LETTER LAM WITH DOUBLE BAR: try adding arabic
 * U+08A7 ARABIC LETTER MEEM WITH THREE DOTS ABOVE: try adding arabic
 * U+08A8 ARABIC LETTER YEH WITH TWO DOTS BELOW AND HAMZA ABOVE: try adding arabic
 * U+08A9 ARABIC LETTER YEH WITH TWO DOTS BELOW AND DOT ABOVE: try adding arabic
 * U+08AA ARABIC LETTER REH WITH LOOP: try adding arabic
 * U+08AB ARABIC LETTER WAW WITH DOT WITHIN: try adding arabic
 * U+08AC ARABIC LETTER ROHINGYA YEH: try adding arabic
 * U+08AD ARABIC LETTER LOW ALEF: try adding arabic
 * U+08AE ARABIC LETTER DAL WITH THREE DOTS BELOW: try adding arabic
 * U+08AF ARABIC LETTER SAD WITH THREE DOTS BELOW: try adding arabic
 * U+08B0 ARABIC LETTER GAF WITH INVERTED STROKE: try adding arabic
 * U+08B1 ARABIC LETTER STRAIGHT WAW: try adding arabic
 * U+08B2 ARABIC LETTER ZAIN WITH INVERTED V ABOVE: try adding arabic
 * U+08B3 ARABIC LETTER AIN WITH THREE DOTS BELOW: try adding arabic
 * U+08B4 ARABIC LETTER KAF WITH DOT BELOW: try adding arabic
 * U+08B6 ARABIC LETTER BEH WITH SMALL MEEM ABOVE: try adding arabic
 * U+08B7 ARABIC LETTER PEH WITH SMALL MEEM ABOVE: try adding arabic
 * U+08B8 ARABIC LETTER TEH WITH SMALL TEH ABOVE: try adding arabic
 * U+08B9 ARABIC LETTER REH WITH SMALL NOON ABOVE: try adding arabic
 * U+08BA ARABIC LETTER YEH WITH TWO DOTS BELOW AND SMALL NOON ABOVE: try adding arabic
 * U+08BB ARABIC LETTER AFRICAN FEH: try adding arabic
 * U+08BC ARABIC LETTER AFRICAN QAF: try adding arabic
 * U+08BD ARABIC LETTER AFRICAN NOON: try adding arabic
 * U+08BE ARABIC LETTER PEH WITH SMALL V: try adding arabic
 * U+08BF ARABIC LETTER TEH WITH SMALL V: try adding arabic
 * U+08C0 ARABIC LETTER TTEH WITH SMALL V: try adding arabic
 * U+08C1 ARABIC LETTER TCHEH WITH SMALL V: try adding arabic
 * U+08C2 ARABIC LETTER KEHEH WITH SMALL V: try adding arabic
 * U+08C3 ARABIC LETTER GHAIN WITH THREE DOTS ABOVE: try adding arabic
 * U+08C4 ARABIC LETTER AFRICAN QAF WITH THREE DOTS ABOVE: try adding arabic
 * U+08C5 ARABIC LETTER JEEM WITH THREE DOTS ABOVE: try adding arabic
 * U+08C6 ARABIC LETTER JEEM WITH THREE DOTS BELOW: try adding arabic
 * U+08C7 ARABIC LETTER LAM WITH SMALL ARABIC LETTER TAH ABOVE: try adding arabic
 * U+08E3 ARABIC TURNED DAMMA BELOW: try adding arabic
 * U+08E4 ARABIC CURLY FATHA: try adding arabic
 * U+08E5 ARABIC CURLY DAMMA: try adding arabic
 * U+08E6 ARABIC CURLY KASRA: try adding arabic
 * U+08E7 ARABIC CURLY FATHATAN: try adding arabic
 * U+08E8 ARABIC CURLY DAMMATAN: try adding arabic
 * U+08E9 ARABIC CURLY KASRATAN: try adding arabic
 * U+08EA ARABIC TONE ONE DOT ABOVE: try adding arabic
 * U+08EB ARABIC TONE TWO DOTS ABOVE: try adding arabic
 * U+08EC ARABIC TONE LOOP ABOVE: try adding arabic
 * U+08ED ARABIC TONE ONE DOT BELOW: try adding arabic
 * U+08EE ARABIC TONE TWO DOTS BELOW: try adding arabic
 * U+08EF ARABIC TONE LOOP BELOW: try adding arabic
 * U+08F0 ARABIC OPEN FATHATAN: try adding arabic
 * U+08F1 ARABIC OPEN DAMMATAN: try adding arabic
 * U+08F2 ARABIC OPEN KASRATAN: try adding arabic
 * U+08F3 ARABIC SMALL HIGH WAW: try adding arabic
 * U+08F4 ARABIC FATHA WITH RING: try adding arabic
 * U+08F5 ARABIC FATHA WITH DOT ABOVE: try adding arabic
 * U+08F6 ARABIC KASRA WITH DOT BELOW: try adding arabic
 * U+08F7 ARABIC LEFT ARROWHEAD ABOVE: try adding arabic
 * U+08F8 ARABIC RIGHT ARROWHEAD ABOVE: try adding arabic
 * U+08F9 ARABIC LEFT ARROWHEAD BELOW: try adding arabic
 * U+08FA ARABIC RIGHT ARROWHEAD BELOW: try adding arabic
 * U+08FB ARABIC DOUBLE RIGHT ARROWHEAD ABOVE: try adding arabic
 * U+08FC ARABIC DOUBLE RIGHT ARROWHEAD ABOVE WITH DOT: try adding arabic
 * U+08FD ARABIC RIGHT ARROWHEAD ABOVE WITH DOT: try adding arabic
 * U+08FE ARABIC DAMMA WITH DOT: try adding arabic
 * U+08FF ARABIC MARK SIDEWAYS NOON GHUNNA: try adding arabic
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: chakma, duployan, lepcha, tai-tham, devanagari, modi, kayah-li, siddham, sogdian, kaithi, mandaic, thai, balinese, sundanese, khojki, pahawh-hmong, gujarati, kharoshthi, kannada, syloti-nagri, nko, cham, grantha, mahajani, meetei-mayek, rejang, malayalam, bengali, sharada, khudawadi, yi, javanese, brahmi, gurmukhi, khmer, limbu, phags-pa, newa, sinhala, tamil, myanmar, tagbanwa, manichaean, psalter-pahlavi, tai-viet, dogra, hanunoo, buhid, batak, syriac, warang-citi, tirhuta, oriya, telugu, hatran, mongolian, tagalog, takri, buginese, gunjala-gondi, new-tai-lue, saurashtra, avestan, thaana, tai-le, hanifi-rohingya, tifinagh, tibetan
 * U+200D ZERO WIDTH JOINER: try adding one of: chakma, duployan, lepcha, old-hungarian, tai-tham, devanagari, modi, kayah-li, siddham, kaithi, mandaic, thai, balinese, sundanese, khojki, pahawh-hmong, gujarati, kharoshthi, kannada, syloti-nagri, nko, cham, grantha, mahajani, meetei-mayek, rejang, malayalam, bengali, sharada, khudawadi, yi, javanese, brahmi, gurmukhi, limbu, phags-pa, sinhala, newa, tamil, myanmar, tagbanwa, manichaean, psalter-pahlavi, tai-viet, dogra, hanunoo, buhid, batak, syriac, warang-citi, tirhuta, oriya, telugu, mongolian, tagalog, takri, buginese, gunjala-gondi, new-tai-lue, saurashtra, avestan, thaana, tai-le, hanifi-rohingya, tifinagh, tibetan
 * U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, phags-pa, nko, thaana
 * U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, phags-pa, nko, thaana
 * U+2010 HYPHEN: try adding one of: kharoshthi, syloti-nagri, coptic, sora-sompeng, cham, kayah-li, kaithi, sundanese, yi, lisu
 * U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, yi
 * U+2025 TWO DOT LEADER: try adding phags-pa
 * U+25CC DOTTED CIRCLE: try adding one of: kayah-li, siddham, kaithi, mandaic, symbols, thai, marchen, pahawh-hmong, kharoshthi, kannada, nko, grantha, meetei-mayek, mende-kikakui, yi, brahmi, sinhala, miao, manichaean, psalter-pahlavi, batak, oriya, telugu, tai-le, tibetan, duployan, lepcha, modi, khojki, osage, zanabazar-square, mahajani, bengali, khudawadi, phags-pa, gurmukhi, tamil, bhaiksuki, hebrew, tagbanwa, wancho, hanunoo, tirhuta, math, tifinagh, chakma, caucasian-albanian, coptic, ahom, sogdian, bassa-vah, soyombo, gujarati, rejang, sharada, javanese, limbu, khmer, buhid, masaram-gondi, takri, gunjala-gondi, new-tai-lue, thaana, lao, adlam, devanagari, balinese, old-permic, sundanese, syloti-nagri, cham, malayalam, newa, myanmar, elbasan, tai-viet, dogra, music, syriac, mongolian, tagalog, buginese, hanifi-rohingya
 * U+FBB2 ARABIC SYMBOL DOT ABOVE: try adding arabic
 * U+FBB3 ARABIC SYMBOL DOT BELOW: try adding arabic
 * U+FBB4 ARABIC SYMBOL TWO DOTS ABOVE: try adding arabic
 * U+FBB5 ARABIC SYMBOL TWO DOTS BELOW: try adding arabic
 * U+FBB6 ARABIC SYMBOL THREE DOTS ABOVE: try adding arabic
 * U+FBB7 ARABIC SYMBOL THREE DOTS BELOW: try adding arabic
 * U+FBB8 ARABIC SYMBOL THREE DOTS POINTING DOWNWARDS ABOVE: try adding arabic
 * U+FBB9 ARABIC SYMBOL THREE DOTS POINTING DOWNWARDS BELOW: try adding arabic
 * U+FBBA ARABIC SYMBOL FOUR DOTS ABOVE: try adding arabic
 * U+FBBB ARABIC SYMBOL FOUR DOTS BELOW: try adding arabic
 * U+FBBC ARABIC SYMBOL DOUBLE VERTICAL BAR BELOW: try adding arabic
 * U+FBBD ARABIC SYMBOL TWO DOTS VERTICALLY ABOVE: try adding arabic
 * U+FBBE ARABIC SYMBOL TWO DOTS VERTICALLY BELOW: try adding arabic
 * U+FBBF ARABIC SYMBOL RING: try adding arabic
 * U+FBC0 ARABIC SYMBOL SMALL TAH ABOVE: try adding arabic
 * U+FBC1 ARABIC SYMBOL SMALL TAH BELOW: try adding arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic
 * U+FDF2 ARABIC LIGATURE ALLAH ISOLATED FORM: try adding one of: thaana, arabic
 * U+FDF4 ARABIC LIGATURE MOHAMMAD ISOLATED FORM: try adding arabic
 * U+FDFA ARABIC LIGATURE SALLALLAHOU ALAYHE WASALLAM: try adding arabic
 * U+FDFB ARABIC LIGATURE JALLAJALALOUHOU: try adding arabic
 * U+FDFC RIAL SIGN: try adding arabic
 * U+FDFD ARABIC LIGATURE BISMILLAH AR-RAHMAN AR-RAHEEM: try adding one of: thaana, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Noon
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- ArEightBelowAltNS

	- SmallMeem

	- uni0627.short
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Detect any interpolation issues in the font. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/interpolation_issues">com.google.fonts/check/interpolation_issues</a>)</summary><div>


* ⚠ **WARN** Interpolation issues were found in the font:

	- Contour 0 start point differs in glyph 'BehxMed.inT2outD2HS' between location wght=400 and location wght=700

	- Contour 0 start point differs in glyph 'RehFin.inD3MM' between location wght=400 and location wght=700

	- Contour 0 start point differs in glyph 'BehxMed.inT2outD2HF' between location wght=400 and location wght=700 [code: interpolation-issues]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 567 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 559:
greater, less
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Ebira (Latn, 2,200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 8 | 103 | 8 | 133 | 0 |
| 0% | 1% | 3% | 40% | 3% | 52% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
