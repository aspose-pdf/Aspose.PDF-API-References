---
title: Aspose::Pdf::Color class
linktitle: Color
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Color class. Represents class for color value which can be expressed in different color space in C++.'
type: docs
weight: 3000
url: /cpp/aspose.pdf/color/
---
## Color class


Represents class for color value which can be expressed in different color space.

```cpp
class Color : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Color](./color/)() | Default constructor. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns true if two Colors are equal. |
| static [FromArgb](./fromargb/)(int32_t, int32_t, int32_t) | Gets valid pdf [Color](./) object from RGB color components. |
| static [FromArgb](./fromargb/)(int32_t, int32_t, int32_t, int32_t) | Gets valid pdf [Color](./) object from RGB color components. |
| static [FromCmyk](./fromcmyk/)(double, double, double, double) | Gets valid pdf [Color](./) object from CMYK color components. |
| static [FromGray](./fromgray/)(double) | Gets valid pdf [Color](./) object from Gray color component. |
| static [FromRgb](./fromrgb/)(System::Drawing::Color) | Gets valid pdf [Color](./) object from [System.Drawing.Color](../../system.drawing/color/) value. |
| static [FromRgb](./fromrgb/)(double, double, double) | Gets valid pdf [Color](./) object from RGB color components. |
| [get_A](./get_a/)() const | Gets the alpha component value. |
| static [get_AliceBlue](./get_aliceblue/)() | Gets a system-defined color that has an ARGB value of **#FFF0F8FF**. |
| static [get_AntiqueWhite](./get_antiquewhite/)() | Gets a system-defined color that has an ARGB value of **#FFFAEBD7**. |
| static [get_Aqua](./get_aqua/)() | Gets a system-defined color that has an ARGB value of **#FF00FFFF**. |
| static [get_Aquamarine](./get_aquamarine/)() | Gets a system-defined color that has an ARGB value of **#FF7FFFD4**. |
| static [get_Azure](./get_azure/)() | Gets a system-defined color that has an ARGB value of **#FFF0FFFF**. |
| static [get_Beige](./get_beige/)() | Gets a system-defined color that has an ARGB value of **#FFF5F5DC**. |
| static [get_Bisque](./get_bisque/)() | Gets a system-defined color that has an ARGB value of **#FFFFE4C4**. |
| static [get_Black](./get_black/)() | Gets a system-defined color that has an ARGB value of **#FF000000**. |
| static [get_BlanchedAlmond](./get_blanchedalmond/)() | Gets a system-defined color that has an ARGB value of **#FFFFEBCD**. |
| static [get_Blue](./get_blue/)() | Gets a system-defined color that has an ARGB value of **#FF0000FF**. |
| static [get_BlueViolet](./get_blueviolet/)() | Gets a system-defined color that has an ARGB value of **#FF8A2BE2**. |
| static [get_Brown](./get_brown/)() | Gets a system-defined color that has an ARGB value of **#FFA52A2A**. |
| static [get_BurlyWood](./get_burlywood/)() | Gets a system-defined color that has an ARGB value of **#FFDEB887**. |
| static [get_CadetBlue](./get_cadetblue/)() | Gets a system-defined color that has an ARGB value of **#FF5F9EA0**. |
| static [get_Chartreuse](./get_chartreuse/)() | Gets a system-defined color that has an ARGB value of **#FF7FFF00**. |
| static [get_Chocolate](./get_chocolate/)() | Gets a system-defined color that has an ARGB value of **#FFD2691E**. |
| [get_ColorSpace](./get_colorspace/)() | Gets color space that the color represents. |
| static [get_Coral](./get_coral/)() | Gets a system-defined color that has an ARGB value of **#FFFF7F50**. |
| static [get_CornflowerBlue](./get_cornflowerblue/)() | Gets a system-defined color that has an ARGB value of **#FF6495ED**. |
| static [get_Cornsilk](./get_cornsilk/)() | Gets a system-defined color that has an ARGB value of **#FFFFF8DC**. |
| static [get_Crimson](./get_crimson/)() | Gets a system-defined color that has an ARGB value of **#FFDC143C**. |
| static [get_Cyan](./get_cyan/)() | Gets a system-defined color that has an ARGB value of **#FF00FFFF**. |
| static [get_DarkBlue](./get_darkblue/)() | Gets a system-defined color that has an ARGB value of **#FF00008B**. |
| static [get_DarkCyan](./get_darkcyan/)() | Gets a system-defined color that has an ARGB value of **#FF008B8B**. |
| static [get_DarkGoldenrod](./get_darkgoldenrod/)() | Gets a system-defined color that has an ARGB value of **#FFB8860B**. |
| static [get_DarkGray](./get_darkgray/)() | Gets a system-defined color that has an ARGB value of **#FFA9A9A9**. |
| static [get_DarkGreen](./get_darkgreen/)() | Gets a system-defined color that has an ARGB value of **#FF006400**. |
| static [get_DarkKhaki](./get_darkkhaki/)() | Gets a system-defined color that has an ARGB value of **#FFBDB76B**. |
| static [get_DarkMagenta](./get_darkmagenta/)() | Gets a system-defined color that has an ARGB value of **#FF8B008B**. |
| static [get_DarkOliveGreen](./get_darkolivegreen/)() | Gets a system-defined color that has an ARGB value of **#FF556B2F**. |
| static [get_DarkOrange](./get_darkorange/)() | Gets a system-defined color that has an ARGB value of **#FFFF8C00**. |
| static [get_DarkOrchid](./get_darkorchid/)() | Gets a system-defined color that has an ARGB value of **#FF9932CC**. |
| static [get_DarkRed](./get_darkred/)() | Gets a system-defined color that has an ARGB value of **#FF8B0000**. |
| static [get_DarkSalmon](./get_darksalmon/)() | Gets a system-defined color that has an ARGB value of **#FFE9967A**. |
| static [get_DarkSeaGreen](./get_darkseagreen/)() | Gets a system-defined color that has an ARGB value of **#FF8FBC8F**. |
| static [get_DarkSlateBlue](./get_darkslateblue/)() | Gets a system-defined color that has an ARGB value of **#FF483D8B**. |
| static [get_DarkSlateGray](./get_darkslategray/)() | Gets a system-defined color that has an ARGB value of **#FF2F4F4F**. |
| static [get_DarkTurquoise](./get_darkturquoise/)() | Gets a system-defined color that has an ARGB value of **#FF00CED1**. |
| static [get_DarkViolet](./get_darkviolet/)() | Gets a system-defined color that has an ARGB value of **#FF9400D3**. |
| [get_Data](./get_data/)() const | Gets color value. |
| static [get_DeepPink](./get_deeppink/)() | Gets a system-defined color that has an ARGB value of **#FFFF1493**. |
| static [get_DeepSkyBlue](./get_deepskyblue/)() | Gets a system-defined color that has an ARGB value of **#FF00BFFF**. |
| static [get_DimGray](./get_dimgray/)() | Gets a system-defined color that has an ARGB value of **#FF696969**. |
| static [get_DodgerBlue](./get_dodgerblue/)() | Gets a system-defined color that has an ARGB value of **#FF1E90FF**. |
| static [get_Firebrick](./get_firebrick/)() | Gets a system-defined color that has an ARGB value of **#FFB22222**. |
| static [get_FloralWhite](./get_floralwhite/)() | Gets a system-defined color that has an ARGB value of **#FFFFFAF0**. |
| static [get_ForestGreen](./get_forestgreen/)() | Gets a system-defined color that has an ARGB value of **#FF228B22**. |
| static [get_Fuchsia](./get_fuchsia/)() | Gets a system-defined color that has an ARGB value of **#FFFF00FF**. |
| static [get_Gainsboro](./get_gainsboro/)() | Gets a system-defined color that has an ARGB value of **#FFDCDCDC**. |
| static [get_GhostWhite](./get_ghostwhite/)() | Gets a system-defined color that has an ARGB value of **#FFF8F8FF**. |
| static [get_Gold](./get_gold/)() | Gets a system-defined color that has an ARGB value of **#FFFFD700**. |
| static [get_Goldenrod](./get_goldenrod/)() | Gets a system-defined color that has an ARGB value of **#FFDAA520**. |
| static [get_Gray](./get_gray/)() | Gets a system-defined color that has an ARGB value of **#FF808080**. |
| static [get_Green](./get_green/)() | Gets a system-defined color that has an ARGB value of **#FF008000**. |
| static [get_GreenYellow](./get_greenyellow/)() | Gets a system-defined color that has an ARGB value of **#FFADFF2F**. |
| static [get_Honeydew](./get_honeydew/)() | Gets a system-defined color that has an ARGB value of **#FFF0FFF0**. |
| static [get_HotPink](./get_hotpink/)() | Gets a system-defined color that has an ARGB value of **#FFFF69B4**. |
| static [get_IndianRed](./get_indianred/)() | Gets a system-defined color that has an ARGB value of **#FFCD5C5C**. |
| static [get_Indigo](./get_indigo/)() | Gets a system-defined color that has an ARGB value of **#FF4B0082**. |
| static [get_Ivory](./get_ivory/)() | Gets a system-defined color that has an ARGB value of **#FFFFFFF0**. |
| static [get_Khaki](./get_khaki/)() | Gets a system-defined color that has an ARGB value of **#FFF0E68C**. |
| static [get_Lavender](./get_lavender/)() | Gets a system-defined color that has an ARGB value of **#FFE6E6FA**. |
| static [get_LavenderBlush](./get_lavenderblush/)() | Gets a system-defined color that has an ARGB value of **#FFFFF0F5**. |
| static [get_LawnGreen](./get_lawngreen/)() | Gets a system-defined color that has an ARGB value of **#FF7CFC00**. |
| static [get_LemonChiffon](./get_lemonchiffon/)() | Gets a system-defined color that has an ARGB value of **#FFFFFACD**. |
| static [get_LightBlue](./get_lightblue/)() | Gets a system-defined color that has an ARGB value of **#FFADD8E6**. |
| static [get_LightCoral](./get_lightcoral/)() | Gets a system-defined color that has an ARGB value of **#FFF08080**. |
| static [get_LightCyan](./get_lightcyan/)() | Gets a system-defined color that has an ARGB value of **#FFE0FFFF**. |
| static [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Gets a system-defined color that has an ARGB value of **#FFFAFAD2**. |
| static [get_LightGray](./get_lightgray/)() | Gets a system-defined color that has an ARGB value of **#FFD3D3D3**. |
| static [get_LightGreen](./get_lightgreen/)() | Gets a system-defined color that has an ARGB value of **#FF90EE90**. |
| static [get_LightPink](./get_lightpink/)() | Gets a system-defined color that has an ARGB value of **#FFFFB6C1**. |
| static [get_LightSalmon](./get_lightsalmon/)() | Gets a system-defined color that has an ARGB value of **#FFFFA07A**. |
| static [get_LightSeaGreen](./get_lightseagreen/)() | Gets a system-defined color that has an ARGB value of **#FF20B2AA**. |
| static [get_LightSkyBlue](./get_lightskyblue/)() | Gets a system-defined color that has an ARGB value of **#FF87CEFA**. |
| static [get_LightSlateGray](./get_lightslategray/)() | Gets a system-defined color that has an ARGB value of **#FF778899**. |
| static [get_LightSteelBlue](./get_lightsteelblue/)() | Gets a system-defined color that has an ARGB value of **#FFB0C4DE**. |
| static [get_LightYellow](./get_lightyellow/)() | Gets a system-defined color that has an ARGB value of **#FFFFFFE0**. |
| static [get_Lime](./get_lime/)() | Gets a system-defined color that has an ARGB value of **#FF00FF00**. |
| static [get_LimeGreen](./get_limegreen/)() | Gets a system-defined color that has an ARGB value of **#FF32CD32**. |
| static [get_Linen](./get_linen/)() | Gets a system-defined color that has an ARGB value of **#FFFAF0E6**. |
| static [get_Magenta](./get_magenta/)() | Gets a system-defined color that has an ARGB value of **#FFFF00FF**. |
| static [get_Maroon](./get_maroon/)() | Gets a system-defined color that has an ARGB value of **#FF800000**. |
| static [get_MediumAquamarine](./get_mediumaquamarine/)() | Gets a system-defined color that has an ARGB value of **#FF66CDAA**. |
| static [get_MediumBlue](./get_mediumblue/)() | Gets a system-defined color that has an ARGB value of **#FF0000CD**. |
| static [get_MediumOrchid](./get_mediumorchid/)() | Gets a system-defined color that has an ARGB value of **#FFBA55D3**. |
| static [get_MediumPurple](./get_mediumpurple/)() | Gets a system-defined color that has an ARGB value of **#FF9370DB**. |
| static [get_MediumSeaGreen](./get_mediumseagreen/)() | Gets a system-defined color that has an ARGB value of **#FF3CB371**. |
| static [get_MediumSlateBlue](./get_mediumslateblue/)() | Gets a system-defined color that has an ARGB value of **#FF7B68EE**. |
| static [get_MediumSpringGreen](./get_mediumspringgreen/)() | Gets a system-defined color that has an ARGB value of **#FF00FA9A**. |
| static [get_MediumTurquoise](./get_mediumturquoise/)() | Gets a system-defined color that has an ARGB value of **#FF48D1CC**. |
| static [get_MediumVioletRed](./get_mediumvioletred/)() | Gets a system-defined color that has an ARGB value of **#FFC71585**. |
| static [get_MidnightBlue](./get_midnightblue/)() | Gets a system-defined color that has an ARGB value of **#FF191970**. |
| static [get_MintCream](./get_mintcream/)() | Gets a system-defined color that has an ARGB value of **#FFF5FFFA**. |
| static [get_MistyRose](./get_mistyrose/)() | Gets a system-defined color that has an ARGB value of **#FFFFE4E1**. |
| static [get_Moccasin](./get_moccasin/)() | Gets a system-defined color that has an ARGB value of **#FFFFE4B5**. |
| static [get_NavajoWhite](./get_navajowhite/)() | Gets a system-defined color that has an ARGB value of **#FFFFDEAD**. |
| static [get_Navy](./get_navy/)() | Gets a system-defined color that has an ARGB value of **#FF000080**. |
| static [get_OldLace](./get_oldlace/)() | Gets a system-defined color that has an ARGB value of **#FFFDF5E6**. |
| static [get_Olive](./get_olive/)() | Gets a system-defined color that has an ARGB value of **#FF808000**. |
| static [get_OliveDrab](./get_olivedrab/)() | Gets a system-defined color that has an ARGB value of **#FF6B8E23**. |
| static [get_Orange](./get_orange/)() | Gets a system-defined color that has an ARGB value of **#FFFFA500**. |
| static [get_OrangeRed](./get_orangered/)() | Gets a system-defined color that has an ARGB value of **#FFFF4500**. |
| static [get_Orchid](./get_orchid/)() | Gets a system-defined color that has an ARGB value of **#FFDA70D6**. |
| static [get_PaleGoldenrod](./get_palegoldenrod/)() | Gets a system-defined color that has an ARGB value of **#FFEEE8AA**. |
| static [get_PaleGreen](./get_palegreen/)() | Gets a system-defined color that has an ARGB value of **#FF98FB98**. |
| static [get_PaleTurquoise](./get_paleturquoise/)() | Gets a system-defined color that has an ARGB value of **#FFAFEEEE**. |
| static [get_PaleVioletRed](./get_palevioletred/)() | Gets a system-defined color that has an ARGB value of **#FFDB7093**. |
| static [get_PapayaWhip](./get_papayawhip/)() | Gets a system-defined color that has an ARGB value of **#FFFFEFD5**. |
| [get_PatternColorSpace](./get_patterncolorspace/)() const | Represents a object that indicates the pattern colorspace. |
| static [get_PeachPuff](./get_peachpuff/)() | Gets a system-defined color that has an ARGB value of **#FFFFDAB9**. |
| static [get_Peru](./get_peru/)() | Gets a system-defined color that has an ARGB value of **#FFCD853F**. |
| static [get_Pink](./get_pink/)() | Gets a system-defined color that has an ARGB value of **#FFFFC0CB**. |
| static [get_Plum](./get_plum/)() | Gets a system-defined color that has an ARGB value of **#FFDDA0DD**. |
| static [get_PowderBlue](./get_powderblue/)() | Gets a system-defined color that has an ARGB value of **#FFB0E0E6**. |
| static [get_Purple](./get_purple/)() | Gets a system-defined color that has an ARGB value of **#FF800080**. |
| static [get_Red](./get_red/)() | Gets a system-defined color that has an ARGB value of **#FFFF0000**. |
| static [get_RosyBrown](./get_rosybrown/)() | Gets a system-defined color that has an ARGB value of **#FFBC8F8F**. |
| static [get_RoyalBlue](./get_royalblue/)() | Gets a system-defined color that has an ARGB value of **#FF4169E1**. |
| static [get_SaddleBrown](./get_saddlebrown/)() | Gets a system-defined color that has an ARGB value of **#FF8B4513**. |
| static [get_Salmon](./get_salmon/)() | Gets a system-defined color that has an ARGB value of **#FFFA8072**. |
| static [get_SandyBrown](./get_sandybrown/)() | Gets a system-defined color that has an ARGB value of **#FFF4A460**. |
| static [get_SeaGreen](./get_seagreen/)() | Gets a system-defined color that has an ARGB value of **#FF2E8B57**. |
| static [get_SeaShell](./get_seashell/)() | Gets a system-defined color that has an ARGB value of **#FFFFF5EE**. |
| static [get_Sienna](./get_sienna/)() | Gets a system-defined color that has an ARGB value of **#FFA0522D**. |
| static [get_Silver](./get_silver/)() | Gets a system-defined color that has an ARGB value of **#FFC0C0C0**. |
| static [get_SkyBlue](./get_skyblue/)() | Gets a system-defined color that has an ARGB value of **#FF87CEEB**. |
| static [get_SlateBlue](./get_slateblue/)() | Gets a system-defined color that has an ARGB value of **#FF6A5ACD**. |
| static [get_SlateGray](./get_slategray/)() | Gets a system-defined color that has an ARGB value of **#FF708090**. |
| static [get_Snow](./get_snow/)() | Gets a system-defined color that has an ARGB value of **#FFFFFAFA**. |
| static [get_SpringGreen](./get_springgreen/)() | Gets a system-defined color that has an ARGB value of **#FF00FF7F**. |
| static [get_SteelBlue](./get_steelblue/)() | Gets a system-defined color that has an ARGB value of **#FF4682B4**. |
| static [get_Tan](./get_tan/)() | Gets a system-defined color that has an ARGB value of **#FFD2B48C**. |
| static [get_Teal](./get_teal/)() | Gets a system-defined color that has an ARGB value of **#FF008080**. |
| static [get_Thistle](./get_thistle/)() | Gets a system-defined color that has an ARGB value of **#FFD8BFD8**. |
| static [get_Tomato](./get_tomato/)() | Gets a system-defined color that has an ARGB value of **#FFFF6347**. |
| static [get_Transparent](./get_transparent/)() | Gets a system-defined color. |
| static [get_Turquoise](./get_turquoise/)() | Gets a system-defined color that has an ARGB value of **#FF40E0D0**. |
| static [get_Violet](./get_violet/)() | Gets a system-defined color that has an ARGB value of **#FFEE82EE**. |
| static [get_Wheat](./get_wheat/)() | Gets a system-defined color that has an ARGB value of **#FFF5DEB3**. |
| static [get_White](./get_white/)() | Gets a system-defined color that has an ARGB value of **#FFFFFFFF**. |
| static [get_WhiteSmoke](./get_whitesmoke/)() | Gets a system-defined color that has an ARGB value of **#FFF5F5F5**. |
| static [get_Yellow](./get_yellow/)() | Gets a system-defined color that has an ARGB value of **#FFFFFF00**. |
| static [get_YellowGreen](./get_yellowgreen/)() | Gets a system-defined color that has an ARGB value of **#FF9ACD32**. |
| static [Parse](./parse/)(System::String) | Extracts color components from the string. |
| [set_PatternColorSpace](./set_patterncolorspace/)(System::SharedPtr\<Aspose::Pdf::Drawing::PatternColorSpace\>) | Represents a object that indicates the pattern colorspace. |
| [ToRgb](./torgb/)() | Converts color into rgb. |
| [ToString](./tostring/)() const override | Converts to string. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Represents empty color. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
