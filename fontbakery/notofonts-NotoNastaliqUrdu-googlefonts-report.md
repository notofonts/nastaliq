## FontBakery report

fontbakery version: 0.12.8



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[2] NotoNastaliqUrdu[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>'smcp' or 'liga' lookups not found in GSUB table.</p>
 [code: missing-lookups]



</div>
</details>

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



<details><summary>[11] NotoNastaliqUrdu[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 180 font units wide, non-breaking space named (uni00A0) is 132 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that no collisions are found while shaping <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/collisions.json: 2 collisions found while shaping.</p>
<ul>
<li>
<p>twodotshorizontalbelowar/uni0650,twodotshorizontalbelowar/uni0650,uni0650/twodotshorizontalbelowar,uni0650/twodotshorizontalbelowar collision found in e.g. <span class='tf'>دِینا</span> <div><svg style="height:100px;margin:10px;"  viewBox="121 -460 875 1285"><path d="M264,0 Q190,0 155.5,56.5 Q121,113 121,223 Q121,306 124.5,385 Q128,464 133,530.5 Q138,597 144,645.5 Q150,694 155,716 Q159,733 164.5,750.5 Q170,768 176.5,787 Q183,806 191,825 L212,819 Q206,785 202,741.5 Q198,698 195,645 Q192,592 190.5,530 Q189,468 189,396 Q189,358 191.5,316.5 Q194,275 205.5,239 Q217,203 242.5,180.5 Q268,158 313,158 Q335,158 345.5,144 Q356,130 356,101 Q356,63 341,41 Q326,19 304.5,9.5 Q283,0 264,0 Z" fill="green"/> <path d="M406,421 Q392,435 378,448 Q364,461 350.5,473 Q337,485 323,495 L323,504 Q329,514 341,528.5 Q353,543 366.5,558 Q380,573 392,584.5 Q404,596 410,600 L419,600 Q465,571 481,551.5 Q497,532 497,515 Q497,498 476.5,474 Q456,450 414,421 L406,421 Z" fill="red"/> <path d="M263,0 Q249,0 239.5,6.5 Q230,13 225.5,26 Q221,39 221,57 Q221,94 235.5,116 Q250,138 271.5,148 Q293,158 313,158 Q343,158 367,169.5 Q391,181 409,204 L443,249 Q451,260 461.5,265.5 Q472,271 484,271 Q494,271 502,268.5 Q510,266 517,263 Q528,259 539,255 Q550,251 564,251 Q577,251 585,239 Q593,227 593,213 Q593,178 571,161.5 Q549,145 530,145 Q517,145 504.5,148 Q492,151 481,157 Q462,169 452,169 Q440,169 430,155.5 Q420,142 406,120 Q389,92 371,67 Q353,42 332,25 Q318,14 300.5,7 Q283,0 263,0 Z" fill="purple"/> <path d="M611,-460 Q597,-445 582.5,-432 Q568,-419 554.5,-407 Q541,-395 528,-385 L528,-376 Q534,-367 546,-352.5 Q558,-338 571.5,-322.5 Q585,-307 597,-295.5 Q609,-284 615,-281 L624,-281 Q649,-296 666,-309 Q683,-322 692,-336 Q710,-314 732,-290.5 Q754,-267 763,-262 L771,-262 Q811,-287 830.5,-306.5 Q850,-326 850,-346 Q850,-365 830,-388.5 Q810,-412 770,-441 L761,-441 Q744,-424 728,-409.5 Q712,-395 697,-383 Q683,-415 620,-460 L611,-460 Z" fill="yellow"/> <path d="M530,145 Q522,145 511.5,154 Q501,163 501,184 Q501,215 520.5,233 Q540,251 563,251 Q593,251 610,263 Q627,275 640,300 L661,296 Q648,241 628,207.5 Q608,174 583,159.5 Q558,145 530,145 Z" fill="green"/> <path d="M749,-364 L742,-359 Q746,-337 762,-319.5 Q778,-302 797,-290 Q816,-278 828,-271 Q863,-251 897,-232 Q931,-213 965,-194 Q973,-189 978.5,-186 Q984,-183 987,-181 L996,-186 Q988,-207 976,-223 Q964,-239 941,-252 L802,-328 Q778,-341 766.5,-349 Q755,-357 749,-364 Z" fill="purple"/> <path d="M673,-67 L671,-45 Q696,-32 728.5,-13 Q761,6 795,29 Q829,52 857.5,75 Q886,98 904,119 Q922,140 922,156 Q922,171 908.5,193 Q895,215 865,240.5 Q835,266 784,289 Q788,302 798.5,325 Q809,348 822,374.5 Q835,401 847.5,424 Q860,447 869,459 L880,459 Q908,442 933.5,415 Q959,388 975.5,351 Q992,314 992,266 Q992,229 982,187 Q972,145 953.5,105.5 Q935,66 911.5,36 Q888,6 861,-8 Q836,-21 788.5,-35.5 Q741,-50 673,-67 Z" fill="blue"/></svg> </div></p>
<pre><code>Got     : uni0627.fina=4+263|dotabovear=3@147,-411+0|uni066E.medi.alef=3+267|r150=3+0|twodotshorizontalbelowar=2@158,-262+0|uni066E.init.fbeh=2@0,145+156|nobari=2+0|uni0650=0@176,-180+0|uni062F.isol=0@30,0+330
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -1422 1001 3326" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g5" d="M264.0,0.0Q190.0,0.0 155.5,56.5Q121.0,113.0 121.0,223.0Q121.0,306.0 124.5,385.0Q128.0,464.0 133.0,530.5Q138.0,597.0 144.0,645.5Q150.0,694.0 155.0,716.0Q159.0,733.0 164.5,750.5Q170.0,768.0 176.5,787.0Q183.0,806.0 191.0,825.0L212.0,819.0Q206.0,785.0 202.0,741.5Q198.0,698.0 195.0,645.0Q192.0,592.0 190.5,530.0Q189.0,468.0 189.0,396.0Q189.0,358.0 191.5,316.5Q194.0,275.0 205.5,239.0Q217.0,203.0 242.5,180.5Q268.0,158.0 313.0,158.0Q335.0,158.0 345.5,144.0Q356.0,130.0 356.0,101.0Q356.0,63.0 341.0,41.0Q326.0,19.0 304.5,9.5Q283.0,0.0 264.0,0.0Z"/> <path id="g763" d="M-4.0,832.0Q-18.0,846.0 -32.0,859.0Q-46.0,872.0 -59.5,884.0Q-73.0,896.0 -87.0,906.0L-87.0,915.0Q-81.0,925.0 -69.0,939.5Q-57.0,954.0 -43.5,969.0Q-30.0,984.0 -18.0,995.5Q-6.0,1007.0 0.0,1011.0L9.0,1011.0Q55.0,982.0 71.0,962.5Q87.0,943.0 87.0,926.0Q87.0,909.0 66.5,885.0Q46.0,861.0 4.0,832.0L-4.0,832.0Z"/> <path id="g18" d="M0.0,0.0Q-14.0,0.0 -23.5,6.5Q-33.0,13.0 -37.5,26.0Q-42.0,39.0 -42.0,57.0Q-42.0,94.0 -27.5,116.0Q-13.0,138.0 8.5,148.0Q30.0,158.0 50.0,158.0Q80.0,158.0 104.0,169.5Q128.0,181.0 146.0,204.0L180.0,249.0Q188.0,260.0 198.5,265.5Q209.0,271.0 221.0,271.0Q231.0,271.0 239.0,268.5Q247.0,266.0 254.0,263.0Q265.0,259.0 276.0,255.0Q287.0,251.0 301.0,251.0Q314.0,251.0 322.0,239.0Q330.0,227.0 330.0,213.0Q330.0,178.0 308.0,161.5Q286.0,145.0 267.0,145.0Q254.0,145.0 241.5,148.0Q229.0,151.0 218.0,157.0Q199.0,169.0 189.0,169.0Q177.0,169.0 167.0,155.5Q157.0,142.0 143.0,120.0Q126.0,92.0 108.0,67.0Q90.0,42.0 69.0,25.0Q55.0,14.0 37.5,7.0Q20.0,0.0 0.0,0.0Z"/> <path id="g957" d=""/> <path id="g781" d="M-77.0,-198.0Q-91.0,-183.0 -105.5,-170.0Q-120.0,-157.0 -133.5,-145.0Q-147.0,-133.0 -160.0,-123.0L-160.0,-114.0Q-154.0,-105.0 -142.0,-90.5Q-130.0,-76.0 -116.5,-60.5Q-103.0,-45.0 -91.0,-33.5Q-79.0,-22.0 -73.0,-19.0L-64.0,-19.0Q-39.0,-34.0 -22.0,-47.0Q-5.0,-60.0 4.0,-74.0Q22.0,-52.0 44.0,-28.5Q66.0,-5.0 75.0,0.0L83.0,0.0Q123.0,-25.0 142.5,-44.5Q162.0,-64.0 162.0,-84.0Q162.0,-103.0 142.0,-126.5Q122.0,-150.0 82.0,-179.0L73.0,-179.0Q56.0,-162.0 40.0,-147.5Q24.0,-133.0 9.0,-121.0Q-5.0,-153.0 -68.0,-198.0L-77.0,-198.0Z"/> <path id="g42" d="M0.0,0.0Q-8.0,0.0 -18.5,9.0Q-29.0,18.0 -29.0,39.0Q-29.0,70.0 -9.5,88.0Q10.0,106.0 33.0,106.0Q63.0,106.0 80.0,118.0Q97.0,130.0 110.0,155.0L131.0,151.0Q118.0,96.0 98.0,62.5Q78.0,29.0 53.0,14.5Q28.0,0.0 0.0,0.0Z"/> <path id="g954" d=""/> <path id="g825" d="M-113.0,-184.0L-120.0,-179.0Q-116.0,-157.0 -100.0,-139.5Q-84.0,-122.0 -65.0,-110.0Q-46.0,-98.0 -34.0,-91.0Q1.0,-71.0 35.0,-52.0Q69.0,-33.0 103.0,-14.0Q111.0,-9.0 116.5,-6.0Q122.0,-3.0 125.0,-1.0L134.0,-6.0Q126.0,-27.0 114.0,-43.0Q102.0,-59.0 79.0,-72.0L-60.0,-148.0Q-84.0,-161.0 -95.5,-169.0Q-107.0,-177.0 -113.0,-184.0Z"/> <path id="g126" d="M-43.0,-67.0L-45.0,-45.0Q-20.0,-32.0 12.5,-13.0Q45.0,6.0 79.0,29.0Q113.0,52.0 141.5,75.0Q170.0,98.0 188.0,119.0Q206.0,140.0 206.0,156.0Q206.0,171.0 192.5,193.0Q179.0,215.0 149.0,240.5Q119.0,266.0 68.0,289.0Q72.0,302.0 82.5,325.0Q93.0,348.0 106.0,374.5Q119.0,401.0 131.5,424.0Q144.0,447.0 153.0,459.0L164.0,459.0Q192.0,442.0 217.5,415.0Q243.0,388.0 259.5,351.0Q276.0,314.0 276.0,266.0Q276.0,229.0 266.0,187.0Q256.0,145.0 237.5,105.5Q219.0,66.0 195.5,36.0Q172.0,6.0 145.0,-8.0Q120.0,-21.0 72.5,-35.5Q25.0,-50.0 -43.0,-67.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g5"/> </g> <g transform="translate(410,-411)"> <use href="#g763"/> </g> <g transform="translate(263,0)"> <use href="#g18"/> </g> <g transform="translate(530,0)"> <use href="#g957"/> </g> <g transform="translate(688,-262)"> <use href="#g781"/> </g> <g transform="translate(530,145)"> <use href="#g42"/> </g> <g transform="translate(686,0)"> <use href="#g954"/> </g> <g transform="translate(862,-180)"> <use href="#g825"/> </g> <g transform="translate(716,0)"> <use href="#g126"/> </g> </svg></p>
</li>
<li>
<p>threedotsdownbelowar/uni06D2.isol,threedotsdownbelowar/uni06D2.isol collision found in e.g. <span class='tf'>ےپیل</span> <div><svg style="height:100px;margin:10px;"  viewBox="28 -341 2564 1468"><path d="M280,-341 Q216,-341 168.5,-320 Q121,-299 90,-263.5 Q59,-228 43.5,-181.5 Q28,-135 28,-84 Q28,9 49,102.5 Q70,196 123,308 L151,297 Q123,229 109,171.5 Q95,114 95,63 Q95,-3 115,-47 Q135,-91 168.5,-116 Q202,-141 244,-151.5 Q286,-162 329,-162 Q378,-162 423.5,-150.5 Q469,-139 508.5,-117 Q548,-95 578,-64 Q621,-19 643,26.5 Q665,72 670,104 Q673,122 675.5,146 Q678,170 681,206.5 Q684,243 686,297 L707,802 Q710,866 714.5,910.5 Q719,955 727,989.5 Q735,1024 746,1056 Q757,1088 773,1127 L794,1119 Q791,1104 788,1082.5 Q785,1061 782,1031.5 Q779,1002 776.5,962.5 Q774,923 772.5,873 Q771,823 771,761 Q771,690 780.5,641 Q790,592 817.5,567 Q845,542 897,542 Q921,542 930.5,526 Q940,510 940,485 Q940,447 925,425 Q910,403 889,393.5 Q868,384 848,384 Q816,384 794,394 Q772,404 760,416 L757,334 Q756,302 747,236.5 Q738,171 714,86.5 Q690,2 643,-88 Q604,-162 550.5,-219.5 Q497,-277 429.5,-309 Q362,-341 280,-341 Z" fill="green"/> <path d="M892,15 Q878,30 863.5,43 Q849,56 835.5,68 Q822,80 809,90 L809,99 Q815,108 827,122.5 Q839,137 852.5,152.5 Q866,168 878,179.5 Q890,191 896,194 L905,194 Q930,179 947,166 Q964,153 973,139 Q991,161 1013,184.5 Q1035,208 1044,213 L1052,213 Q1092,188 1111.5,168.5 Q1131,149 1131,129 Q1131,110 1111,86.5 Q1091,63 1051,34 L1042,34 Q1025,51 1009,65.5 Q993,80 978,92 Q964,60 901,15 L892,15 Z" fill="red"/> <path d="M848,384 Q834,384 824.5,390.5 Q815,397 810.5,410 Q806,423 806,441 Q806,478 820.5,500 Q835,522 856.5,532 Q878,542 898,542 Q928,542 952,553.5 Q976,565 994,588 L1028,633 Q1036,644 1046.5,649.5 Q1057,655 1069,655 Q1079,655 1087,652.5 Q1095,650 1102,647 Q1113,643 1124,639 Q1135,635 1149,635 Q1162,635 1170,623 Q1178,611 1178,597 Q1178,562 1156,545.5 Q1134,529 1115,529 Q1102,529 1089.5,532 Q1077,535 1066,541 Q1047,553 1037,553 Q1025,553 1015,539.5 Q1005,526 991,504 Q974,476 956,451 Q938,426 917,409 Q903,398 885.5,391 Q868,384 848,384 Z" fill="purple"/> <path d="M1191,249 Q1177,264 1163,277 Q1149,290 1135.5,302 Q1122,314 1108,324 L1108,333 Q1115,343 1127,357.5 Q1139,372 1152.5,387 Q1166,402 1177.5,413.5 Q1189,425 1195,428 L1204,428 Q1229,412 1246,399 Q1263,386 1272,373 Q1284,388 1298,403.5 Q1312,419 1324.5,431.5 Q1337,444 1343,447 L1352,447 Q1391,422 1410.5,402.5 Q1430,383 1430,363 Q1430,344 1410,320.5 Q1390,297 1350,268 L1341,268 Q1330,280 1319,290 Q1308,300 1297.5,309 Q1287,318 1277,326 Q1263,294 1200,249 L1191,249 Z" fill="yellow"/> <path d="M1267,105 Q1259,115 1241.5,130.5 Q1224,146 1208,160 Q1192,174 1188,176 L1188,184 Q1203,204 1221,223 Q1239,242 1254,255.5 Q1269,269 1274,272 L1282,272 Q1318,247 1335.5,227.5 Q1353,208 1353,192 Q1353,177 1337,158 Q1321,139 1275,105 L1267,105 Z" fill="yellow"/> <path d="M1115,529 Q1107,529 1096.5,538 Q1086,547 1086,568 Q1086,599 1105.5,617 Q1125,635 1148,635 Q1178,635 1195,647 Q1212,659 1225,684 L1246,680 Q1233,625 1213,591.5 Q1193,558 1168,543.5 Q1143,529 1115,529 Z" fill="green"/> <path d="M1569,-46 Q1510,-46 1467,-41 Q1424,-36 1394,-29 Q1351,-17 1330.5,0 Q1310,17 1304,37 Q1298,57 1298,76 Q1298,90 1301,110 Q1304,130 1310,150.5 Q1316,171 1324,187 Q1367,271 1592,386 Q1648,415 1684,439 Q1720,463 1752,497 L1769,487 Q1730,407 1677.5,366 Q1625,325 1572,300 Q1492,262 1447,238 Q1402,214 1383.5,197.5 Q1365,181 1365,164 Q1365,139 1392.5,124.5 Q1420,110 1484,102 Q1505,100 1528.5,97.5 Q1552,95 1579,94 Q1606,93 1635,93 Q1672,93 1708,94 Q1744,95 1789.5,98 Q1835,101 1901,106 Q1967,111 2064,119 Q2129,124 2201,127 Q2273,130 2353,130 Q2424,130 2483.5,127.5 Q2543,125 2591,120 L2592,97 Q2501,71 2377,46.5 Q2253,22 2095,-1 Q1937,-23 1805.5,-34.5 Q1674,-46 1569,-46 Z" fill="purple"/></svg> </div></p>
<pre><code>Got     : uni0644.fina=3+848|twodotshorizontalbelowar=2@121,213+0|uni066E.medi.alef=2@0,384+267|r550=2+0|threedotsdownbelowar=1@155,447+0|uni066E.init.fbeh=1@0,529+156|nobari=1+0|uni06D2.isol=0+1409
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -1127 2707 3031" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g399" d="M280.0,-341.0Q216.0,-341.0 168.5,-320.0Q121.0,-299.0 90.0,-263.5Q59.0,-228.0 43.5,-181.5Q28.0,-135.0 28.0,-84.0Q28.0,9.0 49.0,102.5Q70.0,196.0 123.0,308.0L151.0,297.0Q123.0,229.0 109.0,171.5Q95.0,114.0 95.0,63.0Q95.0,-3.0 115.0,-47.0Q135.0,-91.0 168.5,-116.0Q202.0,-141.0 244.0,-151.5Q286.0,-162.0 329.0,-162.0Q378.0,-162.0 423.5,-150.5Q469.0,-139.0 508.5,-117.0Q548.0,-95.0 578.0,-64.0Q621.0,-19.0 643.0,26.5Q665.0,72.0 670.0,104.0Q673.0,122.0 675.5,146.0Q678.0,170.0 681.0,206.5Q684.0,243.0 686.0,297.0L707.0,802.0Q710.0,866.0 714.5,910.5Q719.0,955.0 727.0,989.5Q735.0,1024.0 746.0,1056.0Q757.0,1088.0 773.0,1127.0L794.0,1119.0Q791.0,1104.0 788.0,1082.5Q785.0,1061.0 782.0,1031.5Q779.0,1002.0 776.5,962.5Q774.0,923.0 772.5,873.0Q771.0,823.0 771.0,761.0Q771.0,690.0 780.5,641.0Q790.0,592.0 817.5,567.0Q845.0,542.0 897.0,542.0Q921.0,542.0 930.5,526.0Q940.0,510.0 940.0,485.0Q940.0,447.0 925.0,425.0Q910.0,403.0 889.0,393.5Q868.0,384.0 848.0,384.0Q816.0,384.0 794.0,394.0Q772.0,404.0 760.0,416.0L757.0,334.0Q756.0,302.0 747.0,236.5Q738.0,171.0 714.0,86.5Q690.0,2.0 643.0,-88.0Q604.0,-162.0 550.5,-219.5Q497.0,-277.0 429.5,-309.0Q362.0,-341.0 280.0,-341.0Z"/> <path id="g781" d="M-77.0,-198.0Q-91.0,-183.0 -105.5,-170.0Q-120.0,-157.0 -133.5,-145.0Q-147.0,-133.0 -160.0,-123.0L-160.0,-114.0Q-154.0,-105.0 -142.0,-90.5Q-130.0,-76.0 -116.5,-60.5Q-103.0,-45.0 -91.0,-33.5Q-79.0,-22.0 -73.0,-19.0L-64.0,-19.0Q-39.0,-34.0 -22.0,-47.0Q-5.0,-60.0 4.0,-74.0Q22.0,-52.0 44.0,-28.5Q66.0,-5.0 75.0,0.0L83.0,0.0Q123.0,-25.0 142.5,-44.5Q162.0,-64.0 162.0,-84.0Q162.0,-103.0 142.0,-126.5Q122.0,-150.0 82.0,-179.0L73.0,-179.0Q56.0,-162.0 40.0,-147.5Q24.0,-133.0 9.0,-121.0Q-5.0,-153.0 -68.0,-198.0L-77.0,-198.0Z"/> <path id="g18" d="M0.0,0.0Q-14.0,0.0 -23.5,6.5Q-33.0,13.0 -37.5,26.0Q-42.0,39.0 -42.0,57.0Q-42.0,94.0 -27.5,116.0Q-13.0,138.0 8.5,148.0Q30.0,158.0 50.0,158.0Q80.0,158.0 104.0,169.5Q128.0,181.0 146.0,204.0L180.0,249.0Q188.0,260.0 198.5,265.5Q209.0,271.0 221.0,271.0Q231.0,271.0 239.0,268.5Q247.0,266.0 254.0,263.0Q265.0,259.0 276.0,255.0Q287.0,251.0 301.0,251.0Q314.0,251.0 322.0,239.0Q330.0,227.0 330.0,213.0Q330.0,178.0 308.0,161.5Q286.0,145.0 267.0,145.0Q254.0,145.0 241.5,148.0Q229.0,151.0 218.0,157.0Q199.0,169.0 189.0,169.0Q177.0,169.0 167.0,155.5Q157.0,142.0 143.0,120.0Q126.0,92.0 108.0,67.0Q90.0,42.0 69.0,25.0Q55.0,14.0 37.5,7.0Q20.0,0.0 0.0,0.0Z"/> <path id="g966" d=""/> <path id="g788" d="M-79.0,-198.0Q-93.0,-183.0 -107.0,-170.0Q-121.0,-157.0 -134.5,-145.0Q-148.0,-133.0 -162.0,-123.0L-162.0,-114.0Q-155.0,-104.0 -143.0,-89.5Q-131.0,-75.0 -117.5,-60.0Q-104.0,-45.0 -92.5,-33.5Q-81.0,-22.0 -75.0,-19.0L-66.0,-19.0Q-41.0,-35.0 -24.0,-48.0Q-7.0,-61.0 2.0,-74.0Q14.0,-59.0 28.0,-43.5Q42.0,-28.0 54.5,-15.5Q67.0,-3.0 73.0,0.0L82.0,0.0Q121.0,-25.0 140.5,-44.5Q160.0,-64.0 160.0,-84.0Q160.0,-103.0 140.0,-126.5Q120.0,-150.0 80.0,-179.0L71.0,-179.0Q60.0,-167.0 49.0,-157.0Q38.0,-147.0 27.5,-138.0Q17.0,-129.0 7.0,-121.0Q-7.0,-153.0 -70.0,-198.0L-79.0,-198.0ZM-3.0,-342.0Q-11.0,-332.0 -28.5,-316.5Q-46.0,-301.0 -62.0,-287.0Q-78.0,-273.0 -82.0,-271.0L-82.0,-263.0Q-67.0,-243.0 -49.0,-224.0Q-31.0,-205.0 -16.0,-191.5Q-1.0,-178.0 4.0,-175.0L12.0,-175.0Q48.0,-200.0 65.5,-219.5Q83.0,-239.0 83.0,-255.0Q83.0,-270.0 67.0,-289.0Q51.0,-308.0 5.0,-342.0L-3.0,-342.0Z"/> <path id="g42" d="M0.0,0.0Q-8.0,0.0 -18.5,9.0Q-29.0,18.0 -29.0,39.0Q-29.0,70.0 -9.5,88.0Q10.0,106.0 33.0,106.0Q63.0,106.0 80.0,118.0Q97.0,130.0 110.0,155.0L131.0,151.0Q118.0,96.0 98.0,62.5Q78.0,29.0 53.0,14.5Q28.0,0.0 0.0,0.0Z"/> <path id="g954" d=""/> <path id="g596" d="M298.0,-46.0Q239.0,-46.0 196.0,-41.0Q153.0,-36.0 123.0,-29.0Q80.0,-17.0 59.5,0.0Q39.0,17.0 33.0,37.0Q27.0,57.0 27.0,76.0Q27.0,90.0 30.0,110.0Q33.0,130.0 39.0,150.5Q45.0,171.0 53.0,187.0Q96.0,271.0 321.0,386.0Q377.0,415.0 413.0,439.0Q449.0,463.0 481.0,497.0L498.0,487.0Q459.0,407.0 406.5,366.0Q354.0,325.0 301.0,300.0Q221.0,262.0 176.0,238.0Q131.0,214.0 112.5,197.5Q94.0,181.0 94.0,164.0Q94.0,139.0 121.5,124.5Q149.0,110.0 213.0,102.0Q234.0,100.0 257.5,97.5Q281.0,95.0 308.0,94.0Q335.0,93.0 364.0,93.0Q401.0,93.0 437.0,94.0Q473.0,95.0 518.5,98.0Q564.0,101.0 630.0,106.0Q696.0,111.0 793.0,119.0Q858.0,124.0 930.0,127.0Q1002.0,130.0 1082.0,130.0Q1153.0,130.0 1212.5,127.5Q1272.0,125.0 1320.0,120.0L1321.0,97.0Q1230.0,71.0 1106.0,46.5Q982.0,22.0 824.0,-1.0Q666.0,-23.0 534.5,-34.5Q403.0,-46.0 298.0,-46.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g399"/> </g> <g transform="translate(969,213)"> <use href="#g781"/> </g> <g transform="translate(848,384)"> <use href="#g18"/> </g> <g transform="translate(1115,0)"> <use href="#g966"/> </g> <g transform="translate(1270,447)"> <use href="#g788"/> </g> <g transform="translate(1115,529)"> <use href="#g42"/> </g> <g transform="translate(1271,0)"> <use href="#g954"/> </g> <g transform="translate(1271,0)"> <use href="#g596"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-collides]



</div>
</details>

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
<td align="left">Shaper didn't attach uni0670 to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0653 to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0654 to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0655 to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni064B to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni064C to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni064D to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni064E to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni064F to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0650 to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0651 to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni06540652 to TatweelNS</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0650 to uni0651</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni064D to uni0651</td>
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
<tr>
<td align="left">^</td>
<td align="left">.fina version of ARABIC LETTER NGOEH; both buffers returned twodotshorizontalabovear.kaf=1+0</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">.medi version of ARABIC LETTER NGOEH; both buffers returned space=1+0</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">.init version of ARABIC LETTER NGOEH; both buffers returned space=0+0</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">.fina version of ARABIC LETTER GUEH; both buffers returned twodotsverticalbelowar=1+0</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">.medi version of ARABIC LETTER GUEH; both buffers returned space=1+0</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">.init version of ARABIC LETTER GUEH; both buffers returned space=0+0</td>
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
<pre><code>- Contour 0 point 10 in glyph 'seven.encl' has a kink between location wght=400 and location wght=700

- Contour 0 point 29 in glyph 'uni0647.medi.jeem' has a kink between location wght=400 and location wght=700

- Contour 0 point 46 in glyph 'uni06D2.fina' has a kink between location wght=400 and location wght=700

- Contour 0 in glyph 'nine': becomes underweight between wght=400 and wght=700.

- Contour 0 point 31 in glyph 'nine' has a kink between location wght=400 and location wght=700

- Contour 0 in glyph 'uni0635.medi.sad': becomes underweight between wght=400 and wght=700.

- Contour 0 point 36 in glyph 'uni0635.medi.sad' has a kink between location wght=400 and location wght=700

- Contour 0 point 42 in glyph 'uni0635.medi.sad' has a kink between location wght=400 and location wght=700

- Contour 1 point 8 in glyph 'uni0635.isol' has a kink between location wght=400 and location wght=700

- Contour 0 point 40 in glyph 'uniFDFD' has a kink between location wght=400 and location wght=700

- Contour 0 point 31 in glyph 'uni0633.medi.seen' has a kink between location wght=400 and location wght=700

- Contour 0 in glyph 'uni0603': becomes underweight between wght=400 and wght=700.
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
greater, less</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- NullMk

- Smallmeemar

- _gaf.sarkash.inv2

- _gaf.sarkash.invshort2

- _gaf.sarkash.invshorter

- _gaf.sarkash.thin

- _graf.sarkash.thin

- uni0635.medi.yeh
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Yala (Latn, 200,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Fur (Latn, 1,230,163 speakers), South Central Banda (Latn, 244,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Navajo (Latn, 166,319 speakers), Dan (Latn, 1,099,244 speakers), Bete-Bendi (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nateni (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Zapotec (Latn, 490,000 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers), Mundani (Latn, 34,000 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Ma’di (Latn, 584,000 speakers), Southern Kisi (Latn, 360,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Cicipu (Latn, 44,000 speakers), Aghem (Latn, 38,843 speakers), Lugbara (Latn, 2,200,000 speakers).</p>
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
<li>U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, tifinagh, coptic, canadian-aboriginal, malayalam, tai-le, math</li>
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
<li>U+060C ARABIC COMMA: try adding one of: thaana, nko, syriac, hanifi-rohingya, yezidi, arabic</li>
<li>U+060D ARABIC DATE SEPARATOR: try adding arabic</li>
<li>U+060E ARABIC POETIC VERSE SIGN: try adding arabic</li>
<li>U+060F ARABIC SIGN MISRA: try adding arabic</li>
<li>U+0610 ARABIC SIGN SALLALLAHOU ALAYHE WASSALLAM: try adding arabic</li>
<li>U+0611 ARABIC SIGN ALAYHE ASSALLAM: try adding arabic</li>
<li>U+0612 ARABIC SIGN RAHMATULLAH ALAYHE: try adding arabic</li>
<li>U+0613 ARABIC SIGN RADI ALLAHOU ANHU: try adding arabic</li>
<li>U+0614 ARABIC SIGN TAKHALLUS: try adding arabic</li>
<li>U+0615 ARABIC SMALL HIGH TAH: try adding arabic</li>
<li>U+061B ARABIC SEMICOLON: try adding one of: thaana, nko, syriac, hanifi-rohingya, yezidi, arabic</li>
<li>U+061C ARABIC LETTER MARK: try adding one of: thaana, arabic, syriac</li>
<li>U+061E ARABIC TRIPLE DOT PUNCTUATION MARK: try adding arabic</li>
<li>U+061F ARABIC QUESTION MARK: try adding one of: thaana, nko, syriac, hanifi-rohingya, yezidi, adlam, arabic</li>
<li>U+0620 ARABIC LETTER KASHMIRI YEH: try adding arabic</li>
<li>U+0621 ARABIC LETTER HAMZA: try adding one of: arabic, syriac</li>
<li>U+0622 ARABIC LETTER ALEF WITH MADDA ABOVE: try adding arabic</li>
<li>U+0623 ARABIC LETTER ALEF WITH HAMZA ABOVE: try adding arabic</li>
<li>U+0624 ARABIC LETTER WAW WITH HAMZA ABOVE: try adding arabic</li>
<li>U+0625 ARABIC LETTER ALEF WITH HAMZA BELOW: try adding arabic</li>
<li>U+0626 ARABIC LETTER YEH WITH HAMZA ABOVE: try adding arabic</li>
<li>U+0627 ARABIC LETTER ALEF: try adding one of: arabic, indic-siyaq-numbers</li>
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
<li>U+0640 ARABIC TATWEEL: try adding one of: mandaic, syriac, old-uyghur, hanifi-rohingya, manichaean, psalter-pahlavi, sogdian, adlam, arabic</li>
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
<li>U+0660 ARABIC-INDIC DIGIT ZERO: try adding one of: thaana, syriac, hanifi-rohingya, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0661 ARABIC-INDIC DIGIT ONE: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0662 ARABIC-INDIC DIGIT TWO: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0663 ARABIC-INDIC DIGIT THREE: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0664 ARABIC-INDIC DIGIT FOUR: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0665 ARABIC-INDIC DIGIT FIVE: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0666 ARABIC-INDIC DIGIT SIX: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0667 ARABIC-INDIC DIGIT SEVEN: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0668 ARABIC-INDIC DIGIT EIGHT: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+0669 ARABIC-INDIC DIGIT NINE: try adding one of: thaana, syriac, yezidi, indic-siyaq-numbers, arabic</li>
<li>U+066A ARABIC PERCENT SIGN: try adding one of: thaana, arabic, nko, syriac</li>
<li>U+066B ARABIC DECIMAL SEPARATOR: try adding one of: thaana, arabic, syriac</li>
<li>U+066C ARABIC THOUSANDS SEPARATOR: try adding one of: thaana, arabic, syriac</li>
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
<li>U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi</li>
<li>U+06D5 ARABIC LETTER AE: try adding arabic</li>
<li>U+06DD ARABIC END OF AYAH: try adding arabic</li>
<li>U+06DE ARABIC START OF RUB EL HIZB: try adding arabic</li>
<li>U+06E0 ARABIC SMALL HIGH UPRIGHT RECTANGULAR ZERO: try adding arabic</li>
<li>U+06E1 ARABIC SMALL HIGH DOTLESS HEAD OF KHAH: try adding arabic</li>
<li>U+06E9 ARABIC PLACE OF SAJDAH: try adding arabic</li>
<li>U+06EE ARABIC LETTER DAL WITH INVERTED V: try adding arabic</li>
<li>U+06EF ARABIC LETTER REH WITH INVERTED V: try adding arabic</li>
<li>U+06F0 EXTENDED ARABIC-INDIC DIGIT ZERO: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F1 EXTENDED ARABIC-INDIC DIGIT ONE: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F2 EXTENDED ARABIC-INDIC DIGIT TWO: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F3 EXTENDED ARABIC-INDIC DIGIT THREE: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F4 EXTENDED ARABIC-INDIC DIGIT FOUR: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F5 EXTENDED ARABIC-INDIC DIGIT FIVE: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F6 EXTENDED ARABIC-INDIC DIGIT SIX: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F7 EXTENDED ARABIC-INDIC DIGIT SEVEN: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F8 EXTENDED ARABIC-INDIC DIGIT EIGHT: try adding one of: arabic, indic-siyaq-numbers</li>
<li>U+06F9 EXTENDED ARABIC-INDIC DIGIT NINE: try adding one of: arabic, indic-siyaq-numbers</li>
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
<li>U+08C8 ARABIC LETTER GRAF: try adding arabic</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sharada, tagbanwa, myanmar, kayah-li, lao, lepcha, sogdian, tamil, mongolian, sinhala, balinese, dogra, brahmi, hebrew, bengali, thaana, khudawadi, newa, pahawh-hmong, thai, tifinagh, batak, yi, kannada, modi, tibetan, tai-le, psalter-pahlavi, gurmukhi, kaithi, mandaic, sundanese, telugu, kharoshthi, avestan, tagalog, hatran, nko, hanunoo, oriya, phags-pa, syloti-nagri, chakma, cham, takri, warang-citi, gujarati, saurashtra, malayalam, meetei-mayek, tai-viet, devanagari, rejang, buginese, tai-tham, bhaiksuki, masaram-gondi, syriac, tirhuta, zanabazar-square, buhid, hanifi-rohingya, javanese, manichaean, khmer, new-tai-lue, gunjala-gondi, limbu, siddham, arabic, grantha, khojki, duployan, mahajani</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sharada, tagbanwa, myanmar, kayah-li, lao, lepcha, sogdian, tamil, mongolian, sinhala, balinese, dogra, brahmi, hebrew, bengali, thaana, khudawadi, newa, pahawh-hmong, thai, tifinagh, batak, yi, kannada, modi, tibetan, tai-le, old-hungarian, psalter-pahlavi, gurmukhi, kaithi, mandaic, sundanese, telugu, kharoshthi, avestan, tagalog, nko, hanunoo, oriya, phags-pa, syloti-nagri, chakma, cham, takri, warang-citi, gujarati, saurashtra, malayalam, meetei-mayek, tai-viet, devanagari, rejang, buginese, tai-tham, bhaiksuki, masaram-gondi, syriac, tirhuta, zanabazar-square, buhid, hanifi-rohingya, javanese, manichaean, khmer, new-tai-lue, gunjala-gondi, limbu, siddham, arabic, grantha, khojki, duployan, mahajani</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: thaana, hebrew, nko, syriac, phags-pa, arabic</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, hebrew, nko, syriac, phags-pa</li>
<li>U+2010 HYPHEN: try adding one of: hebrew, kayah-li, yi, sora-sompeng, coptic, syloti-nagri, cham, armenian, kaithi, arabic, sundanese, lisu, kharoshthi</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: arabic, syloti-nagri, yi</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: tagbanwa, ahom, osage, sinhala, thaana, old-permic, newa, kannada, gurmukhi, sundanese, symbols, telugu, kharoshthi, cham, meetei-mayek, rejang, javanese, khmer, grantha, duployan, mende-kikakui, sogdian, dogra, brahmi, khudawadi, pahawh-hmong, tifinagh, batak, coptic, modi, warang-citi, gujarati, saurashtra, adlam, soyombo, tai-tham, bhaiksuki, syriac, siddham, malayalam, tai-le, mahajani, myanmar, canadian-aboriginal, lao, lepcha, wancho, hebrew, yi, psalter-pahlavi, tagalog, hanunoo, syloti-nagri, chakma, takri, caucasian-albanian, tai-viet, devanagari, buginese, limbu, khojki, sharada, kayah-li, tamil, mongolian, balinese, thai, bengali, bassa-vah, marchen, tibetan, armenian, kaithi, mandaic, music, nko, oriya, phags-pa, masaram-gondi, tirhuta, zanabazar-square, buhid, hanifi-rohingya, miao, manichaean, new-tai-lue, gunjala-gondi, elbasan, math</li>
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
<li>U+FDF2 ARABIC LIGATURE ALLAH ISOLATED FORM: try adding one of: thaana, arabic</li>
<li>U+FDF4 ARABIC LIGATURE MOHAMMAD ISOLATED FORM: try adding arabic</li>
<li>U+FDFA ARABIC LIGATURE SALLALLAHOU ALAYHE WASALLAM: try adding arabic</li>
<li>U+FDFB ARABIC LIGATURE JALLAJALALOUHOU: try adding arabic</li>
<li>U+FDFC RIAL SIGN: try adding arabic</li>
<li>U+FDFD ARABIC LIGATURE BISMILLAH AR-RAHMAN AR-RAHEEM: try adding one of: thaana, arabic</li>
<li>U+FEAE ARABIC LETTER REH FINAL FORM: try adding arabic</li>
<li>U+FEEE ARABIC LETTER WAW FINAL FORM: try adding arabic</li>
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
| 0 | 0 | 5 | 8 | 96 | 8 | 134 | 0 | 
| 0% | 0% | 2% | 3% | 38% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
