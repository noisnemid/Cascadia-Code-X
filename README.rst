============================================================
Cascadia-Code-X
============================================================

This is a very special modification version to Cascadia Code Font.

The main mod part is the Glyphs' aspect ratio changed to w:h = 1200:2400 = 1:2 to fit CJK fonts' alignment in editors.

The second mod part is turning off the ligature feature.

Version number = 2.0
============================================================

Change the original Cascadia Code font's aspect ratio from 2048:1200 to 2400:1200, in order to collaborate perfect with any CJK fonts which often have a 1:1 aspect ratio.

A little side-effect: Font weight is slightly lighter compared to the original font.

修改原版 Cascadia Code 字体高宽比，从 2048:1200 修改为 2400:1200，从而使之可与任意高宽比为1:1的包含中文在内的类似CJK字符集的字体完美配合。

一点副作用是与原字体相比，字重呈现略微降低。

Software: Fontforge.

Additional Changes
============================================================

#.  A tiny modification to glyph '1' to make it more distinguishable from 'l'(small letter of L) when the digital '1' appears alone;
#.  Lengthened glyph(grave,u+0060, `````)
#.  Clear all ligature glyphs and relevant sub-lookup information because this feature is hard to turn off in some terminals while the ligature feature makes things messed up in some special scenarios. This makes the font file size very small.

