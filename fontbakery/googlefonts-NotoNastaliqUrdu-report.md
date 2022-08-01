## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoNastaliqUrdu/googlefonts/ttf', 'fonts/NotoNastaliqUrdu/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[11] NotoNastaliqUrdu-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1981, but got 1904 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 1518, but got 596 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: alef-ar.short

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni067A
	* uni0681
	* uni06C4
	* YehBarreeHamza
	* uni06C6
	* YehKashmiri
	* uni0778
	* YehBarree
	* uni0771
	* uni076C and 136 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- multiply

	- guillemetleft

	- divide

	- ArEightBelowAltNS

	- quoteright

	- nbspace

	- alef-ar.short

	- SmallMeem

	- guillemetright

	- minus 

	- And ellipsis
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=275.0,Y=1.0 (should be at baseline 0?)

	* exclam (U+0021): X=283.0,Y=1.0 (should be at baseline 0?)

	* parenright (U+0029): X=158.5,Y=-2.0 (should be at baseline 0?)

	* comma (U+002C): X=171.5,Y=1.5 (should be at baseline 0?)

	* comma (U+002C): X=269.5,Y=-1.0 (should be at baseline 0?)

	* period (U+002E): X=139.0,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=147.0,Y=1.0 (should be at baseline 0?)

	* two (U+0032): X=74.0,Y=-2.0 (should be at baseline 0?)

	* two (U+0032): X=74.0,Y=-2.0 (should be at baseline 0?)

	* eight (U+0038): X=284.0,Y=1.0 (should be at baseline 0?) 

	* And 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni08F3_NS (U+08F3): L<<12.0,893.0>--<-34.0,873.0>> -> L<<-34.0,873.0>--<-131.0,837.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* y (U+0079): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* yacute (U+00FD): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ycircumflex (U+0177): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ydieresis (U+00FF): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 

	* And ygrave (U+1EF3): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>> 

	* And sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] NotoNastaliqUrdu-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1981, but got 1904 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 1518, but got 596 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: alef-ar.short

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/nastaliq.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoNastaliqUrdu/googlefonts/ttf/NotoNastaliqUrdu-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/nastaliq.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">؃۱۹؂٨۵࣯ࣹݺ؀9٣</span> (Added by SIESTA)</li>


<pre>Expected: ThreeArabic.small=9@1167,271+0|nine.small=9@761,271+0|NumberSign.alt2=9+1977|uni077A=8+1409|uni08F9_NS=3@0,-221+0|uni08EF_NS=3+0|FiveFarsi.small=3@1309,310+0|EightArabic.small=3@903,310+0|Footnote.alt2=3+2045|NineArabic.small=0@1230,301+0|OneArabic.small=0@824,301+0|Safhah.alt2=0+2538</pre>



<pre>Got     : ThreeArabic.small=9@1167,271+0|nine.small=9@761,271+0|NumberSign.alt2=9+1977|Small2AboveNS=8@144,-15+0|YehBarreeSep=8+1409|uni08F9_NS=3@0,-221+0|uni08EF_NS=3+0|FiveFarsi.small=3@1309,310+0|EightArabic.small=3@903,310+0|Footnote.alt2=3+2045|NineArabic.small=0@1230,301+0|OneArabic.small=0@824,301+0|Safhah.alt2=0+2538</pre>



<pre>                                                                                       ^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7969 3500" transform="matrix(1 0 0 -1 0 0)">
<path d="M-100.0,-5.0L-119.0,-2.0Q-117.0,15.0 -116.0,34.5Q-115.0,54.0 -115.0,82.0Q-115.0,111.0 -117.5,148.0Q-120.0,185.0 -123.5,219.5Q-127.0,254.0 -132.0,275.0Q-134.0,286.0 -137.5,302.0Q-141.0,318.0 -141.0,323.0Q-141.0,334.0 -134.5,352.5Q-128.0,371.0 -110.0,414.0L-99.0,413.0Q-97.0,408.0 -94.0,397.0Q-91.0,386.0 -88.0,369.0Q-82.0,335.0 -46.0,335.0Q-20.0,335.0 -3.5,349.5Q13.0,364.0 26.0,413.0L46.0,411.0Q44.0,389.0 42.0,376.5Q40.0,364.0 37.0,350.0Q41.0,343.0 49.0,339.0Q57.0,335.0 73.0,335.0Q102.0,335.0 116.5,354.5Q131.0,374.0 142.0,414.0L160.0,412.0Q155.0,350.0 136.0,316.5Q117.0,283.0 93.0,270.0Q69.0,257.0 46.0,257.0Q20.0,257.0 -1.0,272.0Q-25.0,251.0 -63.0,251.0L-73.0,251.0Q-70.0,223.0 -70.0,199.0Q-70.0,148.0 -72.5,112.5Q-75.0,77.0 -81.5,49.5Q-88.0,22.0 -100.0,-5.0Z"  transform="translate(1167, 1367)"/>
<path d="M-32.0,-6.0Q-67.0,-6.0 -86.0,2.0Q-96.0,6.0 -106.5,12.5Q-117.0,19.0 -129.0,27.0L-110.0,51.0Q-105.0,50.0 -92.5,43.0Q-80.0,36.0 -71.0,34.0Q-54.0,30.0 -29.0,32.5Q-4.0,35.0 19.0,61.0Q40.0,85.0 51.0,119.0Q62.0,153.0 63.0,183.0Q35.0,152.0 -16.0,152.0Q-79.0,152.0 -114.5,185.5Q-150.0,219.0 -150.0,273.0Q-150.0,321.0 -127.5,352.5Q-105.0,384.0 -72.0,400.0Q-39.0,416.0 -6.0,416.0Q71.0,416.0 110.5,364.0Q150.0,312.0 150.0,221.0Q150.0,164.0 129.0,112.0Q108.0,60.0 67.5,27.0Q27.0,-6.0 -32.0,-6.0ZM-3.0,187.0Q19.0,187.0 39.0,201.0Q57.0,215.0 65.0,238.0Q64.0,309.0 49.5,347.0Q35.0,385.0 -3.0,385.0Q-37.0,385.0 -51.0,358.0Q-65.0,331.0 -65.0,278.0Q-65.0,230.0 -49.5,208.5Q-34.0,187.0 -3.0,187.0Z"  transform="translate(761, 1367)"/>
<path d="M580.0,-23.0Q495.0,-23.0 434.5,-21.0Q374.0,-19.0 331.5,-15.0Q289.0,-11.0 258.5,-6.5Q228.0,-2.0 201.0,4.0Q163.0,12.0 144.5,23.5Q126.0,35.0 120.5,49.5Q115.0,64.0 115.0,80.0Q115.0,94.0 117.0,102.5Q119.0,111.0 123.0,124.0L130.0,132.0Q171.0,123.0 243.0,116.5Q315.0,110.0 405.0,106.5Q495.0,103.0 589.0,103.0Q754.0,103.0 906.0,111.5Q1058.0,120.0 1188.0,135.5Q1318.0,151.0 1416.5,172.5Q1515.0,194.0 1572.0,221.0Q1598.0,233.0 1618.0,245.5Q1638.0,258.0 1653.0,273.0Q1670.0,290.0 1681.5,300.0Q1693.0,310.0 1700.0,317.0Q1707.0,343.0 1722.0,379.0Q1737.0,415.0 1754.0,447.0Q1789.0,512.0 1827.5,562.0Q1866.0,612.0 1892.0,635.0L1902.0,631.0Q1901.0,623.0 1893.5,601.0Q1886.0,579.0 1875.5,553.5Q1865.0,528.0 1856.0,508.5Q1847.0,489.0 1843.0,484.0Q1831.0,473.0 1815.0,455.5Q1799.0,438.0 1787.5,418.0Q1776.0,398.0 1776.0,378.0Q1776.0,358.0 1802.0,344.0Q1839.0,325.0 1854.0,313.5Q1869.0,302.0 1869.0,281.0Q1869.0,267.0 1860.5,245.0Q1852.0,223.0 1838.5,201.0Q1825.0,179.0 1807.5,164.5Q1790.0,150.0 1772.0,150.0Q1758.0,150.0 1731.0,164.0Q1712.0,175.0 1695.0,182.0Q1678.0,189.0 1663.0,189.0Q1641.0,189.0 1624.0,183.5Q1607.0,178.0 1582.0,164.0Q1502.0,120.0 1405.5,88.0Q1309.0,56.0 1203.5,34.5Q1098.0,13.0 990.0,0.5Q882.0,-12.0 777.5,-17.5Q673.0,-23.0 580.0,-23.0Z"  transform="translate(0, 1096)"/>
<path d="M5.0,465.0L-9.0,468.0Q-8.0,479.0 -7.0,489.5Q-6.0,500.0 -6.0,510.0Q-6.0,527.0 -8.0,553.5Q-10.0,580.0 -13.5,607.5Q-17.0,635.0 -22.0,654.0Q-20.0,660.0 -18.0,666.0Q-16.0,672.0 -11.0,685.0L-4.0,703.0L5.0,702.0Q7.0,696.0 8.5,690.0Q10.0,684.0 11.0,678.0Q16.0,658.0 46.0,658.0Q66.0,658.0 79.0,668.0Q92.0,678.0 101.0,703.0L117.0,701.0Q108.0,649.0 89.5,629.0Q71.0,609.0 36.0,609.0Q29.0,609.0 20.0,612.0L20.0,577.0Q20.0,546.0 19.0,527.0Q18.0,508.0 15.0,494.5Q12.0,481.0 5.0,465.0Z"  transform="translate(2121, 1081)"/>
<path d="M298.0,-46.0Q239.0,-46.0 196.0,-41.0Q153.0,-36.0 123.0,-29.0Q80.0,-17.0 59.5,0.0Q39.0,17.0 33.0,37.0Q27.0,57.0 27.0,76.0Q27.0,97.0 33.5,130.0Q40.0,163.0 53.0,187.0Q96.0,271.0 321.0,386.0Q377.0,415.0 413.0,439.0Q449.0,463.0 481.0,497.0L498.0,487.0Q459.0,407.0 406.5,366.0Q354.0,325.0 301.0,300.0Q221.0,262.0 176.0,238.0Q131.0,214.0 112.5,197.5Q94.0,181.0 94.0,164.0Q94.0,139.0 121.5,124.5Q149.0,110.0 213.0,102.0Q244.0,98.0 282.0,95.5Q320.0,93.0 364.0,93.0Q401.0,93.0 437.0,94.0Q473.0,95.0 518.5,98.0Q564.0,101.0 630.0,106.0Q696.0,111.0 793.0,119.0Q858.0,124.0 930.0,127.0Q1002.0,130.0 1082.0,130.0Q1153.0,130.0 1212.5,127.5Q1272.0,125.0 1320.0,120.0L1321.0,97.0Q1230.0,71.0 1106.0,46.5Q982.0,22.0 824.0,-1.0Q508.0,-46.0 298.0,-46.0Z"  transform="translate(1977, 1096)"/>
<path d="M62.0,-32.0L62.0,-39.0Q56.0,-44.0 40.0,-56.0Q24.0,-68.0 5.0,-82.0Q-14.0,-96.0 -30.5,-107.5Q-47.0,-119.0 -53.0,-123.0L-53.0,-126.0Q-18.0,-149.0 1.0,-162.0Q20.0,-175.0 33.0,-184.0Q46.0,-193.0 61.0,-206.0L60.0,-212.0Q43.0,-229.0 29.0,-233.0Q2.0,-211.0 -15.5,-197.5Q-33.0,-184.0 -50.5,-171.0Q-68.0,-158.0 -97.0,-139.0L-96.0,-123.0Q-51.0,-86.0 -24.0,-64.0Q3.0,-42.0 16.5,-30.0Q30.0,-18.0 37.0,-11.0L62.0,-32.0Z"  transform="translate(3386, 875)"/>
<path d="M106.0,-149.0Q90.0,-132.0 77.0,-120.0Q64.0,-108.0 56.0,-101.0Q29.0,-124.0 1.5,-137.5Q-26.0,-151.0 -57.0,-151.0Q-82.0,-151.0 -101.5,-134.0Q-121.0,-117.0 -121.0,-92.0Q-121.0,-69.0 -106.5,-52.0Q-92.0,-35.0 -70.5,-25.5Q-49.0,-16.0 -30.0,-16.0Q5.0,-16.0 41.0,-45.0Q49.0,-52.0 62.0,-65.0L114.0,-21.0L128.0,-35.0L77.0,-82.0Q91.0,-97.0 104.0,-112.0Q117.0,-127.0 123.0,-135.0L106.0,-149.0ZM-83.0,-81.0Q-83.0,-95.0 -70.0,-104.5Q-57.0,-114.0 -38.0,-114.0Q-21.0,-114.0 -2.0,-107.0Q17.0,-100.0 35.0,-87.0Q10.0,-67.0 -9.0,-58.5Q-28.0,-50.0 -44.0,-50.0Q-63.0,-50.0 -73.0,-60.0Q-83.0,-70.0 -83.0,-81.0Z"  transform="translate(3386, 1096)"/>
<path d="M-68.0,7.0Q-108.0,7.0 -123.0,33.0Q-138.0,59.0 -138.0,93.0Q-138.0,160.0 -108.5,221.5Q-79.0,283.0 -34.0,345.0L-34.0,349.0Q-34.0,354.0 -27.5,365.5Q-21.0,377.0 -11.5,389.5Q-2.0,402.0 6.0,410.0L15.0,409.0Q80.0,341.0 107.0,288.0Q134.0,235.0 134.0,187.0Q134.0,162.0 129.0,132.5Q124.0,103.0 113.0,76.5Q102.0,50.0 84.5,33.0Q67.0,16.0 43.0,16.0Q30.0,16.0 16.0,19.0Q2.0,22.0 -8.0,35.0Q-15.0,25.0 -29.5,16.0Q-44.0,7.0 -68.0,7.0ZM-56.0,90.0Q-41.0,90.0 -26.0,99.0Q-11.0,108.0 2.0,127.0L13.0,126.0Q25.0,96.0 56.0,96.0Q78.0,96.0 85.0,112.5Q92.0,129.0 92.0,143.0Q92.0,175.0 69.5,210.5Q47.0,246.0 24.0,271.0L-6.0,304.0Q-52.0,257.0 -73.5,213.0Q-95.0,169.0 -95.0,139.0Q-95.0,90.0 -56.0,90.0Z"  transform="translate(4695, 1406)"/>
<path d="M-137.0,-3.0Q-140.0,1.0 -143.0,11.0L-150.0,29.0Q-158.0,50.0 -158.0,57.0L-134.0,109.0Q-118.0,143.0 -89.0,209.0Q-60.0,275.0 -20.0,375.0Q-14.0,390.0 -8.5,400.0Q-3.0,410.0 0.0,414.0L16.0,414.0Q17.0,413.0 25.5,391.5Q34.0,370.0 46.0,338.5Q58.0,307.0 71.0,274.0Q84.0,241.0 93.5,216.5Q103.0,192.0 106.0,185.0Q124.0,145.0 132.5,124.0Q141.0,103.0 145.0,94.5Q149.0,86.0 151.0,81.0L151.0,77.0Q150.0,73.0 141.5,54.5Q133.0,36.0 123.5,18.5Q114.0,1.0 111.0,-3.0L101.0,-3.0Q92.0,13.0 79.5,43.0Q67.0,73.0 53.5,109.5Q40.0,146.0 27.0,182.5Q14.0,219.0 4.5,249.0Q-5.0,279.0 -9.0,295.0L-11.0,295.0Q-21.0,268.0 -31.5,240.5Q-42.0,213.0 -52.0,186.0Q-68.0,143.0 -88.5,91.5Q-109.0,40.0 -126.0,-3.0L-137.0,-3.0Z"  transform="translate(4289, 1406)"/>
<path d="M301.0,0.0Q213.0,0.0 172.5,27.0Q132.0,54.0 132.0,101.0Q132.0,122.0 141.5,153.5Q151.0,185.0 173.0,220.0Q195.0,255.0 231.0,284.0Q279.0,323.0 323.0,323.0Q378.0,323.0 403.0,287.5Q428.0,252.0 428.0,200.0Q428.0,152.0 411.0,104.0Q629.0,112.0 852.5,129.5Q1076.0,147.0 1305.0,172.0Q1534.0,198.0 1688.0,224.5Q1842.0,251.0 1921.0,279.0L1931.0,277.0Q1930.0,260.0 1922.5,236.5Q1915.0,213.0 1900.0,184.0Q1815.0,144.0 1641.0,111.5Q1467.0,79.0 1206.0,53.0Q945.0,27.0 718.5,13.5Q492.0,0.0 301.0,0.0ZM368.0,104.0L387.0,104.0L387.0,110.0Q387.0,162.0 371.0,189.5Q355.0,217.0 329.5,228.0Q304.0,239.0 275.0,239.0Q241.0,239.0 212.0,217.0Q183.0,195.0 183.0,163.0Q183.0,145.0 197.5,132.0Q212.0,119.0 252.0,111.5Q292.0,104.0 368.0,104.0Z"  transform="translate(3386, 1096)"/>
<path d="M62.0,-4.0L50.0,-3.0Q46.0,8.0 43.0,32.5Q40.0,57.0 37.5,87.5Q35.0,118.0 33.5,148.0Q32.0,178.0 32.0,199.0Q18.0,183.0 -0.5,177.5Q-19.0,172.0 -34.0,172.0Q-52.0,172.0 -71.5,178.5Q-91.0,185.0 -104.0,202.5Q-117.0,220.0 -117.0,252.0Q-117.0,286.0 -104.0,323.5Q-91.0,361.0 -66.5,387.5Q-42.0,414.0 -7.0,414.0Q22.0,414.0 38.5,397.5Q55.0,381.0 63.0,341.0Q71.0,301.0 76.0,230.0Q79.0,184.0 81.0,164.5Q83.0,145.0 85.0,131.0L92.0,78.0Q90.0,70.0 84.5,55.0Q79.0,40.0 62.0,-4.0ZM-19.0,249.0Q-2.0,249.0 9.5,251.0Q21.0,253.0 30.0,257.0Q30.0,339.0 -24.0,339.0Q-46.0,339.0 -60.5,322.0Q-75.0,305.0 -75.0,288.0Q-75.0,268.0 -56.0,257.0Q-40.0,249.0 -19.0,249.0Z"  transform="translate(6661, 1397)"/>
<path d="M2.0,-5.0L-18.0,-2.0Q-15.0,12.0 -14.0,31.5Q-13.0,51.0 -13.0,82.0Q-13.0,135.0 -17.5,180.5Q-22.0,226.0 -28.0,276.0Q-31.0,302.0 -33.0,313.5Q-35.0,325.0 -35.0,329.0Q-27.0,352.0 -18.0,375.5Q-9.0,399.0 -2.0,414.0L10.0,413.0Q13.0,402.0 17.0,375.0Q21.0,348.0 24.5,315.0Q28.0,282.0 30.0,250.5Q32.0,219.0 32.0,199.0Q32.0,146.0 29.5,111.5Q27.0,77.0 21.0,50.5Q15.0,24.0 2.0,-5.0Z"  transform="translate(6255, 1397)"/>
<path d="M877.0,-37.0Q631.0,-37.0 446.0,-16.0Q261.0,5.0 114.0,44.0L120.0,67.0Q202.0,64.0 281.5,62.5Q361.0,61.0 452.0,61.0Q512.0,61.0 558.0,61.5Q604.0,62.0 645.0,63.5Q686.0,65.0 730.5,67.0Q775.0,69.0 833.0,71.0Q1041.0,79.0 1200.0,93.0Q1359.0,107.0 1471.0,126.0Q1583.0,146.0 1667.0,167.0Q1751.0,188.0 1806.0,213.0Q1862.0,238.0 1895.0,252.0Q1928.0,266.0 1934.0,266.0Q1945.0,266.0 1951.0,263.5Q1957.0,261.0 1966.0,256.5Q1975.0,252.0 1994.0,244.0Q1999.0,249.0 2003.5,255.5Q2008.0,262.0 2015.0,270.0Q2034.0,294.0 2045.5,308.0Q2057.0,322.0 2067.0,334.0Q2077.0,346.0 2091.0,363.0Q2161.0,445.0 2222.0,481.5Q2283.0,518.0 2340.0,518.0Q2380.0,518.0 2397.5,497.5Q2415.0,477.0 2415.0,454.0Q2415.0,423.0 2403.0,389.5Q2391.0,356.0 2372.0,324.0Q2353.0,292.0 2332.5,265.0Q2312.0,238.0 2294.0,220.0Q2273.0,199.0 2238.5,174.5Q2204.0,150.0 2157.5,133.0Q2111.0,116.0 2053.0,116.0Q1983.0,116.0 1928.0,145.0Q1900.0,160.0 1886.5,166.0Q1873.0,172.0 1870.0,172.0Q1865.0,172.0 1853.0,166.5Q1841.0,161.0 1813.0,147.5Q1785.0,134.0 1730.0,110.0Q1666.0,82.0 1577.5,56.5Q1489.0,31.0 1377.0,8.0Q1155.0,-37.0 877.0,-37.0ZM2054.0,229.0Q2108.0,229.0 2157.0,240.0Q2206.0,251.0 2244.0,269.0Q2282.0,287.0 2304.0,307.5Q2326.0,328.0 2326.0,347.0Q2326.0,363.0 2314.5,372.0Q2303.0,381.0 2287.0,385.5Q2271.0,390.0 2257.0,390.0Q2234.0,390.0 2210.5,383.5Q2187.0,377.0 2163.0,361.0Q2135.0,343.0 2104.5,311.5Q2074.0,280.0 2037.0,231.0Q2041.0,230.0 2045.0,229.5Q2049.0,229.0 2054.0,229.0Z"  transform="translate(5431, 1096)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7969 3500" transform="matrix(1 0 0 -1 0 0)">
<path d="M-100.0,-5.0L-119.0,-2.0Q-117.0,15.0 -116.0,34.5Q-115.0,54.0 -115.0,82.0Q-115.0,111.0 -117.5,148.0Q-120.0,185.0 -123.5,219.5Q-127.0,254.0 -132.0,275.0Q-134.0,286.0 -137.5,302.0Q-141.0,318.0 -141.0,323.0Q-141.0,334.0 -134.5,352.5Q-128.0,371.0 -110.0,414.0L-99.0,413.0Q-97.0,408.0 -94.0,397.0Q-91.0,386.0 -88.0,369.0Q-82.0,335.0 -46.0,335.0Q-20.0,335.0 -3.5,349.5Q13.0,364.0 26.0,413.0L46.0,411.0Q44.0,389.0 42.0,376.5Q40.0,364.0 37.0,350.0Q41.0,343.0 49.0,339.0Q57.0,335.0 73.0,335.0Q102.0,335.0 116.5,354.5Q131.0,374.0 142.0,414.0L160.0,412.0Q155.0,350.0 136.0,316.5Q117.0,283.0 93.0,270.0Q69.0,257.0 46.0,257.0Q20.0,257.0 -1.0,272.0Q-25.0,251.0 -63.0,251.0L-73.0,251.0Q-70.0,223.0 -70.0,199.0Q-70.0,148.0 -72.5,112.5Q-75.0,77.0 -81.5,49.5Q-88.0,22.0 -100.0,-5.0Z"  transform="translate(1167, 1367)"/>
<path d="M-32.0,-6.0Q-67.0,-6.0 -86.0,2.0Q-96.0,6.0 -106.5,12.5Q-117.0,19.0 -129.0,27.0L-110.0,51.0Q-105.0,50.0 -92.5,43.0Q-80.0,36.0 -71.0,34.0Q-54.0,30.0 -29.0,32.5Q-4.0,35.0 19.0,61.0Q40.0,85.0 51.0,119.0Q62.0,153.0 63.0,183.0Q35.0,152.0 -16.0,152.0Q-79.0,152.0 -114.5,185.5Q-150.0,219.0 -150.0,273.0Q-150.0,321.0 -127.5,352.5Q-105.0,384.0 -72.0,400.0Q-39.0,416.0 -6.0,416.0Q71.0,416.0 110.5,364.0Q150.0,312.0 150.0,221.0Q150.0,164.0 129.0,112.0Q108.0,60.0 67.5,27.0Q27.0,-6.0 -32.0,-6.0ZM-3.0,187.0Q19.0,187.0 39.0,201.0Q57.0,215.0 65.0,238.0Q64.0,309.0 49.5,347.0Q35.0,385.0 -3.0,385.0Q-37.0,385.0 -51.0,358.0Q-65.0,331.0 -65.0,278.0Q-65.0,230.0 -49.5,208.5Q-34.0,187.0 -3.0,187.0Z"  transform="translate(761, 1367)"/>
<path d="M580.0,-23.0Q495.0,-23.0 434.5,-21.0Q374.0,-19.0 331.5,-15.0Q289.0,-11.0 258.5,-6.5Q228.0,-2.0 201.0,4.0Q163.0,12.0 144.5,23.5Q126.0,35.0 120.5,49.5Q115.0,64.0 115.0,80.0Q115.0,94.0 117.0,102.5Q119.0,111.0 123.0,124.0L130.0,132.0Q171.0,123.0 243.0,116.5Q315.0,110.0 405.0,106.5Q495.0,103.0 589.0,103.0Q754.0,103.0 906.0,111.5Q1058.0,120.0 1188.0,135.5Q1318.0,151.0 1416.5,172.5Q1515.0,194.0 1572.0,221.0Q1598.0,233.0 1618.0,245.5Q1638.0,258.0 1653.0,273.0Q1670.0,290.0 1681.5,300.0Q1693.0,310.0 1700.0,317.0Q1707.0,343.0 1722.0,379.0Q1737.0,415.0 1754.0,447.0Q1789.0,512.0 1827.5,562.0Q1866.0,612.0 1892.0,635.0L1902.0,631.0Q1901.0,623.0 1893.5,601.0Q1886.0,579.0 1875.5,553.5Q1865.0,528.0 1856.0,508.5Q1847.0,489.0 1843.0,484.0Q1831.0,473.0 1815.0,455.5Q1799.0,438.0 1787.5,418.0Q1776.0,398.0 1776.0,378.0Q1776.0,358.0 1802.0,344.0Q1839.0,325.0 1854.0,313.5Q1869.0,302.0 1869.0,281.0Q1869.0,267.0 1860.5,245.0Q1852.0,223.0 1838.5,201.0Q1825.0,179.0 1807.5,164.5Q1790.0,150.0 1772.0,150.0Q1758.0,150.0 1731.0,164.0Q1712.0,175.0 1695.0,182.0Q1678.0,189.0 1663.0,189.0Q1641.0,189.0 1624.0,183.5Q1607.0,178.0 1582.0,164.0Q1502.0,120.0 1405.5,88.0Q1309.0,56.0 1203.5,34.5Q1098.0,13.0 990.0,0.5Q882.0,-12.0 777.5,-17.5Q673.0,-23.0 580.0,-23.0Z"  transform="translate(0, 1096)"/>
<path d=""  transform="translate(1977, 1096)"/>
<path d="M62.0,-32.0L62.0,-39.0Q56.0,-44.0 40.0,-56.0Q24.0,-68.0 5.0,-82.0Q-14.0,-96.0 -30.5,-107.5Q-47.0,-119.0 -53.0,-123.0L-53.0,-126.0Q-18.0,-149.0 1.0,-162.0Q20.0,-175.0 33.0,-184.0Q46.0,-193.0 61.0,-206.0L60.0,-212.0Q43.0,-229.0 29.0,-233.0Q2.0,-211.0 -15.5,-197.5Q-33.0,-184.0 -50.5,-171.0Q-68.0,-158.0 -97.0,-139.0L-96.0,-123.0Q-51.0,-86.0 -24.0,-64.0Q3.0,-42.0 16.5,-30.0Q30.0,-18.0 37.0,-11.0L62.0,-32.0Z"  transform="translate(3386, 875)"/>
<path d="M106.0,-149.0Q90.0,-132.0 77.0,-120.0Q64.0,-108.0 56.0,-101.0Q29.0,-124.0 1.5,-137.5Q-26.0,-151.0 -57.0,-151.0Q-82.0,-151.0 -101.5,-134.0Q-121.0,-117.0 -121.0,-92.0Q-121.0,-69.0 -106.5,-52.0Q-92.0,-35.0 -70.5,-25.5Q-49.0,-16.0 -30.0,-16.0Q5.0,-16.0 41.0,-45.0Q49.0,-52.0 62.0,-65.0L114.0,-21.0L128.0,-35.0L77.0,-82.0Q91.0,-97.0 104.0,-112.0Q117.0,-127.0 123.0,-135.0L106.0,-149.0ZM-83.0,-81.0Q-83.0,-95.0 -70.0,-104.5Q-57.0,-114.0 -38.0,-114.0Q-21.0,-114.0 -2.0,-107.0Q17.0,-100.0 35.0,-87.0Q10.0,-67.0 -9.0,-58.5Q-28.0,-50.0 -44.0,-50.0Q-63.0,-50.0 -73.0,-60.0Q-83.0,-70.0 -83.0,-81.0Z"  transform="translate(3386, 1096)"/>
<path d="M-68.0,7.0Q-108.0,7.0 -123.0,33.0Q-138.0,59.0 -138.0,93.0Q-138.0,160.0 -108.5,221.5Q-79.0,283.0 -34.0,345.0L-34.0,349.0Q-34.0,354.0 -27.5,365.5Q-21.0,377.0 -11.5,389.5Q-2.0,402.0 6.0,410.0L15.0,409.0Q80.0,341.0 107.0,288.0Q134.0,235.0 134.0,187.0Q134.0,162.0 129.0,132.5Q124.0,103.0 113.0,76.5Q102.0,50.0 84.5,33.0Q67.0,16.0 43.0,16.0Q30.0,16.0 16.0,19.0Q2.0,22.0 -8.0,35.0Q-15.0,25.0 -29.5,16.0Q-44.0,7.0 -68.0,7.0ZM-56.0,90.0Q-41.0,90.0 -26.0,99.0Q-11.0,108.0 2.0,127.0L13.0,126.0Q25.0,96.0 56.0,96.0Q78.0,96.0 85.0,112.5Q92.0,129.0 92.0,143.0Q92.0,175.0 69.5,210.5Q47.0,246.0 24.0,271.0L-6.0,304.0Q-52.0,257.0 -73.5,213.0Q-95.0,169.0 -95.0,139.0Q-95.0,90.0 -56.0,90.0Z"  transform="translate(4695, 1406)"/>
<path d="M-137.0,-3.0Q-140.0,1.0 -143.0,11.0L-150.0,29.0Q-158.0,50.0 -158.0,57.0L-134.0,109.0Q-118.0,143.0 -89.0,209.0Q-60.0,275.0 -20.0,375.0Q-14.0,390.0 -8.5,400.0Q-3.0,410.0 0.0,414.0L16.0,414.0Q17.0,413.0 25.5,391.5Q34.0,370.0 46.0,338.5Q58.0,307.0 71.0,274.0Q84.0,241.0 93.5,216.5Q103.0,192.0 106.0,185.0Q124.0,145.0 132.5,124.0Q141.0,103.0 145.0,94.5Q149.0,86.0 151.0,81.0L151.0,77.0Q150.0,73.0 141.5,54.5Q133.0,36.0 123.5,18.5Q114.0,1.0 111.0,-3.0L101.0,-3.0Q92.0,13.0 79.5,43.0Q67.0,73.0 53.5,109.5Q40.0,146.0 27.0,182.5Q14.0,219.0 4.5,249.0Q-5.0,279.0 -9.0,295.0L-11.0,295.0Q-21.0,268.0 -31.5,240.5Q-42.0,213.0 -52.0,186.0Q-68.0,143.0 -88.5,91.5Q-109.0,40.0 -126.0,-3.0L-137.0,-3.0Z"  transform="translate(4289, 1406)"/>
<path d="M301.0,0.0Q213.0,0.0 172.5,27.0Q132.0,54.0 132.0,101.0Q132.0,122.0 141.5,153.5Q151.0,185.0 173.0,220.0Q195.0,255.0 231.0,284.0Q279.0,323.0 323.0,323.0Q378.0,323.0 403.0,287.5Q428.0,252.0 428.0,200.0Q428.0,152.0 411.0,104.0Q629.0,112.0 852.5,129.5Q1076.0,147.0 1305.0,172.0Q1534.0,198.0 1688.0,224.5Q1842.0,251.0 1921.0,279.0L1931.0,277.0Q1930.0,260.0 1922.5,236.5Q1915.0,213.0 1900.0,184.0Q1815.0,144.0 1641.0,111.5Q1467.0,79.0 1206.0,53.0Q945.0,27.0 718.5,13.5Q492.0,0.0 301.0,0.0ZM368.0,104.0L387.0,104.0L387.0,110.0Q387.0,162.0 371.0,189.5Q355.0,217.0 329.5,228.0Q304.0,239.0 275.0,239.0Q241.0,239.0 212.0,217.0Q183.0,195.0 183.0,163.0Q183.0,145.0 197.5,132.0Q212.0,119.0 252.0,111.5Q292.0,104.0 368.0,104.0Z"  transform="translate(3386, 1096)"/>
<path d="M62.0,-4.0L50.0,-3.0Q46.0,8.0 43.0,32.5Q40.0,57.0 37.5,87.5Q35.0,118.0 33.5,148.0Q32.0,178.0 32.0,199.0Q18.0,183.0 -0.5,177.5Q-19.0,172.0 -34.0,172.0Q-52.0,172.0 -71.5,178.5Q-91.0,185.0 -104.0,202.5Q-117.0,220.0 -117.0,252.0Q-117.0,286.0 -104.0,323.5Q-91.0,361.0 -66.5,387.5Q-42.0,414.0 -7.0,414.0Q22.0,414.0 38.5,397.5Q55.0,381.0 63.0,341.0Q71.0,301.0 76.0,230.0Q79.0,184.0 81.0,164.5Q83.0,145.0 85.0,131.0L92.0,78.0Q90.0,70.0 84.5,55.0Q79.0,40.0 62.0,-4.0ZM-19.0,249.0Q-2.0,249.0 9.5,251.0Q21.0,253.0 30.0,257.0Q30.0,339.0 -24.0,339.0Q-46.0,339.0 -60.5,322.0Q-75.0,305.0 -75.0,288.0Q-75.0,268.0 -56.0,257.0Q-40.0,249.0 -19.0,249.0Z"  transform="translate(6661, 1397)"/>
<path d="M2.0,-5.0L-18.0,-2.0Q-15.0,12.0 -14.0,31.5Q-13.0,51.0 -13.0,82.0Q-13.0,135.0 -17.5,180.5Q-22.0,226.0 -28.0,276.0Q-31.0,302.0 -33.0,313.5Q-35.0,325.0 -35.0,329.0Q-27.0,352.0 -18.0,375.5Q-9.0,399.0 -2.0,414.0L10.0,413.0Q13.0,402.0 17.0,375.0Q21.0,348.0 24.5,315.0Q28.0,282.0 30.0,250.5Q32.0,219.0 32.0,199.0Q32.0,146.0 29.5,111.5Q27.0,77.0 21.0,50.5Q15.0,24.0 2.0,-5.0Z"  transform="translate(6255, 1397)"/>
<path d="M877.0,-37.0Q631.0,-37.0 446.0,-16.0Q261.0,5.0 114.0,44.0L120.0,67.0Q202.0,64.0 281.5,62.5Q361.0,61.0 452.0,61.0Q512.0,61.0 558.0,61.5Q604.0,62.0 645.0,63.5Q686.0,65.0 730.5,67.0Q775.0,69.0 833.0,71.0Q1041.0,79.0 1200.0,93.0Q1359.0,107.0 1471.0,126.0Q1583.0,146.0 1667.0,167.0Q1751.0,188.0 1806.0,213.0Q1862.0,238.0 1895.0,252.0Q1928.0,266.0 1934.0,266.0Q1945.0,266.0 1951.0,263.5Q1957.0,261.0 1966.0,256.5Q1975.0,252.0 1994.0,244.0Q1999.0,249.0 2003.5,255.5Q2008.0,262.0 2015.0,270.0Q2034.0,294.0 2045.5,308.0Q2057.0,322.0 2067.0,334.0Q2077.0,346.0 2091.0,363.0Q2161.0,445.0 2222.0,481.5Q2283.0,518.0 2340.0,518.0Q2380.0,518.0 2397.5,497.5Q2415.0,477.0 2415.0,454.0Q2415.0,423.0 2403.0,389.5Q2391.0,356.0 2372.0,324.0Q2353.0,292.0 2332.5,265.0Q2312.0,238.0 2294.0,220.0Q2273.0,199.0 2238.5,174.5Q2204.0,150.0 2157.5,133.0Q2111.0,116.0 2053.0,116.0Q1983.0,116.0 1928.0,145.0Q1900.0,160.0 1886.5,166.0Q1873.0,172.0 1870.0,172.0Q1865.0,172.0 1853.0,166.5Q1841.0,161.0 1813.0,147.5Q1785.0,134.0 1730.0,110.0Q1666.0,82.0 1577.5,56.5Q1489.0,31.0 1377.0,8.0Q1155.0,-37.0 877.0,-37.0ZM2054.0,229.0Q2108.0,229.0 2157.0,240.0Q2206.0,251.0 2244.0,269.0Q2282.0,287.0 2304.0,307.5Q2326.0,328.0 2326.0,347.0Q2326.0,363.0 2314.5,372.0Q2303.0,381.0 2287.0,385.5Q2271.0,390.0 2257.0,390.0Q2234.0,390.0 2210.5,383.5Q2187.0,377.0 2163.0,361.0Q2135.0,343.0 2104.5,311.5Q2074.0,280.0 2037.0,231.0Q2041.0,230.0 2045.0,229.5Q2049.0,229.0 2054.0,229.0Z"  transform="translate(5431, 1096)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni067A
	* uni0681
	* uni06C4
	* YehBarreeHamza
	* uni06C6
	* YehKashmiri
	* uni0778
	* YehBarree
	* uni0771
	* uni076C and 135 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- multiply

	- guillemetleft

	- divide

	- ArEightBelowAltNS

	- quoteright

	- nbspace

	- alef-ar.short

	- SmallMeem

	- guillemetright

	- minus 

	- And ellipsis
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenright (U+0029): X=142.0,Y=715.5 (should be at cap-height 714?)

	* two (U+0032): X=104.0,Y=-1.0 (should be at baseline 0?)

	* two (U+0032): X=104.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=290.0,Y=1.0 (should be at baseline 0?)

	* six (U+0036): X=290.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

	* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?) 

	* And 57 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni08F3_NS (U+08F3): L<<18.0,897.0>--<-24.0,879.0>> -> L<<-24.0,879.0>--<-113.0,846.0>> 

	* And uni08F4_NS (U+08F4): L<<-57.0,950.0>--<-55.0,951.0>> -> L<<-55.0,951.0>--<36.0,1002.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[7] NotoNastaliqUrdu[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* 🔥 **FAIL** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1981, but got 1904 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 1518, but got 596 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 263. [code: invalid-default-instance-subfamily-nameid:263]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- multiply

	- divide

	- ArEightBelowAltNS

	- quoteright

	- uni0627.short

	- guillemotleft.1

	- SmallMeem

	- guillemotright.1

	- minus

	- ellipsis 

	- And uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenright (U+0029): X=142.0,Y=715.5 (should be at cap-height 714?)

	* two (U+0032): X=104.0,Y=-1.0 (should be at baseline 0?)

	* two (U+0032): X=104.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=290.0,Y=1.0 (should be at baseline 0?)

	* six (U+0036): X=290.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

	* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

	* f (U+0066): X=331.0,Y=712.5 (should be at cap-height 714?) 

	* And 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 9 | 17 | 328 | 20 | 298 | 0 |
| 0% | 1% | 3% | 49% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
