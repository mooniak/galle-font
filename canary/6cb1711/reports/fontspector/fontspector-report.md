## FontSpector report

fontspector version: 1.9.0



## Checks with FATAL results

These must be addressed first.


<details><summary>[1] fonts/ttf/GalleCANARY-Regular.ttf</summary>
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




<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>


</div>
</details>


<details><summary>[14] fonts/ttf/GalleCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check base characters have non-zero advance width. (base_has_width)</summary>
    <div>








- ⚠️ **WARN** U+200C ZERO WIDTH NON-JOINER has non-zero advance width: 86 [code: non-zero-advance]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check that format 12 cmap subtables are correctly constituted. (cmap/format_12)</summary>
    <div>








- ⚠️ **WARN** The format 12 subtable did not contain all codepoints from the format 4 subtable:

* U+FFFF [code: missing-format-4]
  
  


- ⚠️ **WARN** The format 12 subtable did not contain all codepoints from the format 4 subtable:

* U+FFFF [code: missing-format-4]
  
  

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
* uni0D89 (U+0D89): found 1, expected one of: [2, 3, 4]
* uni0D93 (U+0D93): found 3, expected one of: [4, 5, 6]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0DA1 (U+0DA1): found 2, expected one of: [3, 4, 5] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 363 among a set of 4  math glyphs.
The following math glyphs have a different width, though:
width=424: less, greater [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* usignsinh.alt
* usignsinh.alt5
* uusignsinh.alt
* uusignsinh.alt5
* ddsinh.alt
* mbsinh.alt
* kunddaliya
* notdef
* yasignsinh.alt
* yasign_uusign_rephasinh
* yasign_usign_rephasinh
* sinBhAa.virama
* sinFAa.virama
* sinGAa.virama
* sinHAa.virama
* sinKAa.virama
* sinNAa.virama
* sinNnAa.virama
* sinNngAa.virama
* sinTAa.virama
* NULL
* mooniak [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* uni0DDD (U+0DDD)
* sinGAa.virama
* aasign_viramasinh
* sinFAa.virama
* sinHAa.virama
* sinBhAa.virama [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* ghIsinh: from (580.0, 464.0) to (580.0, 463.0) is colinear with segment from (580.0, 463.0) to (580.0, 462.0)
* nIsinh: from (505.0, 491.0) to (507.0, 491.0) is colinear with segment from (507.0, 491.0) to (508.0, 491.0)
* kIisinh: from (485.0, 493.0) to (485.0, 493.0) is colinear with segment from (485.0, 493.0) to (488.0, 493.0)
* nyjIisinh: from (430.0, 644.0) to (433.0, 644.0) is colinear with segment from (433.0, 644.0) to (436.0, 644.0)
* u111E7 (U+111E7): from (674.0, -10.0) to (672.0, -10.0) is colinear with segment from (672.0, -10.0) to (671.0, -10.0)
* u111E7 (U+111E7): from (672.0, -10.0) to (671.0, -10.0) is colinear with segment from (671.0, -10.0) to (595.0, -10.0)
* sIisinh: from (536.0, 425.0) to (536.0, 427.0) is colinear with segment from (536.0, 427.0) to (536.0, 429.0)
* sIisinh: from (536.0, 427.0) to (536.0, 429.0) is colinear with segment from (536.0, 429.0) to (536.0, 430.0)
* vU_rephasinh: from (244.0, 716.0) to (241.0, 716.0) is colinear with segment from (241.0, 716.0) to (240.0, 716.0)
* vUu_rephasinh: from (244.0, 716.0) to (241.0, 716.0) is colinear with segment from (241.0, 716.0) to (240.0, 716.0)
* rAaesinh: from (399.0, 882.0) to (399.0, 882.0) is colinear with segment from (399.0, 882.0) to (399.0, 882.0)
* ghRIsinh: from (580.0, 464.0) to (580.0, 463.0) is colinear with segment from (580.0, 463.0) to (580.0, 462.0)
* sRIisinh: from (552.0, 425.0) to (552.0, 427.0) is colinear with segment from (552.0, 427.0) to (552.0, 429.0)
* sRIisinh: from (552.0, 427.0) to (552.0, 429.0) is colinear with segment from (552.0, 429.0) to (552.0, 430.0)
* nga_rephasinh: from (223.0, 762.0) to (225.0, 762.0) is colinear with segment from (225.0, 762.0) to (226.0, 762.0)
* nga_rephasinh: from (225.0, 762.0) to (226.0, 762.0) is colinear with segment from (226.0, 762.0) to (227.0, 762.0)
* nndda_rephasinh: from (352.0, 762.0) to (353.0, 762.0) is colinear with segment from (353.0, 762.0) to (354.0, 762.0)
* nndda_rephasinh: from (353.0, 762.0) to (354.0, 762.0) is colinear with segment from (354.0, 762.0) to (354.0, 762.0)
* nndda_rephasinh: from (354.0, 762.0) to (354.0, 762.0) is colinear with segment from (354.0, 762.0) to (354.0, 762.0)
* va_rephasinh: from (244.0, 716.0) to (241.0, 716.0) is colinear with segment from (241.0, 716.0) to (240.0, 716.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D8A (U+0D8A): Quad(QuadBez { p0: (215.0, 561.0), p1: (168.0, 502.0), p2: (143.0, 464.0) })/Quad(QuadBez { p0: (143.0, 464.0), p1: (163.0, 486.0), p2: (200.0, 502.5) }) = 8.932981659616733 degrees
* uni0D9D (U+0D9D): Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* uni0DA9 (U+0DA9): Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* uni0DAA (U+0DAA): Quad(QuadBez { p0: (130.0, 342.5), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* uni0DC2 (U+0DC2): Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* bhU_rephasinh: Quad(QuadBez { p0: (123.5, 349.5), p1: (144.0, 366.0), p2: (158.0, 366.0) })/Quad(QuadBez { p0: (158.0, 366.0), p1: (149.0, 368.0), p2: (141.0, 368.0) }) = 12.528807709151522 degrees
* bhUu_rephasinh: Quad(QuadBez { p0: (123.5, 349.5), p1: (144.0, 366.0), p2: (158.0, 366.0) })/Quad(QuadBez { p0: (158.0, 366.0), p1: (149.0, 368.0), p2: (141.0, 368.0) }) = 12.528807709151522 degrees
* gUu_rephasinh: Quad(QuadBez { p0: (502.5, -0.5), p1: (490.0, -1.0), p2: (481.0, 0.0) })/Quad(QuadBez { p0: (481.0, 0.0), p1: (498.0, -5.0), p2: (515.5, -10.5) }) = 10.0493485881249 degrees
* uusignsinh.alt: Quad(QuadBez { p0: (-422.5, -124.0), p1: (-418.0, -124.0), p2: (-414.0, -125.0) })/Quad(QuadBez { p0: (-414.0, -125.0), p1: (-423.0, -122.0), p2: (-444.5, -111.5) }) = 4.398705354995591 degrees
* ghsinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* chsinh: Quad(QuadBez { p0: (487.5, 414.5), p1: (478.0, 404.0), p2: (458.0, 397.0) })/Quad(QuadBez { p0: (458.0, 397.0), p1: (473.0, 399.0), p2: (495.5, 395.5) }) = 11.695402850597292 degrees
* ddsinh: Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* ddhsinh: Quad(QuadBez { p0: (130.0, 342.5), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* nnsinh: Quad(QuadBez { p0: (717.5, 472.0), p1: (742.0, 448.0), p2: (747.0, 409.0) })/Quad(QuadBez { p0: (747.0, 409.0), p1: (751.0, 446.0), p2: (773.0, 468.5) }) = 13.475934628340466 degrees
* nnAasinh: Quad(QuadBez { p0: (916.0, 474.5), p1: (941.0, 450.0), p2: (945.0, 415.0) })/Quad(QuadBez { p0: (945.0, 415.0), p1: (948.0, 450.0), p2: (974.0, 473.0) }) = 11.418894205444719 degrees
* rsinh: Quad(QuadBez { p0: (178.5, 516.5), p1: (145.0, 486.0), p2: (129.0, 467.0) })/Quad(QuadBez { p0: (129.0, 467.0), p1: (161.0, 496.0), p2: (202.5, 514.5) }) = 7.714649137999015 degrees
* sssinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* ghIsinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* ddIsinh: Quad(QuadBez { p0: (107.0, 347.5), p1: (137.0, 366.0), p2: (158.0, 366.0) })/Quad(QuadBez { p0: (158.0, 366.0), p1: (149.0, 368.0), p2: (141.0, 368.0) }) = 12.528807709151492 degrees
* ddhIsinh: Quad(QuadBez { p0: (130.0, 343.0), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* nnIsinh: Quad(QuadBez { p0: (586.0, 343.5), p1: (587.0, 331.0), p2: (589.0, 317.0) })/Line(Line { p0: (589.0, 317.0), p1: (589.0, 318.0) }) = 8.130102354156005 degrees
* nnIsinh: Line(Line { p0: (589.0, 317.0), p1: (589.0, 318.0) })/Quad(QuadBez { p0: (589.0, 318.0), p1: (591.0, 305.0), p2: (593.0, 290.5) }) = 8.746162262555211 degrees
* rIsinh: Quad(QuadBez { p0: (178.5, 516.5), p1: (145.0, 486.0), p2: (129.0, 467.0) })/Quad(QuadBez { p0: (129.0, 467.0), p1: (161.0, 495.0), p2: (202.5, 514.0) }) = 8.713167288078143 degrees
* ssIsinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* ghIisinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* ddIisinh: Quad(QuadBez { p0: (534.5, 618.0), p1: (529.0, 603.0), p2: (515.0, 589.0) })/Quad(QuadBez { p0: (515.0, 589.0), p1: (570.0, 624.0), p2: (570.0, 692.0) }) = 12.528807709151492 degrees
* ddIisinh: Quad(QuadBez { p0: (107.0, 347.5), p1: (137.0, 366.0), p2: (158.0, 366.0) })/Quad(QuadBez { p0: (158.0, 366.0), p1: (149.0, 368.0), p2: (141.0, 368.0) }) = 12.528807709151492 degrees
* ddhIisinh: Quad(QuadBez { p0: (130.0, 343.0), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* nnIisinh: Quad(QuadBez { p0: (586.0, 343.5), p1: (587.0, 331.0), p2: (589.0, 317.0) })/Line(Line { p0: (589.0, 317.0), p1: (589.0, 318.0) }) = 8.130102354156005 degrees
* nnIisinh: Line(Line { p0: (589.0, 317.0), p1: (589.0, 318.0) })/Quad(QuadBez { p0: (589.0, 318.0), p1: (591.0, 305.0), p2: (593.0, 290.5) }) = 8.746162262555211 degrees
* nnddIisinh: Quad(QuadBez { p0: (674.5, 618.0), p1: (669.0, 603.0), p2: (655.0, 589.0) })/Quad(QuadBez { p0: (655.0, 589.0), p1: (710.0, 625.0), p2: (710.0, 692.0) }) = 11.79342968491043 degrees
* rIisinh: Quad(QuadBez { p0: (183.5, 516.5), p1: (150.0, 486.0), p2: (134.0, 467.0) })/Quad(QuadBez { p0: (134.0, 467.0), p1: (166.0, 495.0), p2: (207.5, 514.0) }) = 8.713167288078143 degrees
* u111ED (U+111ED): Quad(QuadBez { p0: (456.5, 434.0), p1: (402.0, 416.0), p2: (353.0, 378.0) })/Quad(QuadBez { p0: (353.0, 378.0), p1: (370.0, 386.0), p2: (397.0, 389.5) }) = 12.592819353141644 degrees
* uni0DEC (U+0DEC): Quad(QuadBez { p0: (608.5, 85.5), p1: (605.0, 75.0), p2: (601.0, 70.0) })/Quad(QuadBez { p0: (601.0, 70.0), p1: (610.0, 78.0), p2: (625.0, 96.5) }) = 9.706652409339679 degrees
* ssIisinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* ghUsinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* ghU_rephasinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* chU_rephasinh: Quad(QuadBez { p0: (540.0, 329.0), p1: (520.0, 366.0), p2: (485.0, 378.0) })/Quad(QuadBez { p0: (485.0, 378.0), p1: (502.0, 367.0), p2: (507.5, 350.5) }) = 13.980598506936664 degrees
* ddUsinh: Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* ddU_rephasinh: Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* ddhUsinh: Quad(QuadBez { p0: (130.0, 342.5), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* ddhU_rephasinh: Quad(QuadBez { p0: (130.0, 343.0), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* bhUsinh: Quad(QuadBez { p0: (123.5, 349.5), p1: (144.0, 366.0), p2: (158.0, 366.0) })/Quad(QuadBez { p0: (158.0, 366.0), p1: (149.0, 368.0), p2: (141.0, 368.0) }) = 12.528807709151522 degrees
* ssUsinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* ssU_rephasinh: Quad(QuadBez { p0: (554.5, 400.0), p1: (539.0, 386.0), p2: (519.0, 382.0) })/Quad(QuadBez { p0: (519.0, 382.0), p1: (565.0, 382.0), p2: (598.0, 359.5) }) = 11.309932474020195 degrees
* gUusinh: Quad(QuadBez { p0: (502.5, -0.5), p1: (490.0, -1.0), p2: (481.0, 0.0) })/Quad(QuadBez { p0: (481.0, 0.0), p1: (498.0, -5.0), p2: (515.5, -10.5) }) = 10.0493485881249 degrees
* ghUusinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* ghUu_rephasinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* nngUusinh: Quad(QuadBez { p0: (605.0, -0.5), p1: (594.0, 0.0), p2: (585.0, 1.0) })/Quad(QuadBez { p0: (585.0, 1.0), p1: (602.0, -4.0), p2: (619.5, -9.0) }) = 10.0493485881249 degrees
* chRsinh: Quad(QuadBez { p0: (487.5, 414.5), p1: (478.0, 404.0), p2: (458.0, 397.0) })/Quad(QuadBez { p0: (458.0, 397.0), p1: (473.0, 399.0), p2: (495.5, 395.5) }) = 11.695402850597292 degrees
* chUu_rephasinh: Quad(QuadBez { p0: (540.0, 329.0), p1: (520.0, 366.0), p2: (485.0, 378.0) })/Quad(QuadBez { p0: (485.0, 378.0), p1: (502.0, 367.0), p2: (507.5, 350.5) }) = 13.980598506936664 degrees
* ddUusinh: Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* ddUu_rephasinh: Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* ddhRsinh: Quad(QuadBez { p0: (130.0, 342.5), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* ddhRIsinh: Quad(QuadBez { p0: (130.0, 342.5), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* ddhRIisinh: Quad(QuadBez { p0: (130.0, 342.5), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* ddhRasinh: Quad(QuadBez { p0: (130.0, 342.5), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* ddhUusinh: Quad(QuadBez { p0: (130.0, 342.5), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* ddhUu_rephasinh: Quad(QuadBez { p0: (130.0, 343.0), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* bhUusinh: Quad(QuadBez { p0: (123.5, 349.5), p1: (144.0, 366.0), p2: (158.0, 366.0) })/Quad(QuadBez { p0: (158.0, 366.0), p1: (149.0, 368.0), p2: (141.0, 368.0) }) = 12.528807709151522 degrees
* ssUusinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* ssUu_rephasinh: Quad(QuadBez { p0: (554.5, 400.0), p1: (539.0, 386.0), p2: (519.0, 382.0) })/Quad(QuadBez { p0: (519.0, 382.0), p1: (565.0, 382.0), p2: (598.0, 359.5) }) = 11.309932474020195 degrees
* ghRasinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* ddRasinh: Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* ssRasinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* ghRsinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* ddRsinh: Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* ssRsinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* ghRIsinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* ddRIsinh: Quad(QuadBez { p0: (107.0, 347.5), p1: (137.0, 366.0), p2: (158.0, 366.0) })/Quad(QuadBez { p0: (158.0, 366.0), p1: (149.0, 368.0), p2: (141.0, 368.0) }) = 12.528807709151492 degrees
* ssRIsinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* ghRIisinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* ddRIisinh: Quad(QuadBez { p0: (534.5, 618.0), p1: (529.0, 603.0), p2: (515.0, 589.0) })/Quad(QuadBez { p0: (515.0, 589.0), p1: (570.0, 624.0), p2: (570.0, 692.0) }) = 12.528807709151492 degrees
* ddRIisinh: Quad(QuadBez { p0: (107.0, 347.5), p1: (137.0, 366.0), p2: (158.0, 366.0) })/Quad(QuadBez { p0: (158.0, 366.0), p1: (149.0, 368.0), p2: (141.0, 368.0) }) = 12.528807709151492 degrees
* ssRIisinh: Quad(QuadBez { p0: (511.5, 400.0), p1: (496.0, 386.0), p2: (476.0, 382.0) })/Quad(QuadBez { p0: (476.0, 382.0), p1: (522.0, 382.0), p2: (555.0, 359.5) }) = 11.309932474020195 degrees
* gha_rephasinh: Quad(QuadBez { p0: (107.0, 351.0), p1: (137.0, 372.0), p2: (158.0, 372.0) })/Quad(QuadBez { p0: (158.0, 372.0), p1: (149.0, 374.0), p2: (141.0, 374.0) }) = 12.528807709151492 degrees
* cha_rephasinh: Quad(QuadBez { p0: (540.0, 329.0), p1: (520.0, 366.0), p2: (485.0, 378.0) })/Quad(QuadBez { p0: (485.0, 378.0), p1: (502.0, 367.0), p2: (507.5, 350.5) }) = 13.980598506936664 degrees
* dda_rephasinh: Quad(QuadBez { p0: (107.0, 343.5), p1: (137.0, 362.0), p2: (158.0, 362.0) })/Quad(QuadBez { p0: (158.0, 362.0), p1: (149.0, 363.0), p2: (141.0, 363.0) }) = 6.340191745909908 degrees
* ddha_rephasinh: Quad(QuadBez { p0: (130.0, 343.0), p1: (153.0, 353.0), p2: (170.0, 353.0) })/Quad(QuadBez { p0: (170.0, 353.0), p1: (160.0, 354.0), p2: (150.5, 354.0) }) = 5.710593137499633 degrees
* nna_rephasinh: Quad(QuadBez { p0: (586.0, 342.5), p1: (587.0, 330.0), p2: (589.0, 313.0) })/Line(Line { p0: (589.0, 313.0), p1: (589.0, 315.0) }) = 6.70983680775695 degrees
* nna_rephasinh: Line(Line { p0: (589.0, 313.0), p1: (589.0, 315.0) })/Quad(QuadBez { p0: (589.0, 315.0), p1: (591.0, 301.0), p2: (592.5, 287.0) }) = 8.130102354156005 degrees
* ssa_rephasinh: Quad(QuadBez { p0: (554.5, 400.0), p1: (539.0, 386.0), p2: (519.0, 382.0) })/Quad(QuadBez { p0: (519.0, 382.0), p1: (565.0, 382.0), p2: (598.0, 359.5) }) = 11.309932474020195 degrees
* nyaa._csinh: Quad(QuadBez { p0: (518.5, 458.5), p1: (452.0, 431.0), p2: (385.0, 372.0) })/Quad(QuadBez { p0: (385.0, 372.0), p1: (431.0, 396.0), p2: (472.0, 396.0) }) = 13.814237683793984 degrees
* sinNnAa.virama: Quad(QuadBez { p0: (916.0, 474.5), p1: (941.0, 450.0), p2: (945.0, 415.0) })/Quad(QuadBez { p0: (945.0, 415.0), p1: (948.0, 444.0), p2: (966.5, 465.0) }) = 12.425942865427455 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* dhU_rephasinh: Line(Line { p0: (568.0, -310.0), p1: (570.0, 29.0) }) (angle: 89.66 degrees, expected: 90.00 degrees)
* dhU_rephasinh: Line(Line { p0: (615.0, 82.0), p1: (612.0, -350.0) }) (angle: -90.40 degrees, expected: -90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* rAaesinh: Line(Line { p0: (399.0, 882.0), p1: (399.0, 882.0) }) has the same coordinates as a previous segment.
* nndda_rephasinh: Line(Line { p0: (354.0, 762.0), p1: (354.0, 762.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>


</div>
</details>






### Summary

| 💥 ERROR | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 1 | 16 | 11 | 80 | 50 | 
| 1% | 10% | 7% | 51% | 32% | 



