---
title: Color
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для значения цвета, которое может быть выражено в другом цветовом пространстве.
type: docs
weight: 63
url: /ru/java/com.aspose.pdf/color/
---
**Наследование:**
java.lang.Object
```
public final class Color
```

Представляет класс для значения цвета, которое может быть выражено в другом цветовом пространстве.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Color()](#Color--) | Конструктор по умолчанию. |
| [Color(double[] vector)](#Color-double---) | Конструктор |
## Поля

| Поле | Описание |
| --- | --- |
| [Empty](#Empty) | Представляет пустой цвет. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает true, если два цвета равны. |
| [fromArgb(int r, int g, int b)](#fromArgb-int-int-int-) | Получает действительный объект pdf Color из цветовых компонентов RGB. |
| [fromArgb(int a, int r, int g, int b)](#fromArgb-int-int-int-int-) | Получает действительный объект pdf Color из цветовых компонентов RGB. |
| [fromCmyk(double c, double m, double y, double k)](#fromCmyk-double-double-double-double-) | Получает действительный объект pdf Color из цветовых компонентов RGB. |
| [fromGray(double g)](#fromGray-double-) | Получает действительный объект pdf Color из компонента серого цвета. |
| [fromRgb(double r, double g, double b)](#fromRgb-double-double-double-) | Получает действительный объект pdf Color из цветовых компонентов RGB. |
| [fromRgb(Color color)](#fromRgb-java.awt.Color-) | Получает действительный объект pdf Color из значения java.awt.Color. |
| [getA()](#getA--) | Получает значение альфа-компонента |
| [getAliceBlue()](#getAliceBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF0F8FF. |
| [getAntiqueWhite()](#getAntiqueWhite--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFAEBD7. |
| [getAqua()](#getAqua--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF00FFFF. |
| [getAquamarine()](#getAquamarine--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF7FFFD4. |
| [getAzure()](#getAzure--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF0FFFF. |
| [getBeige()](#getBeige--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF5F5DC. |
| [getBisque()](#getBisque--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFE4C4. |
| [getBlack()](#getBlack--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF000000. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFEBCD. |
| [getBlue()](#getBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF0000FF. |
| [getBlueViolet()](#getBlueViolet--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF8A2BE2. |
| [getBrown()](#getBrown--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFA52A2A. |
| [getBurlyWood()](#getBurlyWood--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFDEB887. |
| [getCadetBlue()](#getCadetBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF5F9EA0. |
| [getChartreuse()](#getChartreuse--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF7FFF00. |
| [getChocolate()](#getChocolate--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFD2691E. |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Получает цветовое пространство, которое представляет цвет. |
| [getCoral()](#getCoral--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF7F50. |
| [getCornflowerBlue()](#getCornflowerBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF6495ED. |
| [getCornsilk()](#getCornsilk--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFF8DC. |
| [getCrimson()](#getCrimson--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFDC143C. |
| [getCyan()](#getCyan--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF00FFFF. |
| [getDarkBlue()](#getDarkBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF00008B. |
| [getDarkCyan()](#getDarkCyan--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF008B8B. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFB8860B. |
| [getDarkGray()](#getDarkGray--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFA9A9A9. |
| [getDarkGreen()](#getDarkGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF006400. |
| [getDarkKhaki()](#getDarkKhaki--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFBDB76B. |
| [getDarkMagenta()](#getDarkMagenta--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF8B008B. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF556B2F. |
| [getDarkOrange()](#getDarkOrange--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF8C00. |
| [getDarkOrchid()](#getDarkOrchid--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF9932CC. |
| [getDarkRed()](#getDarkRed--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF8B0000. |
| [getDarkSalmon()](#getDarkSalmon--) |  Получает определяемый системой цвет со значением ARGB, равным\№ FFE9967A. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF8FBC8F. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF483D8B. |
| [getDarkSlateGray()](#getDarkSlateGray--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF2F4F4F. |
| [getDarkTurquoise()](#getDarkTurquoise--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF00CED1. |
| [getDarkViolet()](#getDarkViolet--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF9400D3. |
| [getData()](#getData--) | Значение цвета. |
| [getDeepPink()](#getDeepPink--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF1493. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF00BFFFF. |
| [getDimGray()](#getDimGray--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF696969. |
| [getDodgerBlue()](#getDodgerBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF1E90FF. |
| [getFirebrick()](#getFirebrick--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFB22222. |
| [getFloralWhite()](#getFloralWhite--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFFFAF0. |
| [getForestGreen()](#getForestGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF228B22. |
| [getFuchsia()](#getFuchsia--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF00FF. |
| [getGainsboro()](#getGainsboro--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFDCDCDC. |
| [getGhostWhite()](#getGhostWhite--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF8F8FF. |
| [getGold()](#getGold--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFD700. |
| [getGoldenrod()](#getGoldenrod--) |  Получает определяемый системой цвет со значением ARGB, равным\#ФФДАА520. |
| [getGray()](#getGray--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF808080. |
| [getGreen()](#getGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF008000. |
| [getGreenYellow()](#getGreenYellow--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFADFF2F. |
| [getHoneydew()](#getHoneydew--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF0FFF0. |
| [getHotPink()](#getHotPink--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF69B4. |
| [getIndianRed()](#getIndianRed--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFCD5C5C. |
| [getIndigo()](#getIndigo--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF4B0082. |
| [getIvory()](#getIvory--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFFFFF0. |
| [getKhaki()](#getKhaki--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF0E68C. |
| [getLavender()](#getLavender--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFE6E6FA. |
| [getLavenderBlush()](#getLavenderBlush--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFF0F5. |
| [getLawnGreen()](#getLawnGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF7CFC00. |
| [getLemonChiffon()](#getLemonChiffon--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFFACD. |
| [getLightBlue()](#getLightBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFADD8E6. |
| [getLightCoral()](#getLightCoral--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF08080. |
| [getLightCyan()](#getLightCyan--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFE0FFFF. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) |  Получает определяемый системой цвет со значением ARGB, равным\#ФФФАФАД2. |
| [getLightGray()](#getLightGray--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFD3D3D3. |
| [getLightGreen()](#getLightGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF90EE90. |
| [getLightPink()](#getLightPink--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFB6C1. |
| [getLightSalmon()](#getLightSalmon--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFA07A. |
| [getLightSeaGreen()](#getLightSeaGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF20B2AA. |
| [getLightSkyBlue()](#getLightSkyBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF87CEFA. |
| [getLightSlateGray()](#getLightSlateGray--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF778899. |
| [getLightSteelBlue()](#getLightSteelBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFB0C4DE. |
| [getLightYellow()](#getLightYellow--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFFFFE0. |
| [getLime()](#getLime--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF00FF00. |
| [getLimeGreen()](#getLimeGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF32CD32. |
| [getLinen()](#getLinen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFAFAF0E6. |
| [getMagenta()](#getMagenta--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF00FF. |
| [getMaroon()](#getMaroon--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF800000. |
| [getMediumAquamarine()](#getMediumAquamarine--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF66CDAA. |
| [getMediumBlue()](#getMediumBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF0000CD. |
| [getMediumOrchid()](#getMediumOrchid--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFBA55D3. |
| [getMediumPurple()](#getMediumPurple--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF9370DB. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF3CB371. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF7B68EE. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF00FA9A. |
| [getMediumTurquoise()](#getMediumTurquoise--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF48D1CC. |
| [getMediumVioletRed()](#getMediumVioletRed--) |  Получает определяемый системой цвет со значением ARGB, равным\№ FFC71585. |
| [getMidnightBlue()](#getMidnightBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF191970. |
| [getMintCream()](#getMintCream--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF5FFFA. |
| [getMistyRose()](#getMistyRose--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFE4E1. |
| [getMoccasin()](#getMoccasin--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFE4B5. |
| [getNavajoWhite()](#getNavajoWhite--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFDEAD. |
| [getNavy()](#getNavy--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF000080. |
| [getOldLace()](#getOldLace--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFDF5E6. |
| [getOlive()](#getOlive--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF808000. |
| [getOliveDrab()](#getOliveDrab--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF6B8E23. |
| [getOrange()](#getOrange--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFA500. |
| [getOrangeRed()](#getOrangeRed--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF4500. |
| [getOrchid()](#getOrchid--) |  Получает определяемый системой цвет со значением ARGB, равным\#ФФДА70D6. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFEEE8AA. |
| [getPaleGreen()](#getPaleGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF98FB98. |
| [getPaleTurquoise()](#getPaleTurquoise--) |  Получает определяемый системой цвет со значением ARGB, равным\#ФФФЕЕЕЕЕ. |
| [getPaleVioletRed()](#getPaleVioletRed--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFDB7093. |
| [getPapayaWhip()](#getPapayaWhip--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFEFD5. |
| [getPatternColorSpace()](#getPatternColorSpace--) | Получает объект, указывающий цветовое пространство узора. |
| [getPeachPuff()](#getPeachPuff--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFDAB9. |
| [getPeru()](#getPeru--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFCD853F. |
| [getPink()](#getPink--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFFC0CB. |
| [getPlum()](#getPlum--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFDDA0DD. |
| [getPowderBlue()](#getPowderBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFB0E0E6. |
| [getPurple()](#getPurple--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF800080. |
| [getRed()](#getRed--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF0000. |
| [getRosyBrown()](#getRosyBrown--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFBC8F8F. |
| [getRoyalBlue()](#getRoyalBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF4169E1. |
| [getSaddleBrown()](#getSaddleBrown--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF8B4513. |
| [getSalmon()](#getSalmon--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFA8072. |
| [getSandyBrown()](#getSandyBrown--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF4A460. |
| [getSeaGreen()](#getSeaGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF2E8B57. |
| [getSeaShell()](#getSeaShell--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFF5EE. |
| [getSienna()](#getSienna--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFA0522D. |
| [getSilver()](#getSilver--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFC0C0C0. |
| [getSkyBlue()](#getSkyBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF87CEEB. |
| [getSlateBlue()](#getSlateBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF6A5ACD. |
| [getSlateGray()](#getSlateGray--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF708090. |
| [getSnow()](#getSnow--) |  Получает определяемый системой цвет со значением ARGB, равным\#ФФФФФАФА. |
| [getSpringGreen()](#getSpringGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF00FF7F. |
| [getSteelBlue()](#getSteelBlue--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF4682B4. |
| [getTan()](#getTan--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFD2B48C. |
| [getTeal()](#getTeal--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF008080. |
| [getThistle()](#getThistle--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFD8BFD8. |
| [getTomato()](#getTomato--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFF6347. |
| [getTransparent()](#getTransparent--) | Получает определенный системой цвет. |
| [getTurquoise()](#getTurquoise--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF40E0D0. |
| [getViolet()](#getViolet--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFEE82EE. |
| [getWheat()](#getWheat--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF5DEB3. |
| [getWhite()](#getWhite--) |  Получает определяемый системой цвет со значением ARGB, равным\#ФФФФФФФ. |
| [getWhiteSmoke()](#getWhiteSmoke--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFF5F5F5. |
| [getYellow()](#getYellow--) |  Получает определяемый системой цвет со значением ARGB, равным\#FFFFFF00. |
| [getYellowGreen()](#getYellowGreen--) |  Получает определяемый системой цвет со значением ARGB, равным\#FF9ACD32. |
| [hashCode()](#hashCode--) | Возвращает значение хэш-кода для объекта. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color x, Color y)](#op-Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Возвращает true, если два цвета равны. |
| [op_Inequality(Color x, Color y)](#op-Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Возвращает true, если два цвета не равны. |
| [parse(String value)](#parse-java.lang.String-) | Извлекает компоненты цвета из строки. |
| [setPatternColorSpace(PatternColorSpace value)](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Задает объект, указывающий цветовое пространство шаблона. |
| [toRgb()](#toRgb--) | Преобразует цвет в rgb. |
| [toString()](#toString--) | Преобразуется в строку. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Color() {#Color--}
```
public Color()
```


Конструктор по умолчанию.

### Color(double[] vector) {#Color-double---}
```
public Color(double[] vector)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| vector | двойной[] | double[] множество |

### Empty {#Empty}
```
public static final Color Empty
```


Представляет пустой цвет.

### deepClone() {#deepClone--}
```
public Color deepClone()
```


Клонирует этот экземпляр

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цвет объекта
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает true, если два цвета равны.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения. |

**Возвращает:**
boolean - True, если объекты Color равны.
### fromArgb(int r, int g, int b) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```


Получает действительный объект pdf Color из цветовых компонентов RGB.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| r | int | Компонент красного цвета (значение 0 - 255). |
| g | int | Компонент зеленого цвета (значение 0 - 255). |
| b | int | Компонент синего цвета (значение 0–255). |

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной объект со значением каждого компонента в[0..255].
### fromArgb(int a, int r, int g, int b) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```


Получает действительный объект pdf Color из цветовых компонентов RGB.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | int | Значение альфа-компонента (значение от 0 до 255). |
| r | int | Компонент красного цвета (значение 0 - 255). |
| g | int | Компонент зеленого цвета (значение 0 - 255). |
| b | int | Компонент синего цвета (значение 0–255). |

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной объект со значением каждого компонента в[0..255].
### fromCmyk(double c, double m, double y, double k) {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```


Получает действительный объект pdf Color из цветовых компонентов RGB.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | double | Компонент голубого цвета (значение 0–1). |
| m | double | Компонент пурпурного цвета (значение 0–1). |
| y | double | Компонент желтого цвета (значение 0 - 1). |
| k | double | Компонент Key color (значение 0–1). |

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной объект со значением каждого компонента в[0..1] диапазон.
### fromGray(double g) {#fromGray-double-}
```
public static Color fromGray(double g)
```


Получает действительный объект pdf Color из компонента серого цвета.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| g | double | Компонент серого цвета (значение 0–1). |

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной объект со значением каждого компонента в[0..1] диапазон.
### fromRgb(double r, double g, double b) {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```


Получает действительный объект pdf Color из цветовых компонентов RGB.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| r | double | Компонент красного цвета (значение 0 - 1). |
| g | double | Компонент зеленого цвета (значение 0 - 1). |
| b | double | Компонент синего цвета (значение 0–1). |

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной объект со значением каждого компонента в[0..1] диапазон.
### fromRgb(Color color) {#fromRgb-java.awt.Color-}
```
public static Color fromRgb(Color color)
```


Получает действительный объект pdf Color из значения java.awt.Color.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | java.awt.Color | Значение System.Drawing.Color. |

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной объект со значением каждого компонента в[0..1] диапазон.
### getA() {#getA--}
```
public double getA()
```


Получает значение альфа-компонента

**Возвращает:**
двойное - двойное значение
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF0F8FF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFAEBD7.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF00FFFF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF7FFFD4.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF0FFFF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF5F5DC.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFE4C4.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF000000.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFEBCD.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF0000FF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF8A2BE2.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFA52A2A.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFDEB887.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF5F9EA0.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF7FFF00.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFD2691E.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Получает цветовое пространство, которое представляет цвет.

**Возвращает:**
int - объект ColorSpace
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF7F50.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF6495ED.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFF8DC.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFDC143C.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF00FFFF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF00008B.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF008B8B.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFB8860B.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFA9A9A9.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF006400.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFBDB76B.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF8B008B.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF556B2F.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF8C00.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF9932CC.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF8B0000.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


 Получает определяемый системой цвет со значением ARGB, равным\№ FFE9967A.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF8FBC8F.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF483D8B.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF2F4F4F.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF00CED1.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF9400D3.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getData() {#getData--}
```
public double[] getData()
```


Значение цвета.

**Возвращает:**
двойной[] - массив двойных значений
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF1493.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF00BFFFF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF696969.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF1E90FF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFB22222.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFFFAF0.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF228B22.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF00FF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFDCDCDC.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF8F8FF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getGold() {#getGold--}
```
public static Color getGold()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFD700.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


 Получает определяемый системой цвет со значением ARGB, равным\#ФФДАА520.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getGray() {#getGray--}
```
public static Color getGray()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF808080.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Структура, представляющая определенный системой цвет.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF008000.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFADFF2F.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF0FFF0.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF69B4.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFCD5C5C.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF4B0082.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFFFFF0.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF0E68C.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFE6E6FA.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFF0F5.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF7CFC00.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFFACD.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFADD8E6.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF08080.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFE0FFFF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


 Получает определяемый системой цвет со значением ARGB, равным\#ФФФАФАД2.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFD3D3D3.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF90EE90.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFB6C1.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFA07A.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF20B2AA.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF87CEFA.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF778899.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFB0C4DE.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFFFFE0.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLime() {#getLime--}
```
public static Color getLime()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF00FF00.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF32CD32.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFAFAF0E6.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF00FF.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF800000.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF66CDAA.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF0000CD.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFBA55D3.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF9370DB.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF3CB371.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF7B68EE.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF00FA9A.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF48D1CC.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


 Получает определяемый системой цвет со значением ARGB, равным\№ FFC71585.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF191970.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF5FFFA.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFE4E1.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFE4B5.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFDEAD.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF000080.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFDF5E6.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF808000.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF6B8E23.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFA500.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF4500.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


 Получает определяемый системой цвет со значением ARGB, равным\#ФФДА70D6.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFEEE8AA.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF98FB98.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


 Получает определяемый системой цвет со значением ARGB, равным\#ФФФЕЕЕЕЕ.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFDB7093.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFEFD5.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPatternColorSpace() {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```


Получает объект, указывающий цветовое пространство узора.

Только внутреннее использование

**Возвращает:**
[PatternColorSpace](../../com.aspose.pdf.drawing/patterncolorspace) - Объект PatternColorSpace
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFDAB9.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFCD853F.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPink() {#getPink--}
```
public static Color getPink()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFFC0CB.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFDDA0DD.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFB0E0E6.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF800080.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getRed() {#getRed--}
```
public static Color getRed()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF0000.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFBC8F8F.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF4169E1.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF8B4513.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFA8072.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF4A460.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF2E8B57.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFF5EE.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFA0522D.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFC0C0C0.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF87CEEB.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF6A5ACD.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF708090.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


 Получает определяемый системой цвет со значением ARGB, равным\#ФФФФФАФА.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF00FF7F.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF4682B4.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getTan() {#getTan--}
```
public static Color getTan()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFD2B48C.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF008080.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFD8BFD8.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFF6347.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Получает определенный системой цвет.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF40E0D0.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFEE82EE.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF5DEB3.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


 Получает определяемый системой цвет со значением ARGB, равным\#ФФФФФФФ.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFF5F5F5.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FFFFFF00.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


 Получает определяемый системой цвет со значением ARGB, равным\#FF9ACD32.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - представляет определенный системой цвет.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает значение хэш-кода для объекта. Этот метод поддерживается для хеш-таблиц, таких как предоставляемые java.util.HashMap.

Общий контракт hashCode:

 *  Всякий раз, когда он вызывается для одного и того же объекта более одного раза во время выполнения приложения Java, метод hashCode должен постоянно возвращать одно и то же целое число, при условии, что никакая информация, используемая в сравнениях на равенство для объекта, не изменяется. Это целое число не обязательно должно оставаться постоянным от одного выполнения приложения к другому выполнению того же приложения.
 *  Если два объекта равны в соответствии с методом equals(Object), то вызов метода hashCode для каждого из двух объектов должен давать одинаковый целочисленный результат.
 *   это*not* требуется, чтобы, если два объекта не равны в соответствии с java.lang.Object\#equals(java.lang.Object).equals(java.lang.Object), то вызов метода hashCode для каждого из двух объектов должен давать различные целочисленные результаты. Однако программист должен знать, что создание различных целочисленных результатов для неравных объектов может повысить производительность хеш-таблиц.

Насколько это целесообразно, метод hashCode, определенный классом Object, действительно возвращает разные целые числа для разных объектов. (Обычно это реализуется путем преобразования внутреннего адреса объекта в целое число, но этот метод реализации не требуется для языка программирования JavaTM.)

**Возвращает:**
int - значение хеш-кода для этого объекта.
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


Возвращает true, если два цвета равны.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [Color](../../com.aspose.pdf/color) | Первый цветной объект. |
| y | [Color](../../com.aspose.pdf/color) | Второй цветной объект. |

**Возвращает:**
boolean - True, если объекты Color равны.
### op_Inequality(Color x, Color y) {#op-Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
```
public static boolean op_Inequality(Color x, Color y)
```


Возвращает true, если два цвета не равны.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [Color](../../com.aspose.pdf/color) | Первый цветной объект. |
| y | [Color](../../com.aspose.pdf/color) | Второй цветной объект. |

**Возвращает:**
boolean — True, если объекты Color не равны.
### parse(String value) {#parse-java.lang.String-}
```
public static Color parse(String value)
```


Извлекает компоненты цвета из строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение со значениями компонента цвета. |

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цвет объекта.
### setPatternColorSpace(PatternColorSpace value) {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
```
public void setPatternColorSpace(PatternColorSpace value)
```


Задает объект, указывающий цветовое пространство шаблона.

Только внутреннее использование

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PatternColorSpace](../../com.aspose.pdf.drawing/patterncolorspace) | Объект PatternColorSpace |

### toRgb() {#toRgb--}
```
public Color toRgb()
```


Преобразует цвет в rgb.

**Возвращает:**
[Color](../../java.awt/color) - Значение цвета RGB.
### toString() {#toString--}
```
public String toString()
```


Преобразуется в строку.

**Возвращает:**
java.lang.String — строковое представление объекта Color.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
