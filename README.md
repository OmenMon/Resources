![OmenMon Logo](https://omenmon.github.io/assets/images/favicon.png)

# OmenMon Resources

This repository holds the non-_GPL3_ resources used for building [OmenMon](https://github.com/OmenMon/OmenMon). Please note that these items come with different licenses, which are nonetheless compatible with being bundled with the application.

For information about **OmenMon**, visit [https://omenmon.github.io/](https://omenmon.github.io/)

# Driver.sys.gz

_WinRing0_ driver binary from [OpenLibSys](https://openlibsys.org/manual/WhatIsWinRing0.html)
* Copyright © 2007-2010 OpenLibSys & Noriyuki Miyazaki
* Licensed under the terms of the [Modified BSD License](https://openlibsys.org/manual/License.html)

# IoMon.ttf

A variation of the [Iosevka](https://be5invis.github.io/Iosevka) typeface
  * Copyright © 2015-2023 [Renzhi Li](https://typeof.net/) (aka Belleve Invis)
  * Licensed under the [SIL Open Font License 1.1](https://scripts.sil.org/OFL)

Used to display some of the figures (numbers), including the temperature dynamic notification icon

Modifications for **OmenMon** include in particular:
  * Removal of unused glyphs, glyph variants and substitution tables to reduce size from 9,437 kB to 29 kB
  * Reduction of horizontal spacing between glyphs to allow for more information density
  * A customized glyph for **℃** _Degrees Celsius_ `U+2103`
  * Modified with [FontForge](https://fontforge.org/) 

The following special characters are included:

    ⏮⏪⏴⏫⏶⏸⏹⏺⭘⏻⏽⏯⏷⏬⏩⏵⏭
    ‹«<⋅·∘∙•÷:.⋄⬥⬦◇⬖⬗⬘⬙⁎*✳🞼🞷⁞⁝>»›
    ⁰¹²³⁴⁵⁶⁷⁸⁹⁺⁻°′″^℃% # @|/🞫×~=-+±_₀₁₂₃₄₅₆₇₈₉₊₋ 

As well as the following whitespace sizes: 
| _En_ | _Em_ | _3-Per-Em_ | _4-Per-Em_ | _6-Per-Em_ |
|:----:|:----:|:----------:|:----------:|:----------:|
| > <  | > <  | > <        | > <        | > <        |


# Icon*.ico, Keyboard.png, Logo.png

**OmenMon** logo artwork, icons, and keyboard-layout diagram.

* Copyright © 2023 [Piotr Szczepański](https://piotr.szczepanski.name)
* Licensed under the terms of the [CC BY-NC-ND 4.0](http://creativecommons.org/licenses/by-nc-nd/4.0/)
* Artwork designed in [Inkscape](https://inkscape.org/) and converted to the `.ico` format with [icoutils](https://www.nongnu.org/icoutils/)
