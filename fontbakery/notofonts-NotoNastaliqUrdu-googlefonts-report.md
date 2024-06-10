## FontBakery report

fontbakery version: 0.12.7



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoNastaliqUrdu[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoNastaliqUrdu/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[8] NotoNastaliqUrdu[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Arabic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ar_Arab (Arabic)</td>
<td align="left">Shaper didn't attach AlefSuperiorNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach MaddaNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach HamzaAboveNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach HamzaBelowNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach FathatanNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach DammatanNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach KasratanNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach FathaNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach DammaNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach KasraNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach ShaddaNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach SukunJazmNS to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach KasraNS to ShaddaNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach KasratanNS to ShaddaNS</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Arabic_Plus glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sd_Arab (Sindhi)</td>
<td align="left">Some base glyphs were missing: ڪ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">.fina version of ARABIC LETTER SWASH KAF; both buffers returned .notdef=1+900</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">.medi version of ARABIC LETTER SWASH KAF; both buffers returned space=1+0</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">.init version of ARABIC LETTER SWASH KAF; both buffers returned space=0+0</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Arabic_Plus glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ms_Arab (Malay (Arabic))</td>
<td align="left">No exemplar glyphs were defined for language Malay (Arabic)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Arabic_Plus glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sd_Arab (Sindhi)</td>
<td align="left">Some auxiliary glyphs were missing: ڪ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 in glyph 'HamzaBelowAF_AltNS': becomes underweight between wght=400 and wght=700.

- Contour 0 point 61 in glyph 'TahIni.HRlow' has a kink between location wght=400 and location wght=700

- Contour 0 point 29 in glyph 'HehMed.inD5outD2H' has a kink between location wght=400 and location wght=700

- Contour 0 point 26 in glyph 'GafInvIni.NoutD11' has a kink between location wght=400 and location wght=700

- Contour 1 point 8 in glyph 'SadSep' has a kink between location wght=400 and location wght=700

- Contour 0 in glyph 'nine': becomes underweight between wght=400 and wght=700.

- Contour 0 point 31 in glyph 'nine' has a kink between location wght=400 and location wght=700

- Contour 0 point 46 in glyph 'YehBarreeFin' has a kink between location wght=400 and location wght=700

- Contour 0 point 31 in glyph 'SeenMed.SWinAoutT2' has a kink between location wght=400 and location wght=700

- Contour 0 point 26 in glyph 'KafIni.NoutD11' has a kink between location wght=400 and location wght=700

- Contour 0 point 40 in glyph 'uniFDFD' has a kink between location wght=400 and location wght=700

- Contour 0 point 57 in glyph 'TahMed.HRlow' has a kink between location wght=400 and location wght=700

- Contour 0 in glyph 'Safhah': becomes underweight between wght=400 and wght=700.

- Contour 0 in glyph 'SadMed.inD1outD1': becomes underweight between wght=400 and wght=700.

- Contour 0 point 36 in glyph 'SadMed.inD1outD1' has a kink between location wght=400 and location wght=700

- Contour 0 point 42 in glyph 'SadMed.inD1outD1' has a kink between location wght=400 and location wght=700

- Contour 0 in glyph 'TahDotEnclNS': becomes underweight between wght=400 and wght=700.

- Contour 0 point 10 in glyph 'seven.encl' has a kink between location wght=400 and location wght=700
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 567 among a set of 5 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 559:
less, greater</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- ArEightBelowAltNS

- SmallMeem

- uni0627.short
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Gulay (Latn, 250,478 speakers), Ekpeye (Latn, 226,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Makaa (Latn, 221,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mango (Latn, 77,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Vute (Latn, 21,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Nateni (Latn, 100,000 speakers), Avokaya (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), Aghem (Latn, 38,843 speakers), South Central Banda (Latn, 244,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Dii (Latn, 71,000 speakers), Cicipu (Latn, 44,000 speakers), Igbo (Latn, 27,823,640 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Ebira (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, canadian-aboriginal, malayalam, tifinagh, math, syriac, tai-le, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0600 ARABIC NUMBER SIGN: try adding arabic</li>
<li>U+0601 ARABIC SIGN SANAH: try adding arabic</li>
<li>U+0602 ARABIC FOOTNOTE MARKER: try adding arabic</li>
<li>U+0603 ARABIC SIGN SAFHA: try adding arabic</li>
<li>U+0604 ARABIC SIGN SAMVAT: try adding arabic</li>
<li>U+0609 ARABIC-INDIC PER MILLE SIGN: try adding arabic</li>
<li>U+060A ARABIC-INDIC PER TEN THOUSAND SIGN: try adding arabic</li>
<li>U+060B AFGHANI SIGN: try adding arabic</li>
<li>U+060C ARABIC COMMA: try adding one of: nko, hanifi-rohingya, yezidi, arabic, syriac, thaana</li>
<li>U+060D ARABIC DATE SEPARATOR: try adding arabic</li>
<li>U+060E ARABIC POETIC VERSE SIGN: try adding arabic</li>
<li>U+060F ARABIC SIGN MISRA: try adding arabic</li>
<li>U+0610 ARABIC SIGN SALLALLAHOU ALAYHE WASSALLAM: try adding arabic</li>
<li>U+0611 ARABIC SIGN ALAYHE ASSALLAM: try adding arabic</li>
<li>U+0612 ARABIC SIGN RAHMATULLAH ALAYHE: try adding arabic</li>
<li>U+0613 ARABIC SIGN RADI ALLAHOU ANHU: try adding arabic</li>
<li>U+0614 ARABIC SIGN TAKHALLUS: try adding arabic</li>
<li>U+0615 ARABIC SMALL HIGH TAH: try adding arabic</li>
<li>U+061B ARABIC SEMICOLON: try adding one of: nko, hanifi-rohingya, yezidi, arabic, syriac, thaana</li>
<li>U+061C ARABIC LETTER MARK: try adding one of: arabic, thaana, syriac</li>
<li>U+061E ARABIC TRIPLE DOT PUNCTUATION MARK: try adding arabic</li>
<li>U+061F ARABIC QUESTION MARK: try adding one of: nko, hanifi-rohingya, yezidi, arabic, syriac, thaana, adlam</li>
<li>U+0620 ARABIC LETTER KASHMIRI YEH: try adding arabic</li>
<li>U+0621 ARABIC LETTER HAMZA: try adding one of: arabic, syriac</li>
<li>U+0622 ARABIC LETTER ALEF WITH MADDA ABOVE: try adding arabic</li>
<li>U+0623 ARABIC LETTER ALEF WITH HAMZA ABOVE: try adding arabic</li>
<li>U+0624 ARABIC LETTER WAW WITH HAMZA ABOVE: try adding arabic</li>
<li>U+0625 ARABIC LETTER ALEF WITH HAMZA BELOW: try adding arabic</li>
<li>U+0626 ARABIC LETTER YEH WITH HAMZA ABOVE: try adding arabic</li>
<li>U+0627 ARABIC LETTER ALEF: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+0628 ARABIC LETTER BEH: try adding arabic</li>
<li>U+0629 ARABIC LETTER TEH MARBUTA: try adding arabic</li>
<li>U+062A ARABIC LETTER TEH: try adding arabic</li>
<li>U+062B ARABIC LETTER THEH: try adding arabic</li>
<li>U+062C ARABIC LETTER JEEM: try adding arabic</li>
<li>U+062D ARABIC LETTER HAH: try adding arabic</li>
<li>U+062E ARABIC LETTER KHAH: try adding arabic</li>
<li>U+062F ARABIC LETTER DAL: try adding arabic</li>
<li>U+0630 ARABIC LETTER THAL: try adding arabic</li>
<li>U+0631 ARABIC LETTER REH: try adding arabic</li>
<li>U+0632 ARABIC LETTER ZAIN: try adding arabic</li>
<li>U+0633 ARABIC LETTER SEEN: try adding arabic</li>
<li>U+0634 ARABIC LETTER SHEEN: try adding arabic</li>
<li>U+0635 ARABIC LETTER SAD: try adding arabic</li>
<li>U+0636 ARABIC LETTER DAD: try adding arabic</li>
<li>U+0637 ARABIC LETTER TAH: try adding arabic</li>
<li>U+0638 ARABIC LETTER ZAH: try adding arabic</li>
<li>U+0639 ARABIC LETTER AIN: try adding arabic</li>
<li>U+063A ARABIC LETTER GHAIN: try adding arabic</li>
<li>U+063B ARABIC LETTER KEHEH WITH TWO DOTS ABOVE: try adding arabic</li>
<li>U+063C ARABIC LETTER KEHEH WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+063D ARABIC LETTER FARSI YEH WITH INVERTED V: try adding arabic</li>
<li>U+063E ARABIC LETTER FARSI YEH WITH TWO DOTS ABOVE: try adding arabic</li>
<li>U+063F ARABIC LETTER FARSI YEH WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+0640 ARABIC TATWEEL: try adding one of: mandaic, psalter-pahlavi, manichaean, sogdian, hanifi-rohingya, old-uyghur, arabic, syriac, adlam</li>
<li>U+0641 ARABIC LETTER FEH: try adding arabic</li>
<li>U+0642 ARABIC LETTER QAF: try adding arabic</li>
<li>U+0643 ARABIC LETTER KAF: try adding arabic</li>
<li>U+0644 ARABIC LETTER LAM: try adding arabic</li>
<li>U+0645 ARABIC LETTER MEEM: try adding arabic</li>
<li>U+0646 ARABIC LETTER NOON: try adding arabic</li>
<li>U+0647 ARABIC LETTER HEH: try adding arabic</li>
<li>U+0648 ARABIC LETTER WAW: try adding arabic</li>
<li>U+0649 ARABIC LETTER ALEF MAKSURA: try adding arabic</li>
<li>U+064A ARABIC LETTER YEH: try adding arabic</li>
<li>U+064B ARABIC FATHATAN: try adding one of: arabic, syriac</li>
<li>U+064C ARABIC DAMMATAN: try adding one of: arabic, syriac</li>
<li>U+064D ARABIC KASRATAN: try adding one of: arabic, syriac</li>
<li>U+064E ARABIC FATHA: try adding one of: arabic, syriac</li>
<li>U+064F ARABIC DAMMA: try adding one of: arabic, syriac</li>
<li>U+0650 ARABIC KASRA: try adding one of: arabic, syriac</li>
<li>U+0651 ARABIC SHADDA: try adding one of: arabic, syriac</li>
<li>U+0652 ARABIC SUKUN: try adding one of: arabic, syriac</li>
<li>U+0653 ARABIC MADDAH ABOVE: try adding one of: arabic, syriac</li>
<li>U+0654 ARABIC HAMZA ABOVE: try adding one of: arabic, syriac</li>
<li>U+0655 ARABIC HAMZA BELOW: try adding one of: arabic, syriac</li>
<li>U+0656 ARABIC SUBSCRIPT ALEF: try adding arabic</li>
<li>U+0657 ARABIC INVERTED DAMMA: try adding arabic</li>
<li>U+0658 ARABIC MARK NOON GHUNNA: try adding arabic</li>
<li>U+0659 ARABIC ZWARAKAY: try adding arabic</li>
<li>U+065A ARABIC VOWEL SIGN SMALL V ABOVE: try adding arabic</li>
<li>U+065B ARABIC VOWEL SIGN INVERTED SMALL V ABOVE: try adding arabic</li>
<li>U+065D ARABIC REVERSED DAMMA: try adding arabic</li>
<li>U+065E ARABIC FATHA WITH TWO DOTS: try adding arabic</li>
<li>U+065F ARABIC WAVY HAMZA BELOW: try adding arabic</li>
<li>U+0660 ARABIC-INDIC DIGIT ZERO: try adding one of: hanifi-rohingya, yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0661 ARABIC-INDIC DIGIT ONE: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0662 ARABIC-INDIC DIGIT TWO: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0663 ARABIC-INDIC DIGIT THREE: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0664 ARABIC-INDIC DIGIT FOUR: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0665 ARABIC-INDIC DIGIT FIVE: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0666 ARABIC-INDIC DIGIT SIX: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0667 ARABIC-INDIC DIGIT SEVEN: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0668 ARABIC-INDIC DIGIT EIGHT: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+0669 ARABIC-INDIC DIGIT NINE: try adding one of: yezidi, indic-siyaq-numbers, arabic, thaana, syriac</li>
<li>U+066A ARABIC PERCENT SIGN: try adding one of: arabic, thaana, syriac, nko</li>
<li>U+066B ARABIC DECIMAL SEPARATOR: try adding one of: arabic, thaana, syriac</li>
<li>U+066C ARABIC THOUSANDS SEPARATOR: try adding one of: arabic, thaana, syriac</li>
<li>U+066D ARABIC FIVE POINTED STAR: try adding arabic</li>
<li>U+066E ARABIC LETTER DOTLESS BEH: try adding arabic</li>
<li>U+066F ARABIC LETTER DOTLESS QAF: try adding arabic</li>
<li>U+0670 ARABIC LETTER SUPERSCRIPT ALEF: try adding one of: arabic, syriac</li>
<li>U+0671 ARABIC LETTER ALEF WASLA: try adding arabic</li>
<li>U+0672 ARABIC LETTER ALEF WITH WAVY HAMZA ABOVE: try adding arabic</li>
<li>U+0673 ARABIC LETTER ALEF WITH WAVY HAMZA BELOW: try adding arabic</li>
<li>U+0679 ARABIC LETTER TTEH: try adding arabic</li>
<li>U+067A ARABIC LETTER TTEHEH: try adding arabic</li>
<li>U+067B ARABIC LETTER BEEH: try adding arabic</li>
<li>U+067C ARABIC LETTER TEH WITH RING: try adding arabic</li>
<li>U+067D ARABIC LETTER TEH WITH THREE DOTS ABOVE DOWNWARDS: try adding arabic</li>
<li>U+067E ARABIC LETTER PEH: try adding arabic</li>
<li>U+067F ARABIC LETTER TEHEH: try adding arabic</li>
<li>U+0680 ARABIC LETTER BEHEH: try adding arabic</li>
<li>U+0681 ARABIC LETTER HAH WITH HAMZA ABOVE: try adding arabic</li>
<li>U+0682 ARABIC LETTER HAH WITH TWO DOTS VERTICAL ABOVE: try adding arabic</li>
<li>U+0683 ARABIC LETTER NYEH: try adding arabic</li>
<li>U+0684 ARABIC LETTER DYEH: try adding arabic</li>
<li>U+0685 ARABIC LETTER HAH WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+0686 ARABIC LETTER TCHEH: try adding arabic</li>
<li>U+0687 ARABIC LETTER TCHEHEH: try adding arabic</li>
<li>U+0688 ARABIC LETTER DDAL: try adding arabic</li>
<li>U+0689 ARABIC LETTER DAL WITH RING: try adding arabic</li>
<li>U+068A ARABIC LETTER DAL WITH DOT BELOW: try adding arabic</li>
<li>U+068B ARABIC LETTER DAL WITH DOT BELOW AND SMALL TAH: try adding arabic</li>
<li>U+068C ARABIC LETTER DAHAL: try adding arabic</li>
<li>U+068D ARABIC LETTER DDAHAL: try adding arabic</li>
<li>U+068E ARABIC LETTER DUL: try adding arabic</li>
<li>U+068F ARABIC LETTER DAL WITH THREE DOTS ABOVE DOWNWARDS: try adding arabic</li>
<li>U+0690 ARABIC LETTER DAL WITH FOUR DOTS ABOVE: try adding arabic</li>
<li>U+0691 ARABIC LETTER RREH: try adding arabic</li>
<li>U+0692 ARABIC LETTER REH WITH SMALL V: try adding arabic</li>
<li>U+0693 ARABIC LETTER REH WITH RING: try adding arabic</li>
<li>U+0694 ARABIC LETTER REH WITH DOT BELOW: try adding arabic</li>
<li>U+0695 ARABIC LETTER REH WITH SMALL V BELOW: try adding arabic</li>
<li>U+0696 ARABIC LETTER REH WITH DOT BELOW AND DOT ABOVE: try adding arabic</li>
<li>U+0697 ARABIC LETTER REH WITH TWO DOTS ABOVE: try adding arabic</li>
<li>U+0698 ARABIC LETTER JEH: try adding arabic</li>
<li>U+0699 ARABIC LETTER REH WITH FOUR DOTS ABOVE: try adding arabic</li>
<li>U+069A ARABIC LETTER SEEN WITH DOT BELOW AND DOT ABOVE: try adding arabic</li>
<li>U+069B ARABIC LETTER SEEN WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+069C ARABIC LETTER SEEN WITH THREE DOTS BELOW AND THREE DOTS ABOVE: try adding arabic</li>
<li>U+069D ARABIC LETTER SAD WITH TWO DOTS BELOW: try adding arabic</li>
<li>U+069E ARABIC LETTER SAD WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+069F ARABIC LETTER TAH WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+06A0 ARABIC LETTER AIN WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+06A1 ARABIC LETTER DOTLESS FEH: try adding arabic</li>
<li>U+06A3 ARABIC LETTER FEH WITH DOT BELOW: try adding arabic</li>
<li>U+06A4 ARABIC LETTER VEH: try adding arabic</li>
<li>U+06A5 ARABIC LETTER FEH WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+06A6 ARABIC LETTER PEHEH: try adding arabic</li>
<li>U+06A7 ARABIC LETTER QAF WITH DOT ABOVE: try adding arabic</li>
<li>U+06A8 ARABIC LETTER QAF WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+06A9 ARABIC LETTER KEHEH: try adding arabic</li>
<li>U+06AB ARABIC LETTER KAF WITH RING: try adding arabic</li>
<li>U+06AC ARABIC LETTER KAF WITH DOT ABOVE: try adding arabic</li>
<li>U+06AD ARABIC LETTER NG: try adding arabic</li>
<li>U+06AE ARABIC LETTER KAF WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+06AF ARABIC LETTER GAF: try adding arabic</li>
<li>U+06B0 ARABIC LETTER GAF WITH RING: try adding arabic</li>
<li>U+06B1 ARABIC LETTER NGOEH: try adding arabic</li>
<li>U+06B2 ARABIC LETTER GAF WITH TWO DOTS BELOW: try adding arabic</li>
<li>U+06B3 ARABIC LETTER GUEH: try adding arabic</li>
<li>U+06B4 ARABIC LETTER GAF WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+06B5 ARABIC LETTER LAM WITH SMALL V: try adding arabic</li>
<li>U+06B6 ARABIC LETTER LAM WITH DOT ABOVE: try adding arabic</li>
<li>U+06B7 ARABIC LETTER LAM WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+06B8 ARABIC LETTER LAM WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+06B9 ARABIC LETTER NOON WITH DOT BELOW: try adding arabic</li>
<li>U+06BA ARABIC LETTER NOON GHUNNA: try adding arabic</li>
<li>U+06BB ARABIC LETTER RNOON: try adding arabic</li>
<li>U+06BC ARABIC LETTER NOON WITH RING: try adding arabic</li>
<li>U+06BD ARABIC LETTER NOON WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+06BE ARABIC LETTER HEH DOACHASHMEE: try adding arabic</li>
<li>U+06BF ARABIC LETTER TCHEH WITH DOT ABOVE: try adding arabic</li>
<li>U+06C0 ARABIC LETTER HEH WITH YEH ABOVE: try adding arabic</li>
<li>U+06C1 ARABIC LETTER HEH GOAL: try adding arabic</li>
<li>U+06C2 ARABIC LETTER HEH GOAL WITH HAMZA ABOVE: try adding arabic</li>
<li>U+06C3 ARABIC LETTER TEH MARBUTA GOAL: try adding arabic</li>
<li>U+06C4 ARABIC LETTER WAW WITH RING: try adding arabic</li>
<li>U+06C5 ARABIC LETTER KIRGHIZ OE: try adding arabic</li>
<li>U+06C6 ARABIC LETTER OE: try adding arabic</li>
<li>U+06C7 ARABIC LETTER U: try adding arabic</li>
<li>U+06C8 ARABIC LETTER YU: try adding arabic</li>
<li>U+06C9 ARABIC LETTER KIRGHIZ YU: try adding arabic</li>
<li>U+06CA ARABIC LETTER WAW WITH TWO DOTS ABOVE: try adding arabic</li>
<li>U+06CB ARABIC LETTER VE: try adding arabic</li>
<li>U+06CC ARABIC LETTER FARSI YEH: try adding arabic</li>
<li>U+06CD ARABIC LETTER YEH WITH TAIL: try adding arabic</li>
<li>U+06CE ARABIC LETTER YEH WITH SMALL V: try adding arabic</li>
<li>U+06CF ARABIC LETTER WAW WITH DOT ABOVE: try adding arabic</li>
<li>U+06D0 ARABIC LETTER E: try adding arabic</li>
<li>U+06D1 ARABIC LETTER YEH WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+06D2 ARABIC LETTER YEH BARREE: try adding arabic</li>
<li>U+06D3 ARABIC LETTER YEH BARREE WITH HAMZA ABOVE: try adding arabic</li>
<li>U+06D4 ARABIC FULL STOP: try adding one of: yezidi, hanifi-rohingya, arabic</li>
<li>U+06D5 ARABIC LETTER AE: try adding arabic</li>
<li>U+06DD ARABIC END OF AYAH: try adding arabic</li>
<li>U+06DE ARABIC START OF RUB EL HIZB: try adding arabic</li>
<li>U+06E0 ARABIC SMALL HIGH UPRIGHT RECTANGULAR ZERO: try adding arabic</li>
<li>U+06E1 ARABIC SMALL HIGH DOTLESS HEAD OF KHAH: try adding arabic</li>
<li>U+06E9 ARABIC PLACE OF SAJDAH: try adding arabic</li>
<li>U+06EE ARABIC LETTER DAL WITH INVERTED V: try adding arabic</li>
<li>U+06EF ARABIC LETTER REH WITH INVERTED V: try adding arabic</li>
<li>U+06F0 EXTENDED ARABIC-INDIC DIGIT ZERO: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F1 EXTENDED ARABIC-INDIC DIGIT ONE: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F2 EXTENDED ARABIC-INDIC DIGIT TWO: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F3 EXTENDED ARABIC-INDIC DIGIT THREE: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F4 EXTENDED ARABIC-INDIC DIGIT FOUR: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F5 EXTENDED ARABIC-INDIC DIGIT FIVE: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F6 EXTENDED ARABIC-INDIC DIGIT SIX: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F7 EXTENDED ARABIC-INDIC DIGIT SEVEN: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F8 EXTENDED ARABIC-INDIC DIGIT EIGHT: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06F9 EXTENDED ARABIC-INDIC DIGIT NINE: try adding one of: indic-siyaq-numbers, arabic</li>
<li>U+06FF ARABIC LETTER HEH WITH INVERTED V: try adding arabic</li>
<li>U+0750 ARABIC LETTER BEH WITH THREE DOTS HORIZONTALLY BELOW: try adding arabic</li>
<li>U+0751 ARABIC LETTER BEH WITH DOT BELOW AND THREE DOTS ABOVE: try adding arabic</li>
<li>U+0752 ARABIC LETTER BEH WITH THREE DOTS POINTING UPWARDS BELOW: try adding arabic</li>
<li>U+0753 ARABIC LETTER BEH WITH THREE DOTS POINTING UPWARDS BELOW AND TWO DOTS ABOVE: try adding arabic</li>
<li>U+0754 ARABIC LETTER BEH WITH TWO DOTS BELOW AND DOT ABOVE: try adding arabic</li>
<li>U+0755 ARABIC LETTER BEH WITH INVERTED SMALL V BELOW: try adding arabic</li>
<li>U+0756 ARABIC LETTER BEH WITH SMALL V: try adding arabic</li>
<li>U+0757 ARABIC LETTER HAH WITH TWO DOTS ABOVE: try adding arabic</li>
<li>U+0758 ARABIC LETTER HAH WITH THREE DOTS POINTING UPWARDS BELOW: try adding arabic</li>
<li>U+0759 ARABIC LETTER DAL WITH TWO DOTS VERTICALLY BELOW AND SMALL TAH: try adding arabic</li>
<li>U+075A ARABIC LETTER DAL WITH INVERTED SMALL V BELOW: try adding arabic</li>
<li>U+075B ARABIC LETTER REH WITH STROKE: try adding arabic</li>
<li>U+075C ARABIC LETTER SEEN WITH FOUR DOTS ABOVE: try adding arabic</li>
<li>U+075D ARABIC LETTER AIN WITH TWO DOTS ABOVE: try adding arabic</li>
<li>U+075E ARABIC LETTER AIN WITH THREE DOTS POINTING DOWNWARDS ABOVE: try adding arabic</li>
<li>U+075F ARABIC LETTER AIN WITH TWO DOTS VERTICALLY ABOVE: try adding arabic</li>
<li>U+0760 ARABIC LETTER FEH WITH TWO DOTS BELOW: try adding arabic</li>
<li>U+0761 ARABIC LETTER FEH WITH THREE DOTS POINTING UPWARDS BELOW: try adding arabic</li>
<li>U+0762 ARABIC LETTER KEHEH WITH DOT ABOVE: try adding arabic</li>
<li>U+0763 ARABIC LETTER KEHEH WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+0764 ARABIC LETTER KEHEH WITH THREE DOTS POINTING UPWARDS BELOW: try adding arabic</li>
<li>U+0765 ARABIC LETTER MEEM WITH DOT ABOVE: try adding arabic</li>
<li>U+0766 ARABIC LETTER MEEM WITH DOT BELOW: try adding arabic</li>
<li>U+0767 ARABIC LETTER NOON WITH TWO DOTS BELOW: try adding arabic</li>
<li>U+0768 ARABIC LETTER NOON WITH SMALL TAH: try adding arabic</li>
<li>U+0769 ARABIC LETTER NOON WITH SMALL V: try adding arabic</li>
<li>U+076A ARABIC LETTER LAM WITH BAR: try adding arabic</li>
<li>U+076B ARABIC LETTER REH WITH TWO DOTS VERTICALLY ABOVE: try adding arabic</li>
<li>U+076C ARABIC LETTER REH WITH HAMZA ABOVE: try adding arabic</li>
<li>U+076D ARABIC LETTER SEEN WITH TWO DOTS VERTICALLY ABOVE: try adding arabic</li>
<li>U+076E ARABIC LETTER HAH WITH SMALL ARABIC LETTER TAH BELOW: try adding arabic</li>
<li>U+076F ARABIC LETTER HAH WITH SMALL ARABIC LETTER TAH AND TWO DOTS: try adding arabic</li>
<li>U+0770 ARABIC LETTER SEEN WITH SMALL ARABIC LETTER TAH AND TWO DOTS: try adding arabic</li>
<li>U+0771 ARABIC LETTER REH WITH SMALL ARABIC LETTER TAH AND TWO DOTS: try adding arabic</li>
<li>U+0772 ARABIC LETTER HAH WITH SMALL ARABIC LETTER TAH ABOVE: try adding arabic</li>
<li>U+0773 ARABIC LETTER ALEF WITH EXTENDED ARABIC-INDIC DIGIT TWO ABOVE: try adding arabic</li>
<li>U+0774 ARABIC LETTER ALEF WITH EXTENDED ARABIC-INDIC DIGIT THREE ABOVE: try adding arabic</li>
<li>U+0775 ARABIC LETTER FARSI YEH WITH EXTENDED ARABIC-INDIC DIGIT TWO ABOVE: try adding arabic</li>
<li>U+0776 ARABIC LETTER FARSI YEH WITH EXTENDED ARABIC-INDIC DIGIT THREE ABOVE: try adding arabic</li>
<li>U+0777 ARABIC LETTER FARSI YEH WITH EXTENDED ARABIC-INDIC DIGIT FOUR BELOW: try adding arabic</li>
<li>U+0778 ARABIC LETTER WAW WITH EXTENDED ARABIC-INDIC DIGIT TWO ABOVE: try adding arabic</li>
<li>U+0779 ARABIC LETTER WAW WITH EXTENDED ARABIC-INDIC DIGIT THREE ABOVE: try adding arabic</li>
<li>U+077A ARABIC LETTER YEH BARREE WITH EXTENDED ARABIC-INDIC DIGIT TWO ABOVE: try adding arabic</li>
<li>U+077B ARABIC LETTER YEH BARREE WITH EXTENDED ARABIC-INDIC DIGIT THREE ABOVE: try adding arabic</li>
<li>U+077C ARABIC LETTER HAH WITH EXTENDED ARABIC-INDIC DIGIT FOUR BELOW: try adding arabic</li>
<li>U+077D ARABIC LETTER SEEN WITH EXTENDED ARABIC-INDIC DIGIT FOUR ABOVE: try adding arabic</li>
<li>U+08A0 ARABIC LETTER BEH WITH SMALL V BELOW: try adding arabic</li>
<li>U+08A1 ARABIC LETTER BEH WITH HAMZA ABOVE: try adding arabic</li>
<li>U+08A2 ARABIC LETTER JEEM WITH TWO DOTS ABOVE: try adding arabic</li>
<li>U+08A3 ARABIC LETTER TAH WITH TWO DOTS ABOVE: try adding arabic</li>
<li>U+08A4 ARABIC LETTER FEH WITH DOT BELOW AND THREE DOTS ABOVE: try adding arabic</li>
<li>U+08A5 ARABIC LETTER QAF WITH DOT BELOW: try adding arabic</li>
<li>U+08A6 ARABIC LETTER LAM WITH DOUBLE BAR: try adding arabic</li>
<li>U+08A7 ARABIC LETTER MEEM WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+08A8 ARABIC LETTER YEH WITH TWO DOTS BELOW AND HAMZA ABOVE: try adding arabic</li>
<li>U+08A9 ARABIC LETTER YEH WITH TWO DOTS BELOW AND DOT ABOVE: try adding arabic</li>
<li>U+08AA ARABIC LETTER REH WITH LOOP: try adding arabic</li>
<li>U+08AB ARABIC LETTER WAW WITH DOT WITHIN: try adding arabic</li>
<li>U+08AC ARABIC LETTER ROHINGYA YEH: try adding arabic</li>
<li>U+08AD ARABIC LETTER LOW ALEF: try adding arabic</li>
<li>U+08AE ARABIC LETTER DAL WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+08AF ARABIC LETTER SAD WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+08B0 ARABIC LETTER GAF WITH INVERTED STROKE: try adding arabic</li>
<li>U+08B1 ARABIC LETTER STRAIGHT WAW: try adding arabic</li>
<li>U+08B2 ARABIC LETTER ZAIN WITH INVERTED V ABOVE: try adding arabic</li>
<li>U+08B3 ARABIC LETTER AIN WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+08B4 ARABIC LETTER KAF WITH DOT BELOW: try adding arabic</li>
<li>U+08B6 ARABIC LETTER BEH WITH SMALL MEEM ABOVE: try adding arabic</li>
<li>U+08B7 ARABIC LETTER PEH WITH SMALL MEEM ABOVE: try adding arabic</li>
<li>U+08B8 ARABIC LETTER TEH WITH SMALL TEH ABOVE: try adding arabic</li>
<li>U+08B9 ARABIC LETTER REH WITH SMALL NOON ABOVE: try adding arabic</li>
<li>U+08BA ARABIC LETTER YEH WITH TWO DOTS BELOW AND SMALL NOON ABOVE: try adding arabic</li>
<li>U+08BB ARABIC LETTER AFRICAN FEH: try adding arabic</li>
<li>U+08BC ARABIC LETTER AFRICAN QAF: try adding arabic</li>
<li>U+08BD ARABIC LETTER AFRICAN NOON: try adding arabic</li>
<li>U+08BE ARABIC LETTER PEH WITH SMALL V: try adding arabic</li>
<li>U+08BF ARABIC LETTER TEH WITH SMALL V: try adding arabic</li>
<li>U+08C0 ARABIC LETTER TTEH WITH SMALL V: try adding arabic</li>
<li>U+08C1 ARABIC LETTER TCHEH WITH SMALL V: try adding arabic</li>
<li>U+08C2 ARABIC LETTER KEHEH WITH SMALL V: try adding arabic</li>
<li>U+08C3 ARABIC LETTER GHAIN WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+08C4 ARABIC LETTER AFRICAN QAF WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+08C5 ARABIC LETTER JEEM WITH THREE DOTS ABOVE: try adding arabic</li>
<li>U+08C6 ARABIC LETTER JEEM WITH THREE DOTS BELOW: try adding arabic</li>
<li>U+08C7 ARABIC LETTER LAM WITH SMALL ARABIC LETTER TAH ABOVE: try adding arabic</li>
<li>U+08E3 ARABIC TURNED DAMMA BELOW: try adding arabic</li>
<li>U+08E4 ARABIC CURLY FATHA: try adding arabic</li>
<li>U+08E5 ARABIC CURLY DAMMA: try adding arabic</li>
<li>U+08E6 ARABIC CURLY KASRA: try adding arabic</li>
<li>U+08E7 ARABIC CURLY FATHATAN: try adding arabic</li>
<li>U+08E8 ARABIC CURLY DAMMATAN: try adding arabic</li>
<li>U+08E9 ARABIC CURLY KASRATAN: try adding arabic</li>
<li>U+08EA ARABIC TONE ONE DOT ABOVE: try adding arabic</li>
<li>U+08EB ARABIC TONE TWO DOTS ABOVE: try adding arabic</li>
<li>U+08EC ARABIC TONE LOOP ABOVE: try adding arabic</li>
<li>U+08ED ARABIC TONE ONE DOT BELOW: try adding arabic</li>
<li>U+08EE ARABIC TONE TWO DOTS BELOW: try adding arabic</li>
<li>U+08EF ARABIC TONE LOOP BELOW: try adding arabic</li>
<li>U+08F0 ARABIC OPEN FATHATAN: try adding arabic</li>
<li>U+08F1 ARABIC OPEN DAMMATAN: try adding arabic</li>
<li>U+08F2 ARABIC OPEN KASRATAN: try adding arabic</li>
<li>U+08F3 ARABIC SMALL HIGH WAW: try adding arabic</li>
<li>U+08F4 ARABIC FATHA WITH RING: try adding arabic</li>
<li>U+08F5 ARABIC FATHA WITH DOT ABOVE: try adding arabic</li>
<li>U+08F6 ARABIC KASRA WITH DOT BELOW: try adding arabic</li>
<li>U+08F7 ARABIC LEFT ARROWHEAD ABOVE: try adding arabic</li>
<li>U+08F8 ARABIC RIGHT ARROWHEAD ABOVE: try adding arabic</li>
<li>U+08F9 ARABIC LEFT ARROWHEAD BELOW: try adding arabic</li>
<li>U+08FA ARABIC RIGHT ARROWHEAD BELOW: try adding arabic</li>
<li>U+08FB ARABIC DOUBLE RIGHT ARROWHEAD ABOVE: try adding arabic</li>
<li>U+08FC ARABIC DOUBLE RIGHT ARROWHEAD ABOVE WITH DOT: try adding arabic</li>
<li>U+08FD ARABIC RIGHT ARROWHEAD ABOVE WITH DOT: try adding arabic</li>
<li>U+08FE ARABIC DAMMA WITH DOT: try adding arabic</li>
<li>U+08FF ARABIC MARK SIDEWAYS NOON GHUNNA: try adding arabic</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tai-tham, mongolian, tagalog, malayalam, javanese, nko, buginese, masaram-gondi, kayah-li, tai-viet, kaithi, pahawh-hmong, lao, hebrew, brahmi, khudawadi, gunjala-gondi, modi, newa, new-tai-lue, bhaiksuki, saurashtra, sogdian, tibetan, buhid, hanifi-rohingya, takri, dogra, balinese, yi, zanabazar-square, arabic, thaana, gurmukhi, kharoshthi, avestan, tai-le, chakma, lepcha, mahajani, telugu, mandaic, khojki, sinhala, devanagari, duployan, siddham, grantha, sundanese, syriac, tirhuta, hatran, bengali, hanunoo, gujarati, rejang, syloti-nagri, thai, psalter-pahlavi, manichaean, limbu, oriya, tifinagh, warang-citi, khmer, tamil, myanmar, meetei-mayek, phags-pa, tagbanwa, batak, kannada, sharada, cham</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tai-tham, mongolian, tagalog, malayalam, javanese, nko, buginese, masaram-gondi, kayah-li, tai-viet, kaithi, pahawh-hmong, lao, hebrew, brahmi, khudawadi, gunjala-gondi, modi, newa, new-tai-lue, bhaiksuki, saurashtra, sogdian, tibetan, buhid, hanifi-rohingya, takri, dogra, balinese, old-hungarian, yi, zanabazar-square, arabic, thaana, gurmukhi, kharoshthi, avestan, tai-le, chakma, lepcha, mahajani, telugu, mandaic, khojki, sinhala, devanagari, duployan, siddham, grantha, sundanese, syriac, tirhuta, bengali, hanunoo, gujarati, rejang, syloti-nagri, thai, psalter-pahlavi, manichaean, limbu, oriya, tifinagh, warang-citi, khmer, tamil, myanmar, meetei-mayek, phags-pa, tagbanwa, batak, kannada, sharada, cham</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, arabic, syriac, thaana, phags-pa, hebrew</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, syriac, thaana, phags-pa, hebrew</li>
<li>U+2010 HYPHEN: try adding one of: kayah-li, lisu, sundanese, yi, sora-sompeng, arabic, kaithi, armenian, kharoshthi, hebrew, syloti-nagri, coptic, cham</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, arabic, yi</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: tagalog, javanese, buginese, gunjala-gondi, newa, new-tai-lue, bhaiksuki, buhid, takri, balinese, mende-kikakui, tai-le, adlam, canadian-aboriginal, sinhala, syriac, hanunoo, osage, rejang, psalter-pahlavi, phags-pa, batak, kannada, malayalam, masaram-gondi, hebrew, marchen, hanifi-rohingya, soyombo, bassa-vah, mandaic, duployan, siddham, armenian, gujarati, ahom, tifinagh, myanmar, tagbanwa, coptic, sharada, mahajani, tai-tham, mongolian, wancho, kaithi, pahawh-hmong, lao, yi, gurmukhi, kharoshthi, lepcha, old-permic, miao, telugu, khojki, sundanese, elbasan, tirhuta, bengali, thai, manichaean, warang-citi, tamil, cham, music, nko, kayah-li, tai-viet, brahmi, khudawadi, modi, saurashtra, sogdian, tibetan, dogra, zanabazar-square, thaana, chakma, symbols, devanagari, grantha, math, syloti-nagri, limbu, oriya, khmer, caucasian-albanian, meetei-mayek</li>
<li>U+FBB2 ARABIC SYMBOL DOT ABOVE: try adding arabic</li>
<li>U+FBB3 ARABIC SYMBOL DOT BELOW: try adding arabic</li>
<li>U+FBB4 ARABIC SYMBOL TWO DOTS ABOVE: try adding arabic</li>
<li>U+FBB5 ARABIC SYMBOL TWO DOTS BELOW: try adding arabic</li>
<li>U+FBB6 ARABIC SYMBOL THREE DOTS ABOVE: try adding arabic</li>
<li>U+FBB7 ARABIC SYMBOL THREE DOTS BELOW: try adding arabic</li>
<li>U+FBB8 ARABIC SYMBOL THREE DOTS POINTING DOWNWARDS ABOVE: try adding arabic</li>
<li>U+FBB9 ARABIC SYMBOL THREE DOTS POINTING DOWNWARDS BELOW: try adding arabic</li>
<li>U+FBBA ARABIC SYMBOL FOUR DOTS ABOVE: try adding arabic</li>
<li>U+FBBB ARABIC SYMBOL FOUR DOTS BELOW: try adding arabic</li>
<li>U+FBBC ARABIC SYMBOL DOUBLE VERTICAL BAR BELOW: try adding arabic</li>
<li>U+FBBD ARABIC SYMBOL TWO DOTS VERTICALLY ABOVE: try adding arabic</li>
<li>U+FBBE ARABIC SYMBOL TWO DOTS VERTICALLY BELOW: try adding arabic</li>
<li>U+FBBF ARABIC SYMBOL RING: try adding arabic</li>
<li>U+FBC0 ARABIC SYMBOL SMALL TAH ABOVE: try adding arabic</li>
<li>U+FBC1 ARABIC SYMBOL SMALL TAH BELOW: try adding arabic</li>
<li>U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko</li>
<li>U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko</li>
<li>U+FDF2 ARABIC LIGATURE ALLAH ISOLATED FORM: try adding one of: arabic, thaana</li>
<li>U+FDF4 ARABIC LIGATURE MOHAMMAD ISOLATED FORM: try adding arabic</li>
<li>U+FDFA ARABIC LIGATURE SALLALLAHOU ALAYHE WASALLAM: try adding arabic</li>
<li>U+FDFB ARABIC LIGATURE JALLAJALALOUHOU: try adding arabic</li>
<li>U+FDFC RIAL SIGN: try adding arabic</li>
<li>U+FDFD ARABIC LIGATURE BISMILLAH AR-RAHMAN AR-RAHEEM: try adding one of: arabic, thaana</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 7 | 95 | 8 | 136 | 0 | 
| 0% | 0% | 1% | 3% | 38% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
