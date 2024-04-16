## FontBakery report

fontbakery version: 0.12.1



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansSyriacEastern[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansSyriacEastern/googlefonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[8] NotoSansSyriacEastern[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 572 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 573:
plus, minus, equal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- tildecomb

- uni0304.1

- uni0307.1

- uni0308.1

- uni030A.1

- uni0710.medi.2N
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ i̇ ĩ̠ i̠̇ i̠̊ ị̃ ị̇ ị̊ ĩ̤ i̤̇ i̤̊ ĩ̥ i̥̇ i̥̊ ĩ̦ i̦̇ i̦̊ ĩ̧ i̧̇ i̧̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Igbo (Latn, 27,823,640 speakers), Dutch (Latn, 31,709,104 speakers), Ekpeye (Latn, 226,000 speakers), Ebira (Latn, 2,200,000 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Avokaya (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Aghem (Latn, 38,843 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Kom (Latn, 360,685 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Kisi (Latn, 360,000 speakers), Bafut (Latn, 158,146 speakers), Nateni (Latn, 100,000 speakers), Mfumte (Latn, 79,000 speakers), Cicipu (Latn, 44,000 speakers), Nzakara (Latn, 50,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Dan (Latn, 1,099,244 speakers), Sar (Latn, 500,000 speakers), Navajo (Latn, 166,319 speakers).</p>
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
<li>U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>syriac</code></p>
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

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file</p>
 [code: empty-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Syriac Eastern ExtraLight' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 271 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Syriac Eastern ExtraLight' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 271 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Syriac Eastern SemiBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 275 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Syriac Eastern SemiBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 275 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Syriac Eastern ExtraBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 277 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Syriac Eastern ExtraBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 277 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* ⚠️ **WARN** <p>Name ID 6 'NotoSansSyriacEastern-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 7 | 97 | 7 | 136 | 0 | 
| 0% | 0% | 1% | 3% | 39% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
