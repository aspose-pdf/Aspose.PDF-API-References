---
title: "Класс System::Drawing::Color"
linktitle: "Color"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Drawing::Color. Представляет цвет. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 500
url: /ru/cpp/system.drawing/color/
---
## Color class


Представляет цвет. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../../system/smartptr/) для управления объектами этого типа.

```cpp
class Color
```

## Методы

| Метод | Описание |
| --- | --- |
| [Color](./color/)() | Создаёт «пустой» экземпляр класса [Color](./), который не представляет никакой цвет. |
| [Equals](./equals/)(const Color\&) const | Определяет, представляют ли текущий и указанный объекты [Color](./) один и тот же цвет. |
| static [FromArgb](./fromargb/)(int) | Создаёт экземпляр класса [Color](./), представляющий указанный цвет. |
| static [FromArgb](./fromargb/)(int, int, int, int) | Создаёт экземпляр класса [Color](./), представляющий указанный цвет. |
| static [FromArgb](./fromargb/)(int, int, int) | Создаёт экземпляр класса [Color](./), представляющий указанный цвет с альфа‑компонентом, установленным в 0xFF. |
| static [FromArgb](./fromargb/)(int, Color) | Создаёт экземпляр класса [Color](./), представляющий указанный цвет. |
| static [FromKnownColor](./fromknowncolor/)(KnownColor) | Создаёт экземпляр класса [Color](./), представляющий указанный известный цвет. |
| static [FromName](./fromname/)(const String\&) | Создаёт экземпляр класса [Color](./), представляющий цвет с указанным именем. |
| [get_A](./get_a/)() const | Возвращает значение альфа‑компоненты цвета, представленного текущим объектом. |
| static [get_AliceBlue](./get_aliceblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFF0F8FF. |
| static [get_AntiqueWhite](./get_antiquewhite/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFFAEBD7. |
| static [get_Aqua](./get_aqua/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF00FFFF. |
| static [get_Aquamarine](./get_aquamarine/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF7FFFD4. |
| static [get_Azure](./get_azure/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFF0FFFF. |
| [get_B](./get_b/)() const | Возвращает значение синего компонента цвета, представленного текущим объектом. |
| static [get_Beige](./get_beige/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFF5F5DC. |
| static [get_Bisque](./get_bisque/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFFFE4C4. |
| static [get_Black](./get_black/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF000000. |
| static [get_BlanchedAlmond](./get_blanchedalmond/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFFFEBCD. |
| static [get_Blue](./get_blue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF0000FF. |
| static [get_BlueViolet](./get_blueviolet/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF8A2BE2. |
| static [get_Brown](./get_brown/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFA52A2A. |
| static [get_BurlyWood](./get_burlywood/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFDEB887. |
| static [get_CadetBlue](./get_cadetblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF5F9EA0. |
| static [get_Chartreuse](./get_chartreuse/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF7FFF00. |
| static [get_Chocolate](./get_chocolate/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFD2691E. |
| static [get_Coral](./get_coral/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFFF7F50. |
| static [get_CornflowerBlue](./get_cornflowerblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF6495ED. |
| static [get_Cornsilk](./get_cornsilk/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFFFF8DC. |
| static [get_Crimson](./get_crimson/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FFDC143C. |
| static [get_Cyan](./get_cyan/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF00FFFF. |
| static [get_DarkBlue](./get_darkblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF00008B. |
| static [get_DarkCyan](./get_darkcyan/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации равно #FF008B8B. |
| static [get_DarkGoldenrod](./get_darkgoldenrod/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFB8860B. |
| static [get_DarkGray](./get_darkgray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFA9A9A9. |
| static [get_DarkGreen](./get_darkgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF006400. |
| static [get_DarkKhaki](./get_darkkhaki/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFBDB76B. |
| static [get_DarkMagenta](./get_darkmagenta/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF8B008B. |
| static [get_DarkOliveGreen](./get_darkolivegreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF556B2F. |
| static [get_DarkOrange](./get_darkorange/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFF8C00. |
| static [get_DarkOrchid](./get_darkorchid/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF9932CC. |
| static [get_DarkRed](./get_darkred/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF8B0000. |
| static [get_DarkSalmon](./get_darksalmon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFE9967A. |
| static [get_DarkSeaGreen](./get_darkseagreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF8FBC8F. |
| static [get_DarkSlateBlue](./get_darkslateblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF483D8B. |
| static [get_DarkSlateGray](./get_darkslategray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF2F4F4F. |
| static [get_DarkTurquoise](./get_darkturquoise/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF00CED1. |
| static [get_DarkViolet](./get_darkviolet/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF9400D3. |
| static [get_DeepPink](./get_deeppink/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFF1493. |
| static [get_DeepSkyBlue](./get_deepskyblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF00BFFF. |
| static [get_DimGray](./get_dimgray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF696969. |
| static [get_DodgerBlue](./get_dodgerblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF1E90FF. |
| static [get_Firebrick](./get_firebrick/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFB22222. |
| static [get_FloralWhite](./get_floralwhite/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFFAF0. |
| static [get_ForestGreen](./get_forestgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF228B22. |
| static [get_Fuchsia](./get_fuchsia/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFF00FF. |
| [get_G](./get_g/)() const | Возвращает значение зеленого компонента цвета, представленного текущим объектом. |
| static [get_Gainsboro](./get_gainsboro/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFDCDCDC. |
| static [get_GhostWhite](./get_ghostwhite/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFF8F8FF. |
| static [get_Gold](./get_gold/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFD700. |
| static [get_Goldenrod](./get_goldenrod/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFDAA520. |
| static [get_Gray](./get_gray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF808080. |
| static [get_Green](./get_green/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF008000. |
| static [get_GreenYellow](./get_greenyellow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFADFF2F. |
| static [get_Honeydew](./get_honeydew/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFF0FFF0. |
| static [get_HotPink](./get_hotpink/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFF69B4. |
| static [get_IndianRed](./get_indianred/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFCD5C5C. |
| static [get_Indigo](./get_indigo/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF4B0082. |
| [get_IsEmpty](./get_isempty/)() const | Возвращает значение, указывающее, является ли текущий объект "empty", т.е. не представляет никакого цвета. |
| [get_IsNamedColor](./get_isnamedcolor/)() const | Возвращает значение, определяющее, представляет ли структура [Color](./) именованный цвет или является членом перечисления [KnownColor](../knowncolor/). |
| static [get_Ivory](./get_ivory/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFFFF0. |
| static [get_Khaki](./get_khaki/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFF0E68C. |
| static [get_Lavender](./get_lavender/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFE6E6FA. |
| static [get_LavenderBlush](./get_lavenderblush/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFF0F5. |
| static [get_LawnGreen](./get_lawngreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF7CFC00. |
| static [get_LemonChiffon](./get_lemonchiffon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFFACD. |
| static [get_LightBlue](./get_lightblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFADD8E6. |
| static [get_LightCoral](./get_lightcoral/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFF08080. |
| static [get_LightCyan](./get_lightcyan/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFE0FFFF. |
| static [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFAFAD2. |
| static [get_LightGray](./get_lightgray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFD3D3D3. |
| static [get_LightGreen](./get_lightgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF90EE90. |
| static [get_LightPink](./get_lightpink/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFB6C1. |
| static [get_LightSalmon](./get_lightsalmon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFA07A. |
| static [get_LightSeaGreen](./get_lightseagreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF20B2AA. |
| static [get_LightSkyBlue](./get_lightskyblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF87CEFA. |
| static [get_LightSlateGray](./get_lightslategray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF778899. |
| static [get_LightSteelBlue](./get_lightsteelblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFB0C4DE. |
| static [get_LightYellow](./get_lightyellow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFFFE0. |
| static [get_Lime](./get_lime/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF00FF00. |
| static [get_LimeGreen](./get_limegreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF32CD32. |
| static [get_Linen](./get_linen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFAF0E6. |
| static [get_Magenta](./get_magenta/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFF00FF. |
| static [get_Maroon](./get_maroon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF800000. |
| static [get_MediumAquamarine](./get_mediumaquamarine/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF66CDAA. |
| static [get_MediumBlue](./get_mediumblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF0000CD. |
| static [get_MediumOrchid](./get_mediumorchid/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFBA55D3. |
| static [get_MediumPurple](./get_mediumpurple/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF9370DB. |
| static [get_MediumSeaGreen](./get_mediumseagreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF3CB371. |
| static [get_MediumSlateBlue](./get_mediumslateblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF7B68EE. |
| static [get_MediumSpringGreen](./get_mediumspringgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF00FA9A. |
| static [get_MediumTurquoise](./get_mediumturquoise/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF48D1CC. |
| static [get_MediumVioletRed](./get_mediumvioletred/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFC71585. |
| static [get_MidnightBlue](./get_midnightblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF191970. |
| static [get_MintCream](./get_mintcream/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFF5FFFA. |
| static [get_MistyRose](./get_mistyrose/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFE4E1. |
| static [get_Moccasin](./get_moccasin/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFE4B5. |
| [get_Name](./get_name/)() const | Возвращает имя цвета, представленного текущим объектом. |
| static [get_NavajoWhite](./get_navajowhite/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFDEAD. |
| static [get_Navy](./get_navy/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF000080. |
| static [get_OldLace](./get_oldlace/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFDF5E6. |
| static [get_Olive](./get_olive/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF808000. |
| static [get_OliveDrab](./get_olivedrab/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF6B8E23. |
| static [get_Orange](./get_orange/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFA500. |
| static [get_OrangeRed](./get_orangered/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFF4500. |
| static [get_Orchid](./get_orchid/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFDA70D6. |
| static [get_PaleGoldenrod](./get_palegoldenrod/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFEEE8AA. |
| static [get_PaleGreen](./get_palegreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF98FB98. |
| static [get_PaleTurquoise](./get_paleturquoise/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFAFEEEE. |
| static [get_PaleVioletRed](./get_palevioletred/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFDB7093. |
| static [get_PapayaWhip](./get_papayawhip/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFEFD5. |
| static [get_PeachPuff](./get_peachpuff/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFDAB9. |
| static [get_Peru](./get_peru/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFCD853F. |
| static [get_Pink](./get_pink/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFC0CB. |
| static [get_Plum](./get_plum/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFDDA0DD. |
| static [get_PowderBlue](./get_powderblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFB0E0E6. |
| static [get_Purple](./get_purple/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF800080. |
| [get_R](./get_r/)() const | Возвращает значение красного компонента цвета, представленного текущим объектом. |
| static [get_Red](./get_red/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFF0000. |
| static [get_RosyBrown](./get_rosybrown/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFBC8F8F. |
| static [get_RoyalBlue](./get_royalblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF4169E1. |
| static [get_SaddleBrown](./get_saddlebrown/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF8B4513. |
| static [get_Salmon](./get_salmon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFA8072. |
| static [get_SandyBrown](./get_sandybrown/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFF4A460. |
| static [get_SeaGreen](./get_seagreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF2E8B57. |
| static [get_SeaShell](./get_seashell/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFF5EE. |
| static [get_Sienna](./get_sienna/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFA0522D. |
| static [get_Silver](./get_silver/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFC0C0C0. |
| static [get_SkyBlue](./get_skyblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF87CEEB. |
| static [get_SlateBlue](./get_slateblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF6A5ACD. |
| static [get_SlateGray](./get_slategray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF708090. |
| static [get_Snow](./get_snow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFFAFA. |
| static [get_SpringGreen](./get_springgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF00FF7F. |
| static [get_SteelBlue](./get_steelblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF4682B4. |
| static [get_Tan](./get_tan/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFD2B48C. |
| static [get_Teal](./get_teal/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF008080. |
| static [get_Thistle](./get_thistle/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFD8BFD8. |
| static [get_Tomato](./get_tomato/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFF6347. |
| static [get_Transparent](./get_transparent/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #00FFFFFF. |
| static [get_Turquoise](./get_turquoise/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF40E0D0. |
| static [get_Violet](./get_violet/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFEE82EE. |
| static [get_Wheat](./get_wheat/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFF5DEB3. |
| static [get_White](./get_white/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFFFFF. |
| static [get_WhiteSmoke](./get_whitesmoke/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFF5F5F5. |
| static [get_Yellow](./get_yellow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FFFFFF00. |
| static [get_YellowGreen](./get_yellowgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной нотации #FF9ACD32. |
| [GetBrightness](./getbrightness/)() | Возвращает компонент яркости цвета, представленного текущим объектом. |
| [GetHashCode](./gethashcode/)() const | Возвращает хеш‑код текущего объекта. |
| [GetHue](./gethue/)() | Возвращает значение оттенка (Hue) в системе Hue‑Saturation‑Brightness (HSB) в градусах для цвета, представленного текущим объектом. |
| [GetSaturation](./getsaturation/)() | Возвращает насыщенность Hue-Saturation-Brightness (HSB) для цвета, представленного текущим объектом. |
| [IsNull](./isnull/)() const | Всегда возвращает false. |
| [operator!=](./operator!=/)(const std::nullptr_t\&) const | Всегда возвращает true. |
| [operator!=](./operator!=/)(const Color\&) const | Определяет, представляют ли текущий и указанный объекты [Color](./) разные цвета. |
| [operator==](./operator==/)(const std::nullptr_t\&) const | Всегда возвращает false. |
| [operator==](./operator==/)(const Color\&) const | Определяет, представляют ли текущий и указанный объекты [Color](./) один и тот же цвет. |
| [ToArgb](./toargb/)() const | Возвращает 32-битное значение ARGB цвета, представленного текущим объектом. |
| [ToString](./tostring/)() const | Возвращает строковое представление текущего объекта. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](./empty/) | «Пустой» экземпляр класса [Color](./), т.е. экземпляр, который не представляет никакого цвета. |
## См. также

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
