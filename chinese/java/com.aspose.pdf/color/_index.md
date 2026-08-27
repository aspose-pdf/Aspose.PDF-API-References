---
title: "Color"
linktitle: "Color"
second_title: "Aspose.PDF for Java API 参考"
description: "表示可以在不同颜色空间中表达的颜色值类。"
type: docs
weight: 670
url: /zh/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

表示可以在不同颜色空间中表达的颜色值类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Default](#Default) | 表示默认颜色。 |
| [Empty](#Empty) | 表示空颜色。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Color](#Color--) | 默认构造函数。 |
| [Color](#Color-double:A-) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆此实例 |
| [equals](#equals-java.lang.Object-) | 如果两个颜色相等则返回 true。 |
| [fromArgb](#fromArgb-int-int-int-) | 从 RGB 颜色分量获取有效的 pdf Color 对象。 |
| [fromArgb](#fromArgb-int-int-int-int-) | 从 RGB 颜色分量获取有效的 pdf Color 对象。 |
| [fromCmyk](#fromCmyk-double-double-double-double-) | 从 CMYK 颜色分量获取有效的 pdf Color 对象。 |
| [fromGray](#fromGray-double-) | 从灰度颜色分量获取有效的 pdf Color 对象。 |
| [fromRgb](#fromRgb-java.awt.Color-) | 从 java.awt.Color 值获取有效的 pdf Color 对象。 |
| [fromRgb](#fromRgb-double-double-double-) | 从 RGB 颜色分量获取有效的 pdf Color 对象。 |
| [getA](#getA--) | 获取 alpha 分量值 |
| [getAliceBlue](#getAliceBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FFF0F8FF。 |
| [getAntiqueWhite](#getAntiqueWhite--) | 获取系统定义的颜色，其 ARGB 值为 #FFFAEBD7。 |
| [getAqua](#getAqua--) | 获取系统定义的颜色，其 ARGB 值为 #FF00FFFF。 |
| [getAquamarine](#getAquamarine--) | 获取系统定义的颜色，其 ARGB 值为 #FF7FFFD4。 |
| [getAzure](#getAzure--) | 获取系统定义的颜色，其 ARGB 值为 #FFF0FFFF。 |
| [getBeige](#getBeige--) | 获取系统定义的颜色，其 ARGB 值为 #FFF5F5DC。 |
| [getBisque](#getBisque--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFE4C4。 |
| [getBlack](#getBlack--) | 获取系统定义的颜色，其 ARGB 值为 #FF000000。 |
| [getBlanchedAlmond](#getBlanchedAlmond--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFEBCD。 |
| [getBlue](#getBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF0000FF。 |
| [getBlueViolet](#getBlueViolet--) | 获取系统定义的颜色，其 ARGB 值为 #FF8A2BE2。 |
| [getBrown](#getBrown--) | 获取系统定义的颜色，其 ARGB 值为 #FFA52A2A。 |
| [getBurlyWood](#getBurlyWood--) | 获取系统定义的颜色，其 ARGB 值为 #FFDEB887。 |
| [getCadetBlue](#getCadetBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF5F9EA0。 |
| [getChartreuse](#getChartreuse--) | 获取系统定义的颜色，其 ARGB 值为 #FF7FFF00。 |
| [getChocolate](#getChocolate--) | 获取系统定义的颜色，其 ARGB 值为 #FFD2691E。 |
| [getColorSpace](#getColorSpace--) | 获取颜色所表示的颜色空间。 |
| [getCoral](#getCoral--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF7F50。 |
| [getCornflowerBlue](#getCornflowerBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF6495ED. |
| [getCornsilk](#getCornsilk--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFF8DC. |
| [getCrimson](#getCrimson--) | 获取系统定义的颜色，其 ARGB 值为 #FFDC143C. |
| [getCyan](#getCyan--) | 获取系统定义的颜色，其 ARGB 值为 #FF00FFFF。 |
| [getDarkBlue](#getDarkBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF00008B. |
| [getDarkCyan](#getDarkCyan--) | 获取系统定义的颜色，其 ARGB 值为 #FF008B8B. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | 获取系统定义的颜色，其 ARGB 值为 #FFB8860B. |
| [getDarkGray](#getDarkGray--) | 获取系统定义的颜色，其 ARGB 值为 #FFA9A9A9. |
| [getDarkGreen](#getDarkGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF006400. |
| [getDarkKhaki](#getDarkKhaki--) | 获取系统定义的颜色，其 ARGB 值为 #FFBDB76B. |
| [getDarkMagenta](#getDarkMagenta--) | 获取系统定义的颜色，其 ARGB 值为 #FF8B008B. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF556B2F. |
| [getDarkOrange](#getDarkOrange--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | 获取系统定义的颜色，其 ARGB 值为 #FF9932CC. |
| [getDarkRed](#getDarkRed--) | 获取系统定义的颜色，其 ARGB 值为 #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | 获取系统定义的颜色，其 ARGB 值为 #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | 获取系统定义的颜色，其 ARGB 值为 #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | 获取系统定义的颜色，其 ARGB 值为 #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | 获取系统定义的颜色，其 ARGB 值为 #FF9400D3. |
| [getData](#getData--) | 颜色值. |
| [getDeepPink](#getDeepPink--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF00BFFF. |
| [getDimGray](#getDimGray--) | 获取系统定义的颜色，其 ARGB 值为 #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | 获取系统定义的颜色，其 ARGB 值为 #FFB22222。 |
| [getFloralWhite](#getFloralWhite--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFFAF0。 |
| [getForestGreen](#getForestGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF228B22。 |
| [getFuchsia](#getFuchsia--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF00FF。 |
| [getGainsboro](#getGainsboro--) | 获取系统定义的颜色，其 ARGB 值为 #FFDCDCDC。 |
| [getGhostWhite](#getGhostWhite--) | 获取系统定义的颜色，其 ARGB 值为 #FFF8F8FF。 |
| [getGold](#getGold--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFD700。 |
| [getGoldenrod](#getGoldenrod--) | 获取系统定义的颜色，其 ARGB 值为 #FFDAA520。 |
| [getGray](#getGray--) | 获取系统定义的颜色，其 ARGB 值为 #FF808080。 |
| [getGreen](#getGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF008000。 |
| [getGreenYellow](#getGreenYellow--) | 获取系统定义的颜色，其 ARGB 值为 #FFADFF2F。 |
| [getHoneydew](#getHoneydew--) | 获取系统定义的颜色，其 ARGB 值为 #FFF0FFF0。 |
| [getHotPink](#getHotPink--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF69B4。 |
| [getIndianRed](#getIndianRed--) | 获取系统定义的颜色，其 ARGB 值为 #FFCD5C5C。 |
| [getIndigo](#getIndigo--) | 获取系统定义的颜色，其 ARGB 值为 #FF4B0082。 |
| [getIvory](#getIvory--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFFFF0。 |
| [getKhaki](#getKhaki--) | 获取系统定义的颜色，其 ARGB 值为 #FFF0E68C。 |
| [getLavender](#getLavender--) | 获取系统定义的颜色，其 ARGB 值为 #FFE6E6FA。 |
| [getLavenderBlush](#getLavenderBlush--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFF0F5。 |
| [getLawnGreen](#getLawnGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF7CFC00。 |
| [getLemonChiffon](#getLemonChiffon--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFFACD。 |
| [getLightBlue](#getLightBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FFADD8E6。 |
| [getLightCoral](#getLightCoral--) | 获取系统定义的颜色，其 ARGB 值为 #FFF08080。 |
| [getLightCyan](#getLightCyan--) | 获取系统定义的颜色，其 ARGB 值为 #FFE0FFFF。 |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | 获取系统定义的颜色，其 ARGB 值为 #FFFAFAD2。 |
| [getLightGray](#getLightGray--) | 获取系统定义的颜色，其 ARGB 值为 #FFD3D3D3。 |
| [getLightGreen](#getLightGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF90EE90。 |
| [getLightPink](#getLightPink--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFB6C1。 |
| [getLightSalmon](#getLightSalmon--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFA07A。 |
| [getLightSeaGreen](#getLightSeaGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF20B2AA。 |
| [getLightSkyBlue](#getLightSkyBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF87CEFA。 |
| [getLightSlateGray](#getLightSlateGray--) | 获取系统定义的颜色，其 ARGB 值为 #FF778899。 |
| [getLightSteelBlue](#getLightSteelBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FFB0C4DE。 |
| [getLightYellow](#getLightYellow--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFFFE0。 |
| [getLime](#getLime--) | 获取系统定义的颜色，其 ARGB 值为 #FF00FF00。 |
| [getLimeGreen](#getLimeGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF32CD32。 |
| [getLinen](#getLinen--) | 获取系统定义的颜色，其 ARGB 值为 #FFFAF0E6。 |
| [getMagenta](#getMagenta--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF00FF。 |
| [getMaroon](#getMaroon--) | 获取系统定义的颜色，其 ARGB 值为 #FF800000。 |
| [getMediumAquamarine](#getMediumAquamarine--) | 获取系统定义的颜色，其 ARGB 值为 #FF66CDAA。 |
| [getMediumBlue](#getMediumBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF0000CD。 |
| [getMediumOrchid](#getMediumOrchid--) | 获取系统定义的颜色，其 ARGB 值为 #FFBA55D3。 |
| [getMediumPurple](#getMediumPurple--) | 获取系统定义的颜色，其 ARGB 值为 #FF9370DB。 |
| [getMediumSeaGreen](#getMediumSeaGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF3CB371。 |
| [getMediumSlateBlue](#getMediumSlateBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF7B68EE。 |
| [getMediumSpringGreen](#getMediumSpringGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF00FA9A。 |
| [getMediumTurquoise](#getMediumTurquoise--) | 获取系统定义的颜色，其 ARGB 值为 #FF48D1CC。 |
| [getMediumVioletRed](#getMediumVioletRed--) | 获取系统定义的颜色，其 ARGB 值为 #FFC71585。 |
| [getMidnightBlue](#getMidnightBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF191970。 |
| [getMintCream](#getMintCream--) | 获取系统定义的颜色，其 ARGB 值为 #FFF5FFFA。 |
| [getMistyRose](#getMistyRose--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFE4E1。 |
| [getMoccasin](#getMoccasin--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFE4B5。 |
| [getNavajoWhite](#getNavajoWhite--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFDEAD。 |
| [getNavy](#getNavy--) | 获取系统定义的颜色，其 ARGB 值为 #FF000080。 |
| [getOldLace](#getOldLace--) | 获取系统定义的颜色，其 ARGB 值为 #FFFDF5E6。 |
| [getOlive](#getOlive--) | 获取系统定义的颜色，其 ARGB 值为 #FF808000。 |
| [getOliveDrab](#getOliveDrab--) | 获取系统定义的颜色，其 ARGB 值为 #FF6B8E23。 |
| [getOrange](#getOrange--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFA500。 |
| [getOrangeRed](#getOrangeRed--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF4500。 |
| [getOrchid](#getOrchid--) | 获取系统定义的颜色，其 ARGB 值为 #FFDA70D6。 |
| [getPaleGoldenrod](#getPaleGoldenrod--) | 获取系统定义的颜色，其 ARGB 值为 #FFEEE8AA。 |
| [getPaleGreen](#getPaleGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF98FB98。 |
| [getPaleTurquoise](#getPaleTurquoise--) | 获取系统定义的颜色，其 ARGB 值为 #FFAFEEEE。 |
| [getPaleVioletRed](#getPaleVioletRed--) | 获取系统定义的颜色，其 ARGB 值为 #FFDB7093。 |
| [getPapayaWhip](#getPapayaWhip--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFEFD5。 |
| [getPatternColorSpace](#getPatternColorSpace--) | 获取一个指示图案颜色空间的对象。仅供内部使用。 |
| [getPeachPuff](#getPeachPuff--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFDAB9。 |
| [getPeru](#getPeru--) | 获取系统定义的颜色，其 ARGB 值为 #FFCD853F。 |
| [getPink](#getPink--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFC0CB。 |
| [getPlum](#getPlum--) | 获取系统定义的颜色，其 ARGB 值为 #FFDDA0DD。 |
| [getPowderBlue](#getPowderBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FFB0E0E6。 |
| [getPurple](#getPurple--) | 获取系统定义的颜色，其 ARGB 值为 #FF800080。 |
| [getRed](#getRed--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF0000。 |
| [getRosyBrown](#getRosyBrown--) | 获取系统定义的颜色，其 ARGB 值为 #FFBC8F8F。 |
| [getRoyalBlue](#getRoyalBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF4169E1。 |
| [getSaddleBrown](#getSaddleBrown--) | 获取系统定义的颜色，其 ARGB 值为 #FF8B4513。 |
| [getSalmon](#getSalmon--) | 获取系统定义的颜色，其 ARGB 值为 #FFFA8072。 |
| [getSandyBrown](#getSandyBrown--) | 获取系统定义的颜色，其 ARGB 值为 #FFF4A460。 |
| [getSeaGreen](#getSeaGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF2E8B57。 |
| [getSeaShell](#getSeaShell--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFF5EE。 |
| [getSienna](#getSienna--) | 获取系统定义的颜色，其 ARGB 值为 #FFA0522D。 |
| [getSilver](#getSilver--) | 获取系统定义的颜色，其 ARGB 值为 #FFC0C0C0。 |
| [getSkyBlue](#getSkyBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF87CEEB。 |
| [getSlateBlue](#getSlateBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF6A5ACD。 |
| [getSlateGray](#getSlateGray--) | 获取系统定义的颜色，其 ARGB 值为 #FF708090。 |
| [getSnow](#getSnow--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFFAFA。 |
| [getSpringGreen](#getSpringGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF00FF7F。 |
| [getSteelBlue](#getSteelBlue--) | 获取系统定义的颜色，其 ARGB 值为 #FF4682B4。 |
| [getTan](#getTan--) | 获取系统定义的颜色，其 ARGB 值为 #FFD2B48C。 |
| [getTeal](#getTeal--) | 获取系统定义的颜色，其 ARGB 值为 #FF008080。 |
| [getThistle](#getThistle--) | 获取系统定义的颜色，其 ARGB 值为 #FFD8BFD8。 |
| [getTomato](#getTomato--) | 获取系统定义的颜色，其 ARGB 值为 #FFFF6347。 |
| [getTransparent](#getTransparent--) | 获取系统定义的颜色。 |
| [getTurquoise](#getTurquoise--) | 获取系统定义的颜色，其 ARGB 值为 #FF40E0D0。 |
| [getViolet](#getViolet--) | 获取系统定义的颜色，其 ARGB 值为 #FFEE82EE。 |
| [getWheat](#getWheat--) | 获取系统定义的颜色，其 ARGB 值为 #FFF5DEB3。 |
| [getWhite](#getWhite--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFFFFF。 |
| [getWhiteSmoke](#getWhiteSmoke--) | 获取系统定义的颜色，其 ARGB 值为 #FFF5F5F5。 |
| [getYellow](#getYellow--) | 获取系统定义的颜色，其 ARGB 值为 #FFFFFF00。 |
| [getYellowGreen](#getYellowGreen--) | 获取系统定义的颜色，其 ARGB 值为 #FF9ACD32。 |
| [hashCode](#hashCode--) | 返回对象的哈希码值。此方法支持哈希表（例如 {@link java.util.HashMap} 提供的哈希表）。<p> {@code hashCode} 的一般约定是：<ul> <li>在 Java 应用程序的执行期间，如果在同一对象上多次调用，它必须始终返回相同的整数，前提是未修改用于 {@code equals} 比较的任何信息。该整数在不同的应用程序执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 {@code hashCode} 方法必须产生不同的整数结果。然而，程序员应注意，为不相等的对象产生不同的整数结果可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，由类 {@code Object} 定义的 hashCode 方法确实会为不同的对象返回不同的整数。（通常通过将对象的内部地址转换为整数来实现，但 Java<span style=\"font-size:70%\"><sup>TM</sup></span>编程语言并未要求使用此实现技术。） |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | 如果两个颜色相等则返回 true。 |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | 如果两个颜色不相等，则返回 true。 |
| [parse](#parse-java.lang.String-) | 从字符串中提取颜色分量。 |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | 设置指示模式颜色空间的对象。仅供内部使用 |
| [toRgb](#toRgb--) | 将颜色转换为 rgb。 |
| [toString](#toString--) | 转换为字符串。 |

### Default {#Default}
```
public static final Color Default
```

表示默认颜色。

### Empty {#Empty}
```
public static final Color Empty
```

表示空颜色。

### Color {#Color--}
```
public Color()
```

默认构造函数。

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 向量 |  | double[] 数组 |

### deepClone {#deepClone--}
```
public Color deepClone()
```

克隆此实例

**Returns:**
Color 对象

### equals {#equals-java.lang.Object-}
如果两个颜色相等则返回 true。

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

从 RGB 颜色分量获取有效的 pdf Color 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r |  | 红色分量 (值 0 - 255)。 |
| g |  | 绿色分量 (值 0 - 255)。 |
| b |  | 蓝色分量 (值 0 - 255)。 |

**Returns:**
颜色对象，每个分量的值在 [0..255] 范围内。

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

从 RGB 颜色分量获取有效的 pdf Color 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a |  | alpha 分量值 (值 0 - 255)。 |
| r |  | 红色分量 (值 0 - 255)。 |
| g |  | 绿色分量 (值 0 - 255)。 |
| b |  | 蓝色分量 (值 0 - 255)。 |

**Returns:**
颜色对象，每个分量的值在 [0..255] 范围内。

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

从 CMYK 颜色分量获取有效的 pdf Color 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c |  | 青色分量 (值 0 - 1)。 |
| m |  | 品红色分量 (值 0 - 1)。 |
| y |  | 黄色分量 (值 0 - 1)。 |
| k |  | 黑色分量 (值 0 - 1)。 |

**Returns:**
颜色对象，每个分量的值在 [0..1] 范围内。

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

从灰度颜色分量获取有效的 pdf Color 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| g |  | 灰色分量（值 0 - 1）。 |

**Returns:**
颜色对象，每个分量的值在 [0..1] 范围内。

### fromRgb {#fromRgb-java.awt.Color-}
从 java.awt.Color 值获取有效的 pdf Color 对象。

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

从 RGB 颜色分量获取有效的 pdf Color 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r |  | 红色分量（值 0 - 1）。 |
| g |  | 绿色分量（值 0 - 1）。 |
| b |  | 蓝色分量（值 0 - 1）。 |

**Returns:**
颜色对象，每个分量的值在 [0..1] 范围内。

### getA {#getA--}
```
public double getA()
```

获取 alpha 分量值

**Returns:**
double 值

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FFF0F8FF。

**Returns:**
A 表示系统定义的颜色。

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

获取系统定义的颜色，其 ARGB 值为 #FFFAEBD7。

**Returns:**
A 表示系统定义的颜色。

### getAqua {#getAqua--}
```
public static Color getAqua()
```

获取系统定义的颜色，其 ARGB 值为 #FF00FFFF。

**Returns:**
A 表示系统定义的颜色。

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

获取系统定义的颜色，其 ARGB 值为 #FF7FFFD4。

**Returns:**
A 表示系统定义的颜色。

### getAzure {#getAzure--}
```
public static Color getAzure()
```

获取系统定义的颜色，其 ARGB 值为 #FFF0FFFF。

**Returns:**
A 表示系统定义的颜色。

### getBeige {#getBeige--}
```
public static Color getBeige()
```

获取系统定义的颜色，其 ARGB 值为 #FFF5F5DC。

**Returns:**
A 表示系统定义的颜色。

### getBisque {#getBisque--}
```
public static Color getBisque()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFE4C4。

**Returns:**
A 表示系统定义的颜色。

### getBlack {#getBlack--}
```
public static Color getBlack()
```

获取系统定义的颜色，其 ARGB 值为 #FF000000。

**Returns:**
A 表示系统定义的颜色。

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFEBCD。

**Returns:**
A 表示系统定义的颜色。

### getBlue {#getBlue--}
```
public static Color getBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF0000FF。

**Returns:**
A 表示系统定义的颜色。

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

获取系统定义的颜色，其 ARGB 值为 #FF8A2BE2。

**Returns:**
A 表示系统定义的颜色。

### getBrown {#getBrown--}
```
public static Color getBrown()
```

获取系统定义的颜色，其 ARGB 值为 #FFA52A2A。

**Returns:**
A 表示系统定义的颜色。

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

获取系统定义的颜色，其 ARGB 值为 #FFDEB887。

**Returns:**
A 表示系统定义的颜色。

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF5F9EA0。

**Returns:**
A 表示系统定义的颜色。

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

获取系统定义的颜色，其 ARGB 值为 #FF7FFF00。

**Returns:**
A 表示系统定义的颜色。

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

获取系统定义的颜色，其 ARGB 值为 #FFD2691E。

**Returns:**
A 表示系统定义的颜色。

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

获取颜色所表示的颜色空间。

**Returns:**
ColorSpace 对象

### getCoral {#getCoral--}
```
public static Color getCoral()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF7F50。

**Returns:**
A 表示系统定义的颜色。

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF6495ED.

**Returns:**
A 表示系统定义的颜色。

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFF8DC.

**Returns:**
A 表示系统定义的颜色。

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

获取系统定义的颜色，其 ARGB 值为 #FFDC143C.

**Returns:**
A 表示系统定义的颜色。

### getCyan {#getCyan--}
```
public static Color getCyan()
```

获取系统定义的颜色，其 ARGB 值为 #FF00FFFF。

**Returns:**
A 表示系统定义的颜色。

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF00008B.

**Returns:**
A 表示系统定义的颜色。

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

获取系统定义的颜色，其 ARGB 值为 #FF008B8B.

**Returns:**
A 表示系统定义的颜色。

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

获取系统定义的颜色，其 ARGB 值为 #FFB8860B.

**Returns:**
A 表示系统定义的颜色。

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

获取系统定义的颜色，其 ARGB 值为 #FFA9A9A9.

**Returns:**
A 表示系统定义的颜色。

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF006400.

**Returns:**
A 表示系统定义的颜色。

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

获取系统定义的颜色，其 ARGB 值为 #FFBDB76B.

**Returns:**
A 表示系统定义的颜色。

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

获取系统定义的颜色，其 ARGB 值为 #FF8B008B.

**Returns:**
A 表示系统定义的颜色。

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF556B2F.

**Returns:**
A 表示系统定义的颜色。

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF8C00.

**Returns:**
A 表示系统定义的颜色。

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

获取系统定义的颜色，其 ARGB 值为 #FF9932CC.

**Returns:**
A 表示系统定义的颜色。

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

获取系统定义的颜色，其 ARGB 值为 #FF8B0000.

**Returns:**
A 表示系统定义的颜色。

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

获取系统定义的颜色，其 ARGB 值为 #FFE9967A.

**Returns:**
A 表示系统定义的颜色。

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF8FBC8F.

**Returns:**
A 表示系统定义的颜色。

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF483D8B.

**Returns:**
A 表示系统定义的颜色。

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

获取系统定义的颜色，其 ARGB 值为 #FF2F4F4F.

**Returns:**
A 表示系统定义的颜色。

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

获取系统定义的颜色，其 ARGB 值为 #FF00CED1.

**Returns:**
A 表示系统定义的颜色。

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

获取系统定义的颜色，其 ARGB 值为 #FF9400D3.

**Returns:**
A 表示系统定义的颜色。

### getData {#getData--}
```
public double[] getData()
```

颜色值.

**Returns:**
double 值数组

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF1493.

**Returns:**
A 表示系统定义的颜色。

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF00BFFF.

**Returns:**
A 表示系统定义的颜色。

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

获取系统定义的颜色，其 ARGB 值为 #FF696969.

**Returns:**
A 表示系统定义的颜色。

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF1E90FF.

**Returns:**
A 表示系统定义的颜色。

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

获取系统定义的颜色，其 ARGB 值为 #FFB22222。

**Returns:**
A 表示系统定义的颜色。

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFFAF0。

**Returns:**
A 表示系统定义的颜色。

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF228B22。

**Returns:**
A 表示系统定义的颜色。

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF00FF。

**Returns:**
A 表示系统定义的颜色。

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

获取系统定义的颜色，其 ARGB 值为 #FFDCDCDC。

**Returns:**
A 表示系统定义的颜色。

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

获取系统定义的颜色，其 ARGB 值为 #FFF8F8FF。

**Returns:**
A 表示系统定义的颜色。

### getGold {#getGold--}
```
public static Color getGold()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFD700。

**Returns:**
A 表示系统定义的颜色。

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

获取系统定义的颜色，其 ARGB 值为 #FFDAA520。

**Returns:**
A 表示系统定义的颜色。

### getGray {#getGray--}
```
public static Color getGray()
```

获取系统定义的颜色，其 ARGB 值为 #FF808080。

**Returns:**
A 表示系统定义颜色的结构。

### getGreen {#getGreen--}
```
public static Color getGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF008000。

**Returns:**
A 表示系统定义的颜色。

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

获取系统定义的颜色，其 ARGB 值为 #FFADFF2F。

**Returns:**
A 表示系统定义的颜色。

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

获取系统定义的颜色，其 ARGB 值为 #FFF0FFF0。

**Returns:**
A 表示系统定义的颜色。

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF69B4。

**Returns:**
A 表示系统定义的颜色。

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

获取系统定义的颜色，其 ARGB 值为 #FFCD5C5C。

**Returns:**
A 表示系统定义的颜色。

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

获取系统定义的颜色，其 ARGB 值为 #FF4B0082。

**Returns:**
A 表示系统定义的颜色。

### getIvory {#getIvory--}
```
public static Color getIvory()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFFFF0。

**Returns:**
A 表示系统定义的颜色。

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

获取系统定义的颜色，其 ARGB 值为 #FFF0E68C。

**Returns:**
A 表示系统定义的颜色。

### getLavender {#getLavender--}
```
public static Color getLavender()
```

获取系统定义的颜色，其 ARGB 值为 #FFE6E6FA。

**Returns:**
A 表示系统定义的颜色。

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFF0F5。

**Returns:**
A 表示系统定义的颜色。

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF7CFC00。

**Returns:**
A 表示系统定义的颜色。

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFFACD。

**Returns:**
A 表示系统定义的颜色。

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FFADD8E6。

**Returns:**
A 表示系统定义的颜色。

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

获取系统定义的颜色，其 ARGB 值为 #FFF08080。

**Returns:**
A 表示系统定义的颜色。

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

获取系统定义的颜色，其 ARGB 值为 #FFE0FFFF。

**Returns:**
A 表示系统定义的颜色。

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

获取系统定义的颜色，其 ARGB 值为 #FFFAFAD2。

**Returns:**
A 表示系统定义的颜色。

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

获取系统定义的颜色，其 ARGB 值为 #FFD3D3D3。

**Returns:**
A 表示系统定义的颜色。

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF90EE90。

**Returns:**
A 表示系统定义的颜色。

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFB6C1。

**Returns:**
A 表示系统定义的颜色。

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFA07A。

**Returns:**
A 表示系统定义的颜色。

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF20B2AA。

**Returns:**
A 表示系统定义的颜色。

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF87CEFA。

**Returns:**
A 表示系统定义的颜色。

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

获取系统定义的颜色，其 ARGB 值为 #FF778899。

**Returns:**
A 表示系统定义的颜色。

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FFB0C4DE。

**Returns:**
A 表示系统定义的颜色。

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFFFE0。

**Returns:**
A 表示系统定义的颜色。

### getLime {#getLime--}
```
public static Color getLime()
```

获取系统定义的颜色，其 ARGB 值为 #FF00FF00。

**Returns:**
A 表示系统定义的颜色。

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF32CD32。

**Returns:**
A 表示系统定义的颜色。

### getLinen {#getLinen--}
```
public static Color getLinen()
```

获取系统定义的颜色，其 ARGB 值为 #FFFAF0E6。

**Returns:**
A 表示系统定义的颜色。

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF00FF。

**Returns:**
A 表示系统定义的颜色。

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

获取系统定义的颜色，其 ARGB 值为 #FF800000。

**Returns:**
A 表示系统定义的颜色。

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

获取系统定义的颜色，其 ARGB 值为 #FF66CDAA。

**Returns:**
A 表示系统定义的颜色。

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF0000CD。

**Returns:**
A 表示系统定义的颜色。

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

获取系统定义的颜色，其 ARGB 值为 #FFBA55D3。

**Returns:**
A 表示系统定义的颜色。

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

获取系统定义的颜色，其 ARGB 值为 #FF9370DB。

**Returns:**
A 表示系统定义的颜色。

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF3CB371。

**Returns:**
A 表示系统定义的颜色。

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF7B68EE。

**Returns:**
A 表示系统定义的颜色。

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF00FA9A。

**Returns:**
A 表示系统定义的颜色。

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

获取系统定义的颜色，其 ARGB 值为 #FF48D1CC。

**Returns:**
A 表示系统定义的颜色。

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

获取系统定义的颜色，其 ARGB 值为 #FFC71585。

**Returns:**
A 表示系统定义的颜色。

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF191970。

**Returns:**
A 表示系统定义的颜色。

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

获取系统定义的颜色，其 ARGB 值为 #FFF5FFFA。

**Returns:**
A 表示系统定义的颜色。

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFE4E1。

**Returns:**
A 表示系统定义的颜色。

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFE4B5。

**Returns:**
A 表示系统定义的颜色。

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFDEAD。

**Returns:**
A 表示系统定义的颜色。

### getNavy {#getNavy--}
```
public static Color getNavy()
```

获取系统定义的颜色，其 ARGB 值为 #FF000080。

**Returns:**
A 表示系统定义的颜色。

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

获取系统定义的颜色，其 ARGB 值为 #FFFDF5E6。

**Returns:**
A 表示系统定义的颜色。

### getOlive {#getOlive--}
```
public static Color getOlive()
```

获取系统定义的颜色，其 ARGB 值为 #FF808000。

**Returns:**
A 表示系统定义的颜色。

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

获取系统定义的颜色，其 ARGB 值为 #FF6B8E23。

**Returns:**
A 表示系统定义的颜色。

### getOrange {#getOrange--}
```
public static Color getOrange()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFA500。

**Returns:**
A 表示系统定义的颜色。

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF4500。

**Returns:**
A 表示系统定义的颜色。

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

获取系统定义的颜色，其 ARGB 值为 #FFDA70D6。

**Returns:**
A 表示系统定义的颜色。

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

获取系统定义的颜色，其 ARGB 值为 #FFEEE8AA。

**Returns:**
A 表示系统定义的颜色。

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF98FB98。

**Returns:**
A 表示系统定义的颜色。

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

获取系统定义的颜色，其 ARGB 值为 #FFAFEEEE。

**Returns:**
A 表示系统定义的颜色。

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

获取系统定义的颜色，其 ARGB 值为 #FFDB7093。

**Returns:**
A 表示系统定义的颜色。

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFEFD5。

**Returns:**
A 表示系统定义的颜色。

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

获取一个指示图案颜色空间的对象。仅供内部使用。

**Returns:**
PatternColorSpace 对象

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFDAB9。

**Returns:**
A 表示系统定义的颜色。

### getPeru {#getPeru--}
```
public static Color getPeru()
```

获取系统定义的颜色，其 ARGB 值为 #FFCD853F。

**Returns:**
A 表示系统定义的颜色。

### getPink {#getPink--}
```
public static Color getPink()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFC0CB。

**Returns:**
A 表示系统定义的颜色。

### getPlum {#getPlum--}
```
public static Color getPlum()
```

获取系统定义的颜色，其 ARGB 值为 #FFDDA0DD。

**Returns:**
A 表示系统定义的颜色。

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FFB0E0E6。

**Returns:**
A 表示系统定义的颜色。

### getPurple {#getPurple--}
```
public static Color getPurple()
```

获取系统定义的颜色，其 ARGB 值为 #FF800080。

**Returns:**
A 表示系统定义的颜色。

### getRed {#getRed--}
```
public static Color getRed()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF0000。

**Returns:**
A 表示系统定义的颜色。

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

获取系统定义的颜色，其 ARGB 值为 #FFBC8F8F。

**Returns:**
A 表示系统定义的颜色。

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF4169E1。

**Returns:**
A 表示系统定义的颜色。

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

获取系统定义的颜色，其 ARGB 值为 #FF8B4513。

**Returns:**
A 表示系统定义的颜色。

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

获取系统定义的颜色，其 ARGB 值为 #FFFA8072。

**Returns:**
A 表示系统定义的颜色。

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

获取系统定义的颜色，其 ARGB 值为 #FFF4A460。

**Returns:**
A 表示系统定义的颜色。

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF2E8B57。

**Returns:**
A 表示系统定义的颜色。

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFF5EE。

**Returns:**
A 表示系统定义的颜色。

### getSienna {#getSienna--}
```
public static Color getSienna()
```

获取系统定义的颜色，其 ARGB 值为 #FFA0522D。

**Returns:**
A 表示系统定义的颜色。

### getSilver {#getSilver--}
```
public static Color getSilver()
```

获取系统定义的颜色，其 ARGB 值为 #FFC0C0C0。

**Returns:**
A 表示系统定义的颜色。

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF87CEEB。

**Returns:**
A 表示系统定义的颜色。

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF6A5ACD。

**Returns:**
A 表示系统定义的颜色。

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

获取系统定义的颜色，其 ARGB 值为 #FF708090。

**Returns:**
A 表示系统定义的颜色。

### getSnow {#getSnow--}
```
public static Color getSnow()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFFAFA。

**Returns:**
A 表示系统定义的颜色。

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF00FF7F。

**Returns:**
A 表示系统定义的颜色。

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

获取系统定义的颜色，其 ARGB 值为 #FF4682B4。

**Returns:**
A 表示系统定义的颜色。

### getTan {#getTan--}
```
public static Color getTan()
```

获取系统定义的颜色，其 ARGB 值为 #FFD2B48C。

**Returns:**
A 表示系统定义的颜色。

### getTeal {#getTeal--}
```
public static Color getTeal()
```

获取系统定义的颜色，其 ARGB 值为 #FF008080。

**Returns:**
A 表示系统定义的颜色。

### getThistle {#getThistle--}
```
public static Color getThistle()
```

获取系统定义的颜色，其 ARGB 值为 #FFD8BFD8。

**Returns:**
A 表示系统定义的颜色。

### getTomato {#getTomato--}
```
public static Color getTomato()
```

获取系统定义的颜色，其 ARGB 值为 #FFFF6347。

**Returns:**
A 表示系统定义的颜色。

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

获取系统定义的颜色。

**Returns:**
A 表示系统定义的颜色。

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

获取系统定义的颜色，其 ARGB 值为 #FF40E0D0。

**Returns:**
A 表示系统定义的颜色。

### getViolet {#getViolet--}
```
public static Color getViolet()
```

获取系统定义的颜色，其 ARGB 值为 #FFEE82EE。

**Returns:**
A 表示系统定义的颜色。

### getWheat {#getWheat--}
```
public static Color getWheat()
```

获取系统定义的颜色，其 ARGB 值为 #FFF5DEB3。

**Returns:**
A 表示系统定义的颜色。

### getWhite {#getWhite--}
```
public static Color getWhite()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFFFFF。

**Returns:**
A 表示系统定义的颜色。

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

获取系统定义的颜色，其 ARGB 值为 #FFF5F5F5。

**Returns:**
A 表示系统定义的颜色。

### getYellow {#getYellow--}
```
public static Color getYellow()
```

获取系统定义的颜色，其 ARGB 值为 #FFFFFF00。

**Returns:**
A 表示系统定义的颜色。

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

获取系统定义的颜色，其 ARGB 值为 #FF9ACD32。

**Returns:**
A 表示系统定义的颜色。

### hashCode {#hashCode--}
```
public int hashCode()
```

返回对象的哈希码值。此方法支持哈希表（例如 {@link java.util.HashMap} 提供的哈希表）。<p> {@code hashCode} 的一般约定是：<ul> <li>在 Java 应用程序的执行期间，如果在同一对象上多次调用，它必须始终返回相同的整数，前提是未修改用于 {@code equals} 比较的任何信息。该整数在不同的应用程序执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 {@code hashCode} 方法必须产生不同的整数结果。然而，程序员应注意，为不相等的对象产生不同的整数结果可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，由类 {@code Object} 定义的 hashCode 方法确实会为不同的对象返回不同的整数。（通常通过将对象的内部地址转换为整数来实现，但 Java<span style=\"font-size:70%\"><sup>TM</sup></span>编程语言并未要求使用此实现技术。）

**Returns:**
此对象的哈希码值。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
如果两个颜色相等则返回 true。

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
如果两个颜色不相等，则返回 true。

### parse {#parse-java.lang.String-}
从字符串中提取颜色分量。

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
设置指示模式颜色空间的对象。仅供内部使用

### toRgb {#toRgb--}
```
public Color toRgb()
```

将颜色转换为 rgb。

**Returns:**
Rgb 颜色值。

### toString {#toString--}
```
public String toString()
```

转换为字符串。

**Returns:**
Color 对象的字符串表示形式。
