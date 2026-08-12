---
title: "Aspose::Pdf::Color класс"
linktitle: "Color"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Color класс. Представляет класс значения цвета, которое может быть выражено в разных цветовых пространствах в C++."
type: docs
weight: 2800
url: /ru/cpp/aspose.pdf/color/
---
## Color class


Представляет класс для значения цвета, которое может быть выражено в разных цветовых пространствах.

```cpp
class Color : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Color](./color/)() | Конструктор по умолчанию. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Возвращает true, если два Colors равны. |
| static [FromArgb](./fromargb/)(int32_t, int32_t, int32_t) | Получает действительный объект pdf [Color](./) из компонентов цвета RGB. |
| static [FromArgb](./fromargb/)(int32_t, int32_t, int32_t, int32_t) | Получает действительный объект pdf [Color](./) из компонентов цвета RGB. |
| static [FromCmyk](./fromcmyk/)(double, double, double, double) | Получает действительный объект pdf [Color](./) из компонентов цвета CMYK. |
| static [FromGray](./fromgray/)(double) | Получает действительный объект pdf [Color](./) из компонента цвета Gray. |
| static [FromRgb](./fromrgb/)(System::Drawing::Color) | Получает действительный объект pdf [Color](./) из значения [System.Drawing.Color](../../system.drawing/color/). |
| static [FromRgb](./fromrgb/)(double, double, double) | Получает действительный объект pdf [Color](./) из компонентов цвета RGB. |
| [get_A](./get_a/)() const | Получает значение альфа‑компоненты. |
| static [get_AliceBlue](./get_aliceblue/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFF0F8FF**. |
| static [get_AntiqueWhite](./get_antiquewhite/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFFAEBD7**. |
| static [get_Aqua](./get_aqua/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF00FFFF**. |
| static [get_Aquamarine](./get_aquamarine/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF7FFFD4**. |
| static [get_Azure](./get_azure/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFF0FFFF**. |
| static [get_Beige](./get_beige/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFF5F5DC**. |
| static [get_Bisque](./get_bisque/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFFFE4C4**. |
| static [get_Black](./get_black/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF000000**. |
| static [get_BlanchedAlmond](./get_blanchedalmond/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFFFEBCD**. |
| static [get_Blue](./get_blue/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF0000FF**. |
| static [get_BlueViolet](./get_blueviolet/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF8A2BE2**. |
| static [get_Brown](./get_brown/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFA52A2A**. |
| static [get_BurlyWood](./get_burlywood/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFDEB887**. |
| static [get_CadetBlue](./get_cadetblue/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF5F9EA0**. |
| static [get_Chartreuse](./get_chartreuse/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF7FFF00**. |
| static [get_Chocolate](./get_chocolate/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFD2691E**. |
| [get_ColorSpace](./get_colorspace/)() | Получает цветовое пространство, которое представляет цвет. |
| static [get_Coral](./get_coral/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFFF7F50**. |
| static [get_CornflowerBlue](./get_cornflowerblue/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF6495ED**. |
| static [get_Cornsilk](./get_cornsilk/)() | Получает системно‑определённый цвет с ARGB‑значением **#FFFFF8DC**. |
| static [get_Crimson](./get_crimson/)() | Получает системно определённый цвет, значение ARGB которого **#FFDC143C**. |
| static [get_Cyan](./get_cyan/)() | Получает системно‑определённый цвет с ARGB‑значением **#FF00FFFF**. |
| static [get_DarkBlue](./get_darkblue/)() | Получает системно определённый цвет, значение ARGB которого **#FF00008B**. |
| static [get_DarkCyan](./get_darkcyan/)() | Получает системно определённый цвет, значение ARGB которого **#FF008B8B**. |
| static [get_DarkGoldenrod](./get_darkgoldenrod/)() | Получает системно определённый цвет, значение ARGB которого **#FFB8860B**. |
| static [get_DarkGray](./get_darkgray/)() | Получает системно определённый цвет, значение ARGB которого **#FFA9A9A9**. |
| static [get_DarkGreen](./get_darkgreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF006400**. |
| static [get_DarkKhaki](./get_darkkhaki/)() | Получает системно определённый цвет, значение ARGB которого **#FFBDB76B**. |
| static [get_DarkMagenta](./get_darkmagenta/)() | Получает системно определённый цвет, значение ARGB которого **#FF8B008B**. |
| static [get_DarkOliveGreen](./get_darkolivegreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF556B2F**. |
| static [get_DarkOrange](./get_darkorange/)() | Получает системно определённый цвет, значение ARGB которого **#FFFF8C00**. |
| static [get_DarkOrchid](./get_darkorchid/)() | Получает системно определённый цвет, значение ARGB которого **#FF9932CC**. |
| static [get_DarkRed](./get_darkred/)() | Получает системно определённый цвет, значение ARGB которого **#FF8B0000**. |
| static [get_DarkSalmon](./get_darksalmon/)() | Получает системно определённый цвет, значение ARGB которого **#FFE9967A**. |
| static [get_DarkSeaGreen](./get_darkseagreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF8FBC8F**. |
| static [get_DarkSlateBlue](./get_darkslateblue/)() | Получает системно определённый цвет, значение ARGB которого **#FF483D8B**. |
| static [get_DarkSlateGray](./get_darkslategray/)() | Получает системно определённый цвет, значение ARGB которого **#FF2F4F4F**. |
| static [get_DarkTurquoise](./get_darkturquoise/)() | Получает системно определённый цвет, значение ARGB которого **#FF00CED1**. |
| static [get_DarkViolet](./get_darkviolet/)() | Получает системно определённый цвет, значение ARGB которого **#FF9400D3**. |
| [get_Data](./get_data/)() const | Получает значение цвета. |
| static [get_DeepPink](./get_deeppink/)() | Получает системно определённый цвет, значение ARGB которого **#FFFF1493**. |
| static [get_DeepSkyBlue](./get_deepskyblue/)() | Получает системно определённый цвет, значение ARGB которого **#FF00BFFF**. |
| static [get_DimGray](./get_dimgray/)() | Получает системно определённый цвет, значение ARGB которого **#FF696969**. |
| static [get_DodgerBlue](./get_dodgerblue/)() | Получает системно определённый цвет, значение ARGB которого **#FF1E90FF**. |
| static [get_Firebrick](./get_firebrick/)() | Получает системно определённый цвет, значение ARGB которого **#FFB22222**. |
| static [get_FloralWhite](./get_floralwhite/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFFAF0**. |
| static [get_ForestGreen](./get_forestgreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF228B22**. |
| static [get_Fuchsia](./get_fuchsia/)() | Получает системно определённый цвет, значение ARGB которого **#FFFF00FF**. |
| static [get_Gainsboro](./get_gainsboro/)() | Получает системно определённый цвет, значение ARGB которого **#FFDCDCDC**. |
| static [get_GhostWhite](./get_ghostwhite/)() | Получает системно определённый цвет, значение ARGB которого **#FFF8F8FF**. |
| static [get_Gold](./get_gold/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFD700**. |
| static [get_Goldenrod](./get_goldenrod/)() | Получает системно определённый цвет, значение ARGB которого **#FFDAA520**. |
| static [get_Gray](./get_gray/)() | Получает системно определённый цвет, значение ARGB которого **#FF808080**. |
| static [get_Green](./get_green/)() | Получает системно определённый цвет, значение ARGB которого **#FF008000**. |
| static [get_GreenYellow](./get_greenyellow/)() | Получает системно определённый цвет, значение ARGB которого **#FFADFF2F**. |
| static [get_Honeydew](./get_honeydew/)() | Получает системно определённый цвет, значение ARGB которого **#FFF0FFF0**. |
| static [get_HotPink](./get_hotpink/)() | Получает системно определённый цвет, значение ARGB которого **#FFFF69B4**. |
| static [get_IndianRed](./get_indianred/)() | Получает системно определённый цвет, значение ARGB которого **#FFCD5C5C**. |
| static [get_Indigo](./get_indigo/)() | Получает системно определённый цвет, значение ARGB которого **#FF4B0082**. |
| static [get_Ivory](./get_ivory/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFFFF0**. |
| static [get_Khaki](./get_khaki/)() | Получает системно определённый цвет, значение ARGB которого **#FFF0E68C**. |
| static [get_Lavender](./get_lavender/)() | Получает системно определённый цвет, значение ARGB которого **#FFE6E6FA**. |
| static [get_LavenderBlush](./get_lavenderblush/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFF0F5**. |
| static [get_LawnGreen](./get_lawngreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF7CFC00**. |
| static [get_LemonChiffon](./get_lemonchiffon/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFFACD**. |
| static [get_LightBlue](./get_lightblue/)() | Получает системно определённый цвет, значение ARGB которого **#FFADD8E6**. |
| static [get_LightCoral](./get_lightcoral/)() | Получает системно определённый цвет, значение ARGB которого **#FFF08080**. |
| static [get_LightCyan](./get_lightcyan/)() | Получает системно определённый цвет, значение ARGB которого **#FFE0FFFF**. |
| static [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Получает системно определённый цвет, значение ARGB которого **#FFFAFAD2**. |
| static [get_LightGray](./get_lightgray/)() | Получает системно определённый цвет, значение ARGB которого **#FFD3D3D3**. |
| static [get_LightGreen](./get_lightgreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF90EE90**. |
| static [get_LightPink](./get_lightpink/)() | Получает системно определённый цвет со значением ARGB **#FFFFB6C1**. |
| static [get_LightSalmon](./get_lightsalmon/)() | Получает системно определённый цвет со значением ARGB **#FFFFA07A**. |
| static [get_LightSeaGreen](./get_lightseagreen/)() | Получает системно определённый цвет со значением ARGB **#FF20B2AA**. |
| static [get_LightSkyBlue](./get_lightskyblue/)() | Получает системно определённый цвет со значением ARGB **#FF87CEFA**. |
| static [get_LightSlateGray](./get_lightslategray/)() | Получает системно определённый цвет со значением ARGB **#FF778899**. |
| static [get_LightSteelBlue](./get_lightsteelblue/)() | Получает системно определённый цвет со значением ARGB **#FFB0C4DE**. |
| static [get_LightYellow](./get_lightyellow/)() | Получает системно определённый цвет со значением ARGB **#FFFFFFE0**. |
| static [get_Lime](./get_lime/)() | Получает системно определённый цвет со значением ARGB **#FF00FF00**. |
| static [get_LimeGreen](./get_limegreen/)() | Получает системно определённый цвет со значением ARGB **#FF32CD32**. |
| static [get_Linen](./get_linen/)() | Получает системно определённый цвет со значением ARGB **#FFFAF0E6**. |
| static [get_Magenta](./get_magenta/)() | Получает системно определённый цвет, значение ARGB которого **#FFFF00FF**. |
| static [get_Maroon](./get_maroon/)() | Получает системно определённый цвет со значением ARGB **#FF800000**. |
| static [get_MediumAquamarine](./get_mediumaquamarine/)() | Получает системно определённый цвет со значением ARGB **#FF66CDAA**. |
| static [get_MediumBlue](./get_mediumblue/)() | Получает системно определённый цвет со значением ARGB **#FF0000CD**. |
| static [get_MediumOrchid](./get_mediumorchid/)() | Получает системно определённый цвет со значением ARGB **#FFBA55D3**. |
| static [get_MediumPurple](./get_mediumpurple/)() | Получает системно определённый цвет со значением ARGB **#FF9370DB**. |
| static [get_MediumSeaGreen](./get_mediumseagreen/)() | Получает системно определённый цвет со значением ARGB **#FF3CB371**. |
| static [get_MediumSlateBlue](./get_mediumslateblue/)() | Получает системно определённый цвет со значением ARGB **#FF7B68EE**. |
| static [get_MediumSpringGreen](./get_mediumspringgreen/)() | Получает системно определённый цвет со значением ARGB **#FF00FA9A**. |
| static [get_MediumTurquoise](./get_mediumturquoise/)() | Получает системно определённый цвет со значением ARGB **#FF48D1CC**. |
| static [get_MediumVioletRed](./get_mediumvioletred/)() | Получает системно определённый цвет со значением ARGB **#FFC71585**. |
| static [get_MidnightBlue](./get_midnightblue/)() | Получает системно определённый цвет со значением ARGB **#FF191970**. |
| static [get_MintCream](./get_mintcream/)() | Получает системно определённый цвет со значением ARGB **#FFF5FFFA**. |
| static [get_MistyRose](./get_mistyrose/)() | Получает системно определённый цвет со значением ARGB **#FFFFE4E1**. |
| static [get_Moccasin](./get_moccasin/)() | Получает системно определённый цвет со значением ARGB **#FFFFE4B5**. |
| static [get_NavajoWhite](./get_navajowhite/)() | Получает системно определённый цвет со значением ARGB **#FFFFDEAD**. |
| static [get_Navy](./get_navy/)() | Получает системно определённый цвет, значение ARGB которого **#FF000080**. |
| static [get_OldLace](./get_oldlace/)() | Получает системно определённый цвет, значение ARGB которого **#FFFDF5E6**. |
| static [get_Olive](./get_olive/)() | Получает системно определённый цвет, значение ARGB которого **#FF808000**. |
| static [get_OliveDrab](./get_olivedrab/)() | Получает системно определённый цвет, значение ARGB которого **#FF6B8E23**. |
| static [get_Orange](./get_orange/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFA500**. |
| static [get_OrangeRed](./get_orangered/)() | Получает системно определённый цвет, значение ARGB которого **#FFFF4500**. |
| static [get_Orchid](./get_orchid/)() | Получает системно определённый цвет, значение ARGB которого **#FFDA70D6**. |
| static [get_PaleGoldenrod](./get_palegoldenrod/)() | Получает системно определённый цвет, значение ARGB которого **#FFEEE8AA**. |
| static [get_PaleGreen](./get_palegreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF98FB98**. |
| static [get_PaleTurquoise](./get_paleturquoise/)() | Получает системно определённый цвет, значение ARGB которого **#FFAFEEEE**. |
| static [get_PaleVioletRed](./get_palevioletred/)() | Получает системно определённый цвет, значение ARGB которого **#FFDB7093**. |
| static [get_PapayaWhip](./get_papayawhip/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFEFD5**. |
| [get_PatternColorSpace](./get_patterncolorspace/)() const | Представляет объект, указывающий цветовое пространство шаблона. |
| static [get_PeachPuff](./get_peachpuff/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFDAB9**. |
| static [get_Peru](./get_peru/)() | Получает системно определённый цвет, значение ARGB которого **#FFCD853F**. |
| static [get_Pink](./get_pink/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFC0CB**. |
| static [get_Plum](./get_plum/)() | Получает системно определённый цвет, значение ARGB которого **#FFDDA0DD**. |
| static [get_PowderBlue](./get_powderblue/)() | Получает системно определённый цвет, значение ARGB которого **#FFB0E0E6**. |
| static [get_Purple](./get_purple/)() | Получает системно определённый цвет, значение ARGB которого **#FF800080**. |
| static [get_Red](./get_red/)() | Получает системно определённый цвет, значение ARGB которого **#FFFF0000**. |
| static [get_RosyBrown](./get_rosybrown/)() | Получает системно определённый цвет, значение ARGB которого **#FFBC8F8F**. |
| static [get_RoyalBlue](./get_royalblue/)() | Получает системно определённый цвет, значение ARGB которого **#FF4169E1**. |
| static [get_SaddleBrown](./get_saddlebrown/)() | Получает системно определённый цвет, значение ARGB которого **#FF8B4513**. |
| static [get_Salmon](./get_salmon/)() | Получает системно определённый цвет, значение ARGB которого **#FFFA8072**. |
| static [get_SandyBrown](./get_sandybrown/)() | Получает системно определённый цвет, значение ARGB которого **#FFF4A460**. |
| static [get_SeaGreen](./get_seagreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF2E8B57**. |
| static [get_SeaShell](./get_seashell/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFF5EE**. |
| static [get_Sienna](./get_sienna/)() | Получает системно определённый цвет, значение ARGB которого **#FFA0522D**. |
| static [get_Silver](./get_silver/)() | Получает системно определённый цвет, значение ARGB которого **#FFC0C0C0**. |
| static [get_SkyBlue](./get_skyblue/)() | Получает системно определённый цвет, значение ARGB которого **#FF87CEEB**. |
| static [get_SlateBlue](./get_slateblue/)() | Получает системно определённый цвет, значение ARGB которого **#FF6A5ACD**. |
| static [get_SlateGray](./get_slategray/)() | Получает системно определённый цвет, значение ARGB которого **#FF708090**. |
| static [get_Snow](./get_snow/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFFAFA**. |
| static [get_SpringGreen](./get_springgreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF00FF7F**. |
| static [get_SteelBlue](./get_steelblue/)() | Получает системно определённый цвет, значение ARGB которого **#FF4682B4**. |
| static [get_Tan](./get_tan/)() | Получает системно определённый цвет, значение ARGB которого **#FFD2B48C**. |
| static [get_Teal](./get_teal/)() | Получает системно определённый цвет, значение ARGB которого **#FF008080**. |
| static [get_Thistle](./get_thistle/)() | Получает системно определённый цвет, значение ARGB которого **#FFD8BFD8**. |
| static [get_Tomato](./get_tomato/)() | Получает системно определённый цвет, значение ARGB которого **#FFFF6347**. |
| static [get_Transparent](./get_transparent/)() | Получает системно определённый цвет. |
| static [get_Turquoise](./get_turquoise/)() | Получает системно определённый цвет, значение ARGB которого **#FF40E0D0**. |
| static [get_Violet](./get_violet/)() | Получает системно определённый цвет, значение ARGB которого **#FFEE82EE**. |
| static [get_Wheat](./get_wheat/)() | Получает системно определённый цвет, значение ARGB которого **#FFF5DEB3**. |
| static [get_White](./get_white/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFFFFF**. |
| static [get_WhiteSmoke](./get_whitesmoke/)() | Получает системно определённый цвет, значение ARGB которого **#FFF5F5F5**. |
| static [get_Yellow](./get_yellow/)() | Получает системно определённый цвет, значение ARGB которого **#FFFFFF00**. |
| static [get_YellowGreen](./get_yellowgreen/)() | Получает системно определённый цвет, значение ARGB которого **#FF9ACD32**. |
| static [Parse](./parse/)(const System::String\&) | Извлекает компоненты цвета из строки. |
| [set_PatternColorSpace](./set_patterncolorspace/)(const System::SharedPtr\<Aspose::Pdf::Drawing::PatternColorSpace\>\&) | Представляет объект, указывающий цветовое пространство шаблона. |
| [ToRgb](./torgb/)() | Преобразует цвет в rgb. |
| [ToString](./tostring/)() const override | Преобразует в строку. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](./empty/) | Представляет пустой цвет. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
