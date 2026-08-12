---
title: "System::Drawing::Color klass"
linktitle: "Färg"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Color klass. Representerar en färg. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen System::SmartPtr för att hantera objekt av denna typ i C++."
type: docs
weight: 500
url: /sv/cpp/system.drawing/color/
---
## Color class


Representerar en färg. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](../../system/smartptr/) för att hantera objekt av denna typ.

```cpp
class Color
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Color](./color/)() | Skapar en "tom" instans av klassen [Color](./) som inte representerar någon färg. |
| [Equals](./equals/)(const Color\&) const | Avgör om de aktuella och de angivna [Color](./)-objekten representerar samma färg. |
| static [FromArgb](./fromargb/)(int) | Skapar en instans av klassen [Color](./) som representerar den angivna färgen. |
| static [FromArgb](./fromargb/)(int, int, int, int) | Skapar en instans av klassen [Color](./) som representerar den angivna färgen. |
| static [FromArgb](./fromargb/)(int, int, int) | Skapar en instans av klassen [Color](./) som representerar den angivna färgen med alfakomponenten satt till 0xFF. |
| static [FromArgb](./fromargb/)(int, Color) | Skapar en instans av klassen [Color](./) som representerar den angivna färgen. |
| static [FromKnownColor](./fromknowncolor/)(KnownColor) | Skapar en instans av klassen [Color](./) som representerar den angivna fördefinierade färgen. |
| static [FromName](./fromname/)(const String\&) | Skapar en instans av klassen [Color](./) som representerar en färg med det angivna namnet. |
| [get_A](./get_a/)() const | Returnerar värdet för alfakomponenten i färgen som representeras av det aktuella objektet. |
| static [get_AliceBlue](./get_aliceblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF0F8FF. |
| static [get_AntiqueWhite](./get_antiquewhite/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFAEBD7. |
| static [get_Aqua](./get_aqua/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF00FFFF. |
| static [get_Aquamarine](./get_aquamarine/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF7FFFD4. |
| static [get_Azure](./get_azure/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF0FFFF. |
| [get_B](./get_b/)() const | Returnerar värdet för den blå komponenten i färgen som representeras av det aktuella objektet. |
| static [get_Beige](./get_beige/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF5F5DC. |
| static [get_Bisque](./get_bisque/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFE4C4. |
| static [get_Black](./get_black/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF000000. |
| static [get_BlanchedAlmond](./get_blanchedalmond/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFEBCD. |
| static [get_Blue](./get_blue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF0000FF. |
| static [get_BlueViolet](./get_blueviolet/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF8A2BE2. |
| static [get_Brown](./get_brown/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFA52A2A. |
| static [get_BurlyWood](./get_burlywood/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFDEB887. |
| static [get_CadetBlue](./get_cadetblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF5F9EA0. |
| static [get_Chartreuse](./get_chartreuse/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF7FFF00. |
| static [get_Chocolate](./get_chocolate/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFD2691E. |
| static [get_Coral](./get_coral/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFF7F50. |
| static [get_CornflowerBlue](./get_cornflowerblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF6495ED. |
| static [get_Cornsilk](./get_cornsilk/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFF8DC. |
| static [get_Crimson](./get_crimson/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFDC143C. |
| static [get_Cyan](./get_cyan/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF00FFFF. |
| static [get_DarkBlue](./get_darkblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF00008B. |
| static [get_DarkCyan](./get_darkcyan/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF008B8B. |
| static [get_DarkGoldenrod](./get_darkgoldenrod/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFB8860B. |
| static [get_DarkGray](./get_darkgray/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFA9A9A9. |
| static [get_DarkGreen](./get_darkgreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF006400. |
| static [get_DarkKhaki](./get_darkkhaki/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFBDB76B. |
| static [get_DarkMagenta](./get_darkmagenta/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF8B008B. |
| static [get_DarkOliveGreen](./get_darkolivegreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF556B2F. |
| static [get_DarkOrange](./get_darkorange/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFF8C00. |
| static [get_DarkOrchid](./get_darkorchid/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF9932CC. |
| static [get_DarkRed](./get_darkred/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF8B0000. |
| static [get_DarkSalmon](./get_darksalmon/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFE9967A. |
| static [get_DarkSeaGreen](./get_darkseagreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF8FBC8F. |
| static [get_DarkSlateBlue](./get_darkslateblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF483D8B. |
| static [get_DarkSlateGray](./get_darkslategray/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF2F4F4F. |
| static [get_DarkTurquoise](./get_darkturquoise/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF00CED1. |
| static [get_DarkViolet](./get_darkviolet/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF9400D3. |
| static [get_DeepPink](./get_deeppink/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFF1493. |
| static [get_DeepSkyBlue](./get_deepskyblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF00BFFF. |
| static [get_DimGray](./get_dimgray/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF696969. |
| static [get_DodgerBlue](./get_dodgerblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF1E90FF. |
| static [get_Firebrick](./get_firebrick/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFB22222. |
| static [get_FloralWhite](./get_floralwhite/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFFAF0. |
| static [get_ForestGreen](./get_forestgreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF228B22. |
| static [get_Fuchsia](./get_fuchsia/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFF00FF. |
| [get_G](./get_g/)() const | Returnerar värdet av den gröna komponenten i färgen som representeras av det aktuella objektet. |
| static [get_Gainsboro](./get_gainsboro/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFDCDCDC. |
| static [get_GhostWhite](./get_ghostwhite/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF8F8FF. |
| static [get_Gold](./get_gold/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFD700. |
| static [get_Goldenrod](./get_goldenrod/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFDAA520. |
| static [get_Gray](./get_gray/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF808080. |
| static [get_Green](./get_green/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF008000. |
| static [get_GreenYellow](./get_greenyellow/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFADFF2F. |
| static [get_Honeydew](./get_honeydew/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF0FFF0. |
| static [get_HotPink](./get_hotpink/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFF69B4. |
| static [get_IndianRed](./get_indianred/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFCD5C5C. |
| static [get_Indigo](./get_indigo/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF4B0082. |
| [get_IsEmpty](./get_isempty/)() const | Returnerar ett värde som indikerar om det aktuella objektet är "tomt" d.v.s. inte representerar någon färg. |
| [get_IsNamedColor](./get_isnamedcolor/)() const | Returnerar ett värde som avgör om [Color](./)-strukturen representerar en namngiven färg eller en medlem av [KnownColor](../knowncolor/)-enumerationen. |
| static [get_Ivory](./get_ivory/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFFFF0. |
| static [get_Khaki](./get_khaki/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF0E68C. |
| static [get_Lavender](./get_lavender/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFE6E6FA. |
| static [get_LavenderBlush](./get_lavenderblush/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFF0F5. |
| static [get_LawnGreen](./get_lawngreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF7CFC00. |
| static [get_LemonChiffon](./get_lemonchiffon/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFFACD. |
| static [get_LightBlue](./get_lightblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFADD8E6. |
| static [get_LightCoral](./get_lightcoral/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF08080. |
| static [get_LightCyan](./get_lightcyan/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFE0FFFF. |
| static [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFAFAD2. |
| static [get_LightGray](./get_lightgray/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFD3D3D3. |
| static [get_LightGreen](./get_lightgreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF90EE90. |
| static [get_LightPink](./get_lightpink/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFB6C1. |
| static [get_LightSalmon](./get_lightsalmon/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFA07A. |
| static [get_LightSeaGreen](./get_lightseagreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF20B2AA. |
| static [get_LightSkyBlue](./get_lightskyblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF87CEFA. |
| static [get_LightSlateGray](./get_lightslategray/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF778899. |
| static [get_LightSteelBlue](./get_lightsteelblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFB0C4DE. |
| static [get_LightYellow](./get_lightyellow/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFFFE0. |
| static [get_Lime](./get_lime/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF00FF00. |
| static [get_LimeGreen](./get_limegreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF32CD32. |
| static [get_Linen](./get_linen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFAF0E6. |
| static [get_Magenta](./get_magenta/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFF00FF. |
| static [get_Maroon](./get_maroon/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF800000. |
| static [get_MediumAquamarine](./get_mediumaquamarine/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF66CDAA. |
| static [get_MediumBlue](./get_mediumblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF0000CD. |
| static [get_MediumOrchid](./get_mediumorchid/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFBA55D3. |
| static [get_MediumPurple](./get_mediumpurple/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF9370DB. |
| static [get_MediumSeaGreen](./get_mediumseagreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF3CB371. |
| static [get_MediumSlateBlue](./get_mediumslateblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF7B68EE. |
| static [get_MediumSpringGreen](./get_mediumspringgreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF00FA9A. |
| static [get_MediumTurquoise](./get_mediumturquoise/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF48D1CC. |
| static [get_MediumVioletRed](./get_mediumvioletred/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFC71585. |
| static [get_MidnightBlue](./get_midnightblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF191970. |
| static [get_MintCream](./get_mintcream/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF5FFFA. |
| static [get_MistyRose](./get_mistyrose/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFE4E1. |
| static [get_Moccasin](./get_moccasin/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFE4B5. |
| [get_Name](./get_name/)() const | Returnerar namnet på färgen som representeras av det aktuella objektet. |
| static [get_NavajoWhite](./get_navajowhite/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFDEAD. |
| static [get_Navy](./get_navy/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF000080. |
| static [get_OldLace](./get_oldlace/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFDF5E6. |
| static [get_Olive](./get_olive/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF808000. |
| static [get_OliveDrab](./get_olivedrab/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF6B8E23. |
| static [get_Orange](./get_orange/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFA500. |
| static [get_OrangeRed](./get_orangered/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF4500. |
| static [get_Orchid](./get_orchid/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDA70D6. |
| static [get_PaleGoldenrod](./get_palegoldenrod/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFEEE8AA. |
| static [get_PaleGreen](./get_palegreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF98FB98. |
| static [get_PaleTurquoise](./get_paleturquoise/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFAFEEEE. |
| static [get_PaleVioletRed](./get_palevioletred/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDB7093. |
| static [get_PapayaWhip](./get_papayawhip/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFEFD5. |
| static [get_PeachPuff](./get_peachpuff/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFDAB9. |
| static [get_Peru](./get_peru/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFCD853F. |
| static [get_Pink](./get_pink/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFC0CB. |
| static [get_Plum](./get_plum/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDDA0DD. |
| static [get_PowderBlue](./get_powderblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFB0E0E6. |
| static [get_Purple](./get_purple/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF800080. |
| [get_R](./get_r/)() const | Returnerar värdet på den röda komponenten i färgen som representeras av det aktuella objektet. |
| static [get_Red](./get_red/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF0000. |
| static [get_RosyBrown](./get_rosybrown/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFBC8F8F. |
| static [get_RoyalBlue](./get_royalblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF4169E1. |
| static [get_SaddleBrown](./get_saddlebrown/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF8B4513. |
| static [get_Salmon](./get_salmon/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFA8072. |
| static [get_SandyBrown](./get_sandybrown/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF4A460. |
| static [get_SeaGreen](./get_seagreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF2E8B57. |
| static [get_SeaShell](./get_seashell/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFF5EE. |
| static [get_Sienna](./get_sienna/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFA0522D. |
| static [get_Silver](./get_silver/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFC0C0C0. |
| static [get_SkyBlue](./get_skyblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF87CEEB. |
| static [get_SlateBlue](./get_slateblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF6A5ACD. |
| static [get_SlateGray](./get_slategray/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF708090. |
| static [get_Snow](./get_snow/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFFAFA. |
| static [get_SpringGreen](./get_springgreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF00FF7F. |
| static [get_SteelBlue](./get_steelblue/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF4682B4. |
| static [get_Tan](./get_tan/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFD2B48C. |
| static [get_Teal](./get_teal/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF008080. |
| static [get_Thistle](./get_thistle/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFD8BFD8. |
| static [get_Tomato](./get_tomato/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFF6347. |
| static [get_Transparent](./get_transparent/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #00FFFFFF. |
| static [get_Turquoise](./get_turquoise/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF40E0D0. |
| static [get_Violet](./get_violet/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFEE82EE. |
| static [get_Wheat](./get_wheat/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF5DEB3. |
| static [get_White](./get_white/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFFFFF. |
| static [get_WhiteSmoke](./get_whitesmoke/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFF5F5F5. |
| static [get_Yellow](./get_yellow/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FFFFFF00. |
| static [get_YellowGreen](./get_yellowgreen/)() | Returnerar en färg vars ARGB‑värde i hexadecimal notation är #FF9ACD32. |
| [GetBrightness](./getbrightness/)() | Returnerar ljusstyrkekomponenten för färgen som representeras av det aktuella objektet. |
| [GetHashCode](./gethashcode/)() const | Returnerar hash‑koden för det aktuella objektet. |
| [GetHue](./gethue/)() | Returnerar nyansvärdet Hue-Saturation-Brightness (HSB), i grader, för färgen som representeras av det aktuella objektet. |
| [GetSaturation](./getsaturation/)() | Returnerar mättnadsvärdet Hue-Saturation-Brightness (HSB) för färgen som representeras av det aktuella objektet. |
| [IsNull](./isnull/)() const | Returnerar alltid falskt. |
| [operator!=](./operator!=/)(const std::nullptr_t\&) const | Returnerar alltid true. |
| [operator!=](./operator!=/)(const Color\&) const | Bestämmer om de aktuella och de angivna [Color](./)-objekten representerar olika färger. |
| [operator==](./operator==/)(const std::nullptr_t\&) const | Returnerar alltid falskt. |
| [operator==](./operator==/)(const Color\&) const | Avgör om de aktuella och de angivna [Color](./)-objekten representerar samma färg. |
| [ToArgb](./toargb/)() const | Returnerar ett 32‑bitars ARGB‑värde för färgen som representeras av det aktuella objektet. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av det aktuella objektet. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En "tom" instans av [Color](./)-klassen, dvs. en instans som inte representerar någon färg. |
## Se även

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
