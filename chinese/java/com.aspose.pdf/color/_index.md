---
title: Color
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示可以在不同颜色空间中表示的颜色值的类。
type: docs
weight: 63
url: /zh/java/com.aspose.pdf/color/
---
**遗产：**
java.lang.Object
```
public final class Color
```

表示可以在不同颜色空间中表示的颜色值的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Color()](#Color--) | 默认构造函数。 |
| [Color(double[] vector)](#Color-double---) | 构造函数 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [Empty](#Empty) | 代表空的颜色。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆这个实例 |
| [equals(Object obj)](#equals-java.lang.Object-) | 如果两个颜色相等，则返回 true。 |
| [fromArgb(int r, int g, int b)](#fromArgb-int-int-int-) | 从 RGB 颜色分量获取有效的 pdf 颜色对象。 |
| [fromArgb(int a, int r, int g, int b)](#fromArgb-int-int-int-int-) | 从 RGB 颜色分量获取有效的 pdf 颜色对象。 |
| [fromCmyk(double c, double m, double y, double k)](#fromCmyk-double-double-double-double-) | 从 RGB 颜色分量获取有效的 pdf 颜色对象。 |
| [fromGray(double g)](#fromGray-double-) | 从 Gray 颜色组件获取有效的 pdf Color 对象。 |
| [fromRgb(double r, double g, double b)](#fromRgb-double-double-double-) | 从 RGB 颜色分量获取有效的 pdf 颜色对象。 |
| [fromRgb(Color color)](#fromRgb-java.awt.Color-) | 从 java.awt.Color 值获取有效的 pdf Color 对象。 |
| [getA()](#getA--) | 获取 alpha 分量值 |
| [getAliceBlue()](#getAliceBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FFF0F8FF。 |
| [getAntiqueWhite()](#getAntiqueWhite--) | 获取系统定义的颜色，其 ARGB 值为\#FFFAEBD7。 |
| [getAqua()](#getAqua--) | 获取系统定义的颜色，其 ARGB 值为\#FF00FFFF。 |
| [getAquamarine()](#getAquamarine--) | 获取系统定义的颜色，其 ARGB 值为\#FF7FFFD4。 |
| [getAzure()](#getAzure--) | 获取系统定义的颜色，其 ARGB 值为\#FFF0FFFF。 |
| [getBeige()](#getBeige--) | 获取系统定义的颜色，其 ARGB 值为\#FFF5F5DC。 |
| [getBisque()](#getBisque--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFE4C4。 |
| [getBlack()](#getBlack--) | 获取系统定义的颜色，其 ARGB 值为\#FF000000。 |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFEBCD。 |
| [getBlue()](#getBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF0000FF。 |
| [getBlueViolet()](#getBlueViolet--) | 获取系统定义的颜色，其 ARGB 值为\#FF8A2BE2。 |
| [getBrown()](#getBrown--) | 获取系统定义的颜色，其 ARGB 值为\#FFA52A2A。 |
| [getBurlyWood()](#getBurlyWood--) | 获取系统定义的颜色，其 ARGB 值为\#FFDEB887。 |
| [getCadetBlue()](#getCadetBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF5F9EA0。 |
| [getChartreuse()](#getChartreuse--) | 获取系统定义的颜色，其 ARGB 值为\#FF7FFF00。 |
| [getChocolate()](#getChocolate--) | 获取系统定义的颜色，其 ARGB 值为\#FFD2691E。 |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | 获取颜色代表的颜色空间。 |
| [getCoral()](#getCoral--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF7F50。 |
| [getCornflowerBlue()](#getCornflowerBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF6495ED。 |
| [getCornsilk()](#getCornsilk--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFF8DC。 |
| [getCrimson()](#getCrimson--) | 获取系统定义的颜色，其 ARGB 值为\#FFDC143C。 |
| [getCyan()](#getCyan--) | 获取系统定义的颜色，其 ARGB 值为\#FF00FFFF。 |
| [getDarkBlue()](#getDarkBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF00008B。 |
| [getDarkCyan()](#getDarkCyan--) | 获取系统定义的颜色，其 ARGB 值为\#FF008B8B。 |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | 获取系统定义的颜色，其 ARGB 值为\#FFB8860B。 |
| [getDarkGray()](#getDarkGray--) | 获取系统定义的颜色，其 ARGB 值为\#FFA9A9A9。 |
| [getDarkGreen()](#getDarkGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF006400。 |
| [getDarkKhaki()](#getDarkKhaki--) | 获取系统定义的颜色，其 ARGB 值为\#FFBDB76B。 |
| [getDarkMagenta()](#getDarkMagenta--) | 获取系统定义的颜色，其 ARGB 值为\#FF8B008B。 |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF556B2F。 |
| [getDarkOrange()](#getDarkOrange--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF8C00。 |
| [getDarkOrchid()](#getDarkOrchid--) | 获取系统定义的颜色，其 ARGB 值为\#FF9932CC。 |
| [getDarkRed()](#getDarkRed--) | 获取系统定义的颜色，其 ARGB 值为\#FF8B0000。 |
| [getDarkSalmon()](#getDarkSalmon--) | 获取系统定义的颜色，其 ARGB 值为\#FFE9967A。 |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF8FBC8F。 |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF483D8B。 |
| [getDarkSlateGray()](#getDarkSlateGray--) | 获取系统定义的颜色，其 ARGB 值为\#FF2F4F4F。 |
| [getDarkTurquoise()](#getDarkTurquoise--) | 获取系统定义的颜色，其 ARGB 值为\#FF00CED1。 |
| [getDarkViolet()](#getDarkViolet--) | 获取系统定义的颜色，其 ARGB 值为\#FF9400D3。 |
| [getData()](#getData--) | 颜值。 |
| [getDeepPink()](#getDeepPink--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF1493。 |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF00BFFF。 |
| [getDimGray()](#getDimGray--) | 获取系统定义的颜色，其 ARGB 值为\#FF696969。 |
| [getDodgerBlue()](#getDodgerBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF1E90FF。 |
| [getFirebrick()](#getFirebrick--) | 获取系统定义的颜色，其 ARGB 值为\#FFB22222。 |
| [getFloralWhite()](#getFloralWhite--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFFAF0。 |
| [getForestGreen()](#getForestGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF228B22。 |
| [getFuchsia()](#getFuchsia--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF00FF。 |
| [getGainsboro()](#getGainsboro--) | 获取系统定义的颜色，其 ARGB 值为\#FFDCDCDC。 |
| [getGhostWhite()](#getGhostWhite--) | 获取系统定义的颜色，其 ARGB 值为\#FFF8F8FF。 |
| [getGold()](#getGold--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFD700。 |
| [getGoldenrod()](#getGoldenrod--) | 获取系统定义的颜色，其 ARGB 值为\#FFDAA520。 |
| [getGray()](#getGray--) | 获取系统定义的颜色，其 ARGB 值为\#FF808080。 |
| [getGreen()](#getGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF008000。 |
| [getGreenYellow()](#getGreenYellow--) | 获取系统定义的颜色，其 ARGB 值为\#FFADFF2F。 |
| [getHoneydew()](#getHoneydew--) | 获取系统定义的颜色，其 ARGB 值为\#FFF0FFF0。 |
| [getHotPink()](#getHotPink--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF69B4。 |
| [getIndianRed()](#getIndianRed--) | 获取系统定义的颜色，其 ARGB 值为\#FFCD5C5C。 |
| [getIndigo()](#getIndigo--) | 获取系统定义的颜色，其 ARGB 值为\#FF4B0082。 |
| [getIvory()](#getIvory--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFFFF0。 |
| [getKhaki()](#getKhaki--) | 获取系统定义的颜色，其 ARGB 值为\#FFF0E68C。 |
| [getLavender()](#getLavender--) | 获取系统定义的颜色，其 ARGB 值为\#FFE6E6FA。 |
| [getLavenderBlush()](#getLavenderBlush--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFF0F5。 |
| [getLawnGreen()](#getLawnGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF7CFC00。 |
| [getLemonChiffon()](#getLemonChiffon--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFFACD。 |
| [getLightBlue()](#getLightBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FFADD8E6。 |
| [getLightCoral()](#getLightCoral--) | 获取系统定义的颜色，其 ARGB 值为\#FFF08080。 |
| [getLightCyan()](#getLightCyan--) | 获取系统定义的颜色，其 ARGB 值为\#FFE0FFFF。 |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | 获取系统定义的颜色，其 ARGB 值为\#FFFAFAD2。 |
| [getLightGray()](#getLightGray--) | 获取系统定义的颜色，其 ARGB 值为\#FFD3D3D3。 |
| [getLightGreen()](#getLightGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF90EE90。 |
| [getLightPink()](#getLightPink--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFB6C1。 |
| [getLightSalmon()](#getLightSalmon--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFA07A。 |
| [getLightSeaGreen()](#getLightSeaGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF20B2AA。 |
| [getLightSkyBlue()](#getLightSkyBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF87CEFA。 |
| [getLightSlateGray()](#getLightSlateGray--) | 获取系统定义的颜色，其 ARGB 值为\#FF778899。 |
| [getLightSteelBlue()](#getLightSteelBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FFB0C4DE。 |
| [getLightYellow()](#getLightYellow--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFFFFE0。 |
| [getLime()](#getLime--) | 获取系统定义的颜色，其 ARGB 值为\#FF00FF00。 |
| [getLimeGreen()](#getLimeGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF32CD32。 |
| [getLinen()](#getLinen--) | 获取系统定义的颜色，其 ARGB 值为\#FFFAF0E6。 |
| [getMagenta()](#getMagenta--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF00FF。 |
| [getMaroon()](#getMaroon--) | 获取系统定义的颜色，其 ARGB 值为\#FF800000。 |
| [getMediumAquamarine()](#getMediumAquamarine--) | 获取系统定义的颜色，其 ARGB 值为\#FF66CDAA。 |
| [getMediumBlue()](#getMediumBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF0000CD。 |
| [getMediumOrchid()](#getMediumOrchid--) | 获取系统定义的颜色，其 ARGB 值为\#FFBA55D3。 |
| [getMediumPurple()](#getMediumPurple--) | 获取系统定义的颜色，其 ARGB 值为\#FF9370DB。 |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF3CB371。 |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF7B68EE。 |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF00FA9A。 |
| [getMediumTurquoise()](#getMediumTurquoise--) | 获取系统定义的颜色，其 ARGB 值为\#FF48D1CC。 |
| [getMediumVioletRed()](#getMediumVioletRed--) | 获取系统定义的颜色，其 ARGB 值为\#FFC71585。 |
| [getMidnightBlue()](#getMidnightBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF191970。 |
| [getMintCream()](#getMintCream--) | 获取系统定义的颜色，其 ARGB 值为\#FFF5FFFA。 |
| [getMistyRose()](#getMistyRose--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFE4E1。 |
| [getMoccasin()](#getMoccasin--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFE4B5。 |
| [getNavajoWhite()](#getNavajoWhite--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFDEAD。 |
| [getNavy()](#getNavy--) | 获取系统定义的颜色，其 ARGB 值为\#FF000080。 |
| [getOldLace()](#getOldLace--) | 获取系统定义的颜色，其 ARGB 值为\#FFFDF5E6。 |
| [getOlive()](#getOlive--) | 获取系统定义的颜色，其 ARGB 值为\#FF808000。 |
| [getOliveDrab()](#getOliveDrab--) | 获取系统定义的颜色，其 ARGB 值为\#FF6B8E23。 |
| [getOrange()](#getOrange--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFA500。 |
| [getOrangeRed()](#getOrangeRed--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF4500。 |
| [getOrchid()](#getOrchid--) | 获取系统定义的颜色，其 ARGB 值为\#FDA70D6。 |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | 获取系统定义的颜色，其 ARGB 值为\#FFEEE8AA。 |
| [getPaleGreen()](#getPaleGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF98FB98。 |
| [getPaleTurquoise()](#getPaleTurquoise--) | 获取系统定义的颜色，其 ARGB 值为\#FFAFEEEE。 |
| [getPaleVioletRed()](#getPaleVioletRed--) | 获取系统定义的颜色，其 ARGB 值为\#FFDB7093。 |
| [getPapayaWhip()](#getPapayaWhip--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFEFD5。 |
| [getPatternColorSpace()](#getPatternColorSpace--) | 获取一个对象，该对象指示图案颜色空间。 |
| [getPeachPuff()](#getPeachPuff--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFDAB9。 |
| [getPeru()](#getPeru--) | 获取系统定义的颜色，其 ARGB 值为\#FFCD853F。 |
| [getPink()](#getPink--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFC0CB。 |
| [getPlum()](#getPlum--) | 获取系统定义的颜色，其 ARGB 值为\#FFDDA0DD。 |
| [getPowderBlue()](#getPowderBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FFB0E0E6。 |
| [getPurple()](#getPurple--) | 获取系统定义的颜色，其 ARGB 值为\#FF800080。 |
| [getRed()](#getRed--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF0000。 |
| [getRosyBrown()](#getRosyBrown--) | 获取系统定义的颜色，其 ARGB 值为\#FFBC8F8F。 |
| [getRoyalBlue()](#getRoyalBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF4169E1。 |
| [getSaddleBrown()](#getSaddleBrown--) | 获取系统定义的颜色，其 ARGB 值为\#FF8B4513。 |
| [getSalmon()](#getSalmon--) | 获取系统定义的颜色，其 ARGB 值为\#FFFA8072。 |
| [getSandyBrown()](#getSandyBrown--) | 获取系统定义的颜色，其 ARGB 值为\#FFF4A460。 |
| [getSeaGreen()](#getSeaGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF2E8B57。 |
| [getSeaShell()](#getSeaShell--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFF5EE。 |
| [getSienna()](#getSienna--) | 获取系统定义的颜色，其 ARGB 值为\#FFA0522D。 |
| [getSilver()](#getSilver--) | 获取系统定义的颜色，其 ARGB 值为\#FFC0C0C0。 |
| [getSkyBlue()](#getSkyBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF87CEEB。 |
| [getSlateBlue()](#getSlateBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF6A5ACD。 |
| [getSlateGray()](#getSlateGray--) | 获取系统定义的颜色，其 ARGB 值为\#FF708090。 |
| [getSnow()](#getSnow--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFFAFA。 |
| [getSpringGreen()](#getSpringGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF00FF7F。 |
| [getSteelBlue()](#getSteelBlue--) | 获取系统定义的颜色，其 ARGB 值为\#FF4682B4。 |
| [getTan()](#getTan--) | 获取系统定义的颜色，其 ARGB 值为\#FFD2B48C。 |
| [getTeal()](#getTeal--) | 获取系统定义的颜色，其 ARGB 值为\#FF008080。 |
| [getThistle()](#getThistle--) | 获取系统定义的颜色，其 ARGB 值为\#FFD8BFD8。 |
| [getTomato()](#getTomato--) | 获取系统定义的颜色，其 ARGB 值为\#FFFF6347。 |
| [getTransparent()](#getTransparent--) | 获取系统定义的颜色。 |
| [getTurquoise()](#getTurquoise--) | 获取系统定义的颜色，其 ARGB 值为\#FF40E0D0。 |
| [getViolet()](#getViolet--) | 获取系统定义的颜色，其 ARGB 值为\#FFEE82EE。 |
| [getWheat()](#getWheat--) | 获取系统定义的颜色，其 ARGB 值为\#FFF5DEB3。 |
| [getWhite()](#getWhite--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFFFFF。 |
| [getWhiteSmoke()](#getWhiteSmoke--) | 获取系统定义的颜色，其 ARGB 值为\#FFF5F5F5。 |
| [getYellow()](#getYellow--) | 获取系统定义的颜色，其 ARGB 值为\#FFFFFF00。 |
| [getYellowGreen()](#getYellowGreen--) | 获取系统定义的颜色，其 ARGB 值为\#FF9ACD32。 |
| [hashCode()](#hashCode--) | 返回对象的哈希码值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color x, Color y)](#op-Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | 如果两个颜色相等，则返回 true。 |
| [op_Inequality(Color x, Color y)](#op-Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | 如果两个颜色不相等，则返回 true。 |
| [parse(String value)](#parse-java.lang.String-) | 从字符串中提取颜色分量。 |
| [setPatternColorSpace(PatternColorSpace value)](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | 设置指示图案颜色空间的对象。 |
| [toRgb()](#toRgb--) | 将颜色转换为 rgb。 |
| [toString()](#toString--) | 转换为字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Color() {#Color--}
```
public Color()
```


默认构造函数。

### Color(double[] vector) {#Color-double---}
```
public Color(double[] vector)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| vector | 双倍的[] | double[大批 |

### Empty {#Empty}
```
public static final Color Empty
```


代表空的颜色。

### deepClone() {#deepClone--}
```
public Color deepClone()
```


克隆这个实例

**退货：**
[Color](../../com.aspose.pdf/color) 颜色对象
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


如果两个颜色相等，则返回 true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的对象。 |

**退货：**
boolean - 如果 Color 对象相等则为 True。
### fromArgb(int r, int g, int b) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```


从 RGB 颜色分量获取有效的 pdf 颜色对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| r | int | 红色分量（值 0 - 255）。 |
| g | int | 绿色分量（值 0 - 255）。 |
| b | int | 蓝色分量（值 0 - 255）。 |

**退货：**
[Color](../../com.aspose.pdf/color) - 具有每个分量值的颜色对象[0..255] 范围。
### fromArgb(int a, int r, int g, int b) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```


从 RGB 颜色分量获取有效的 pdf 颜色对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| a | int | alpha 分量值（值 0 - 255）。 |
| r | int | 红色分量（值 0 - 255）。 |
| g | int | 绿色分量（值 0 - 255）。 |
| b | int | 蓝色分量（值 0 - 255）。 |

**退货：**
[Color](../../com.aspose.pdf/color) - 具有每个分量值的颜色对象[0..255] 范围。
### fromCmyk(double c, double m, double y, double k) {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```


从 RGB 颜色分量获取有效的 pdf 颜色对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| c | double | 青色分量（值 0 - 1）。 |
| m | double | 品红色分量（值 0 - 1）。 |
| y | double | 黄色分量（值 0 - 1）。 |
| k | double | 关键颜色组件（值 0 - 1）。 |

**退货：**
[Color](../../com.aspose.pdf/color) - 具有每个分量值的颜色对象[0..1]范围。
### fromGray(double g) {#fromGray-double-}
```
public static Color fromGray(double g)
```


从 Gray 颜色组件获取有效的 pdf Color 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| g | double | 灰色颜色分量（值 0 - 1）。 |

**退货：**
[Color](../../com.aspose.pdf/color) - 具有每个分量值的颜色对象[0..1]范围。
### fromRgb(double r, double g, double b) {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```


从 RGB 颜色分量获取有效的 pdf 颜色对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| r | double | 红色分量（值 0 - 1）。 |
| g | double | 绿色分量（值 0 - 1）。 |
| b | double | 蓝色分量（值 0 - 1）。 |

**退货：**
[Color](../../com.aspose.pdf/color) - 具有每个分量值的颜色对象[0..1]范围。
### fromRgb(Color color) {#fromRgb-java.awt.Color-}
```
public static Color fromRgb(Color color)
```


从 java.awt.Color 值获取有效的 pdf Color 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | java.awt.Color | System.Drawing.Color 值。 |

**退货：**
[Color](../../com.aspose.pdf/color) - 具有每个分量值的颜色对象[0..1]范围。
### getA() {#getA--}
```
public double getA()
```


获取 alpha 分量值

**退货：**
双倍价值
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FFF0F8FF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


获取系统定义的颜色，其 ARGB 值为\#FFFAEBD7。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


获取系统定义的颜色，其 ARGB 值为\#FF00FFFF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


获取系统定义的颜色，其 ARGB 值为\#FF7FFFD4。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


获取系统定义的颜色，其 ARGB 值为\#FFF0FFFF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


获取系统定义的颜色，其 ARGB 值为\#FFF5F5DC。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFE4C4。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


获取系统定义的颜色，其 ARGB 值为\#FF000000。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFEBCD。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF0000FF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


获取系统定义的颜色，其 ARGB 值为\#FF8A2BE2。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


获取系统定义的颜色，其 ARGB 值为\#FFA52A2A。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


获取系统定义的颜色，其 ARGB 值为\#FFDEB887。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF5F9EA0。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


获取系统定义的颜色，其 ARGB 值为\#FF7FFF00。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


获取系统定义的颜色，其 ARGB 值为\#FFD2691E。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


获取颜色代表的颜色空间。

**退货：**
int - ColorSpace 对象
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF7F50。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF6495ED。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFF8DC。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


获取系统定义的颜色，其 ARGB 值为\#FFDC143C。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


获取系统定义的颜色，其 ARGB 值为\#FF00FFFF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF00008B。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


获取系统定义的颜色，其 ARGB 值为\#FF008B8B。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


获取系统定义的颜色，其 ARGB 值为\#FFB8860B。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


获取系统定义的颜色，其 ARGB 值为\#FFA9A9A9。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF006400。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


获取系统定义的颜色，其 ARGB 值为\#FFBDB76B。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


获取系统定义的颜色，其 ARGB 值为\#FF8B008B。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF556B2F。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF8C00。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


获取系统定义的颜色，其 ARGB 值为\#FF9932CC。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


获取系统定义的颜色，其 ARGB 值为\#FF8B0000。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


获取系统定义的颜色，其 ARGB 值为\#FFE9967A。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF8FBC8F。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF483D8B。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


获取系统定义的颜色，其 ARGB 值为\#FF2F4F4F。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


获取系统定义的颜色，其 ARGB 值为\#FF00CED1。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


获取系统定义的颜色，其 ARGB 值为\#FF9400D3。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getData() {#getData--}
```
public double[] getData()
```


颜值。

**退货：**
双倍的[- 双精度值数组
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF1493。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF00BFFF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


获取系统定义的颜色，其 ARGB 值为\#FF696969。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF1E90FF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


获取系统定义的颜色，其 ARGB 值为\#FFB22222。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFFAF0。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF228B22。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF00FF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


获取系统定义的颜色，其 ARGB 值为\#FFDCDCDC。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


获取系统定义的颜色，其 ARGB 值为\#FFF8F8FF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getGold() {#getGold--}
```
public static Color getGold()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFD700。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


获取系统定义的颜色，其 ARGB 值为\#FFDAA520。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getGray() {#getGray--}
```
public static Color getGray()
```


获取系统定义的颜色，其 ARGB 值为\#FF808080。

**退货：**
[Color](../../com.aspose.pdf/color) 表示系统定义颜色的结构。
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF008000。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


获取系统定义的颜色，其 ARGB 值为\#FFADFF2F。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


获取系统定义的颜色，其 ARGB 值为\#FFF0FFF0。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF69B4。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


获取系统定义的颜色，其 ARGB 值为\#FFCD5C5C。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


获取系统定义的颜色，其 ARGB 值为\#FF4B0082。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFFFF0。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


获取系统定义的颜色，其 ARGB 值为\#FFF0E68C。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


获取系统定义的颜色，其 ARGB 值为\#FFE6E6FA。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFF0F5。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF7CFC00。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFFACD。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FFADD8E6。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


获取系统定义的颜色，其 ARGB 值为\#FFF08080。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


获取系统定义的颜色，其 ARGB 值为\#FFE0FFFF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


获取系统定义的颜色，其 ARGB 值为\#FFFAFAD2。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


获取系统定义的颜色，其 ARGB 值为\#FFD3D3D3。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF90EE90。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFB6C1。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFA07A。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF20B2AA。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF87CEFA。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


获取系统定义的颜色，其 ARGB 值为\#FF778899。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FFB0C4DE。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFFFFE0。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLime() {#getLime--}
```
public static Color getLime()
```


获取系统定义的颜色，其 ARGB 值为\#FF00FF00。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF32CD32。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


获取系统定义的颜色，其 ARGB 值为\#FFFAF0E6。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF00FF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


获取系统定义的颜色，其 ARGB 值为\#FF800000。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


获取系统定义的颜色，其 ARGB 值为\#FF66CDAA。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF0000CD。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


获取系统定义的颜色，其 ARGB 值为\#FFBA55D3。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


获取系统定义的颜色，其 ARGB 值为\#FF9370DB。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF3CB371。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF7B68EE。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF00FA9A。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


获取系统定义的颜色，其 ARGB 值为\#FF48D1CC。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


获取系统定义的颜色，其 ARGB 值为\#FFC71585。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF191970。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


获取系统定义的颜色，其 ARGB 值为\#FFF5FFFA。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFE4E1。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFE4B5。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFDEAD。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


获取系统定义的颜色，其 ARGB 值为\#FF000080。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


获取系统定义的颜色，其 ARGB 值为\#FFFDF5E6。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


获取系统定义的颜色，其 ARGB 值为\#FF808000。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


获取系统定义的颜色，其 ARGB 值为\#FF6B8E23。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFA500。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF4500。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


获取系统定义的颜色，其 ARGB 值为\#FDA70D6。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


获取系统定义的颜色，其 ARGB 值为\#FFEEE8AA。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF98FB98。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


获取系统定义的颜色，其 ARGB 值为\#FFAFEEEE。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


获取系统定义的颜色，其 ARGB 值为\#FFDB7093。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFEFD5。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPatternColorSpace() {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```


获取一个对象，该对象指示图案颜色空间。

仅限内部使用

**退货：**
[PatternColorSpace](../../com.aspose.pdf.drawing/patterncolorspace) PatternColorSpace 对象
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFDAB9。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


获取系统定义的颜色，其 ARGB 值为\#FFCD853F。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPink() {#getPink--}
```
public static Color getPink()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFC0CB。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


获取系统定义的颜色，其 ARGB 值为\#FFDDA0DD。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FFB0E0E6。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


获取系统定义的颜色，其 ARGB 值为\#FF800080。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getRed() {#getRed--}
```
public static Color getRed()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF0000。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


获取系统定义的颜色，其 ARGB 值为\#FFBC8F8F。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF4169E1。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


获取系统定义的颜色，其 ARGB 值为\#FF8B4513。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


获取系统定义的颜色，其 ARGB 值为\#FFFA8072。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


获取系统定义的颜色，其 ARGB 值为\#FFF4A460。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF2E8B57。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFF5EE。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


获取系统定义的颜色，其 ARGB 值为\#FFA0522D。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


获取系统定义的颜色，其 ARGB 值为\#FFC0C0C0。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF87CEEB。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF6A5ACD。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


获取系统定义的颜色，其 ARGB 值为\#FF708090。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFFAFA。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF00FF7F。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


获取系统定义的颜色，其 ARGB 值为\#FF4682B4。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getTan() {#getTan--}
```
public static Color getTan()
```


获取系统定义的颜色，其 ARGB 值为\#FFD2B48C。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


获取系统定义的颜色，其 ARGB 值为\#FF008080。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


获取系统定义的颜色，其 ARGB 值为\#FFD8BFD8。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


获取系统定义的颜色，其 ARGB 值为\#FFFF6347。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


获取系统定义的颜色。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


获取系统定义的颜色，其 ARGB 值为\#FF40E0D0。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


获取系统定义的颜色，其 ARGB 值为\#FFEE82EE。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


获取系统定义的颜色，其 ARGB 值为\#FFF5DEB3。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFFFFF。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


获取系统定义的颜色，其 ARGB 值为\#FFF5F5F5。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


获取系统定义的颜色，其 ARGB 值为\#FFFFFF00。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


获取系统定义的颜色，其 ARGB 值为\#FF9ACD32。

**退货：**
[Color](../../com.aspose.pdf/color) - 代表系统定义的颜色。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回对象的哈希码值。支持此方法是为了散列表的好处，例如 java.util.HashMap 提供的散列表。

hashCode的一般契约是：

 *  每当在 Java 应用程序的执行期间对同一对象多次调用它时，hashCode 方法必须一致地返回相同的整数，前提是在对象的 equals 比较中使用的信息没有被修改。从一个应用程序的一次执行到同一应用程序的另一次执行，该整数不需要保持一致。
 *  如果根据 equals(Object) 方法两个对象相等，则对这两个对象中的每一个调用 hashCode 方法必须产生相同的整数结果。
 *  这是*not*要求如果两个对象根据 java.lang.Object 不相等\#equals(java.lang.Object).equals(java.lang.Object) 方法，然后在两个对象中的每一个上调用 hashCode 方法必须产生不同的整数结果。但是，程序员应该知道，为不相等的对象生成不同的整数结果可能会提高哈希表的性能。

在相当实用的情况下，类 Object 定义的 hashCode 方法确实会为不同的对象返回不同的整数。 （这通常是通过将对象的内部地址转换为整数来实现的，但 JavaTM 编程语言不需要这种实现技术。）

**退货：**
int - 此对象的哈希码值。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(Color x, Color y) {#op-Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
```
public static boolean op_Equality(Color x, Color y)
```


如果两个颜色相等，则返回 true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| x | [Color](../../com.aspose.pdf/color) | 第一个颜色对象。 |
| y | [Color](../../com.aspose.pdf/color) | 第二个颜色对象。 |

**退货：**
boolean - 如果 Color 对象相等则为 True。
### op_Inequality(Color x, Color y) {#op-Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
```
public static boolean op_Inequality(Color x, Color y)
```


如果两个颜色不相等，则返回 true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| x | [Color](../../com.aspose.pdf/color) | 第一个颜色对象。 |
| y | [Color](../../com.aspose.pdf/color) | 第二个颜色对象。 |

**退货：**
boolean - 如果 Color 对象不相等则为 True。
### parse(String value) {#parse-java.lang.String-}
```
public static Color parse(String value)
```


从字符串中提取颜色分量。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 具有颜色分量值的字符串值。 |

**退货：**
[Color](../../com.aspose.pdf/color) - 颜色对象。
### setPatternColorSpace(PatternColorSpace value) {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
```
public void setPatternColorSpace(PatternColorSpace value)
```


设置指示图案颜色空间的对象。

仅限内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PatternColorSpace](../../com.aspose.pdf.drawing/patterncolorspace) | PatternColorSpace 对象 |

### toRgb() {#toRgb--}
```
public Color toRgb()
```


将颜色转换为 rgb。

**退货：**
[Color](../../java.awt/color) RGB 颜色值。
### toString() {#toString--}
```
public String toString()
```


转换为字符串。

**退货：**
java.lang.String - Color 对象的字符串表示。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
