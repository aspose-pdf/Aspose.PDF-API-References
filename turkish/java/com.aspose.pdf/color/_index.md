---
title: "Renk"
linktitle: "Renk"
second_title: "Aspose.PDF for Java API Referansı"
description: "Farklı renk uzaylarında ifade edilebilen renk değeri için bir sınıfı temsil eder."
type: docs
weight: 670
url: /tr/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

Farklı renk uzaylarında ifade edilebilen renk değeri için bir sınıfı temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Default](#Default) | Varsayılan rengi temsil eder. |
| [Empty](#Empty) | Boş rengi temsil eder. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Color](#Color--) | Varsayılan yapıcı. |
| [Color](#Color-double:A-) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | Bu örneği kopyalar |
| [equals](#equals-java.lang.Object-) | İki Colors eşitse true döndürür. |
| [fromArgb](#fromArgb-int-int-int-) | RGB renk bileşenlerinden geçerli pdf Color nesnesi alır. |
| [fromArgb](#fromArgb-int-int-int-int-) | RGB renk bileşenlerinden geçerli pdf Color nesnesi alır. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | CMYK renk bileşenlerinden geçerli pdf Color nesnesi alır. |
| [fromGray](#fromGray-double-) | Gri renk bileşeninden geçerli pdf Color nesnesi alır. |
| [fromRgb](#fromRgb-java.awt.Color-) | java.awt.Color değerinden geçerli pdf Color nesnesi alır. |
| [fromRgb](#fromRgb-double-double-double-) | RGB renk bileşenlerinden geçerli pdf Color nesnesi alır. |
| [getA](#getA--) | Alfa bileşen değerini alır |
| [getAliceBlue](#getAliceBlue--) | ARGB değeri #FFF0F8FF olan sistem tanımlı rengi alır. |
| [getAntiqueWhite](#getAntiqueWhite--) | ARGB değeri #FFFAEBD7 olan sistem tanımlı rengi alır. |
| [getAqua](#getAqua--) | ARGB değeri #FF00FFFF olan sistem tanımlı rengi alır. |
| [getAquamarine](#getAquamarine--) | ARGB değeri #FF7FFFD4 olan sistem tanımlı rengi alır. |
| [getAzure](#getAzure--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFF0FFFF'dir. |
| [getBeige](#getBeige--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFF5F5DC'dir. |
| [getBisque](#getBisque--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFE4C4'dir. |
| [getBlack](#getBlack--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF000000'dir. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFEBCD'dir. |
| [getBlue](#getBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF0000FF'dir. |
| [getBlueViolet](#getBlueViolet--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF8A2BE2'dir. |
| [getBrown](#getBrown--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFA52A2A'dir. |
| [getBurlyWood](#getBurlyWood--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFDEB887'dir. |
| [getCadetBlue](#getCadetBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF5F9EA0'dir. |
| [getChartreuse](#getChartreuse--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF7FFF00'dir. |
| [getChocolate](#getChocolate--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFD2691E'dir. |
| [getColorSpace](#getColorSpace--) | Rengin temsil ettiği renk uzayını alır. |
| [getCoral](#getCoral--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF7F50'dir. |
| [getCornflowerBlue](#getCornflowerBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF6495ED'dir. |
| [getCornsilk](#getCornsilk--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFF8DC'dir. |
| [getCrimson](#getCrimson--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFDC143C'dir. |
| [getCyan](#getCyan--) | ARGB değeri #FF00FFFF olan sistem tanımlı rengi alır. |
| [getDarkBlue](#getDarkBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF00008B'dir. |
| [getDarkCyan](#getDarkCyan--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF008B8B'dir. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFB8860B'dir. |
| [getDarkGray](#getDarkGray--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFA9A9A9'dir. |
| [getDarkGreen](#getDarkGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF006400'dir. |
| [getDarkKhaki](#getDarkKhaki--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFBDB76B'dir. |
| [getDarkMagenta](#getDarkMagenta--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF8B008B'dir. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF556B2F'dir. |
| [getDarkOrange](#getDarkOrange--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF9932CC. |
| [getDarkRed](#getDarkRed--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF9400D3. |
| [getData](#getData--) | Renk değeri. |
| [getDeepPink](#getDeepPink--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF00BFFF. |
| [getDimGray](#getDimGray--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFB22222. |
| [getFloralWhite](#getFloralWhite--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFAF0. |
| [getForestGreen](#getForestGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF228B22. |
| [getFuchsia](#getFuchsia--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF00FF. |
| [getGainsboro](#getGainsboro--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFDCDCDC. |
| [getGhostWhite](#getGhostWhite--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFF8F8FF. |
| [getGold](#getGold--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFD700. |
| [getGoldenrod](#getGoldenrod--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFDAA520. |
| [getGray](#getGray--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF808080. |
| [getGreen](#getGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF008000. |
| [getGreenYellow](#getGreenYellow--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFADFF2F. |
| [getHoneydew](#getHoneydew--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFF0FFF0 olan. |
| [getHotPink](#getHotPink--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF69B4 olan. |
| [getIndianRed](#getIndianRed--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFCD5C5C olan. |
| [getIndigo](#getIndigo--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF4B0082 olan. |
| [getIvory](#getIvory--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFFF0 olan. |
| [getKhaki](#getKhaki--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFF0E68C olan. |
| [getLavender](#getLavender--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFE6E6FA olan. |
| [getLavenderBlush](#getLavenderBlush--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFF0F5 olan. |
| [getLawnGreen](#getLawnGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF7CFC00 olan. |
| [getLemonChiffon](#getLemonChiffon--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFACD olan. |
| [getLightBlue](#getLightBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFADD8E6 olan. |
| [getLightCoral](#getLightCoral--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFF08080 olan. |
| [getLightCyan](#getLightCyan--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFE0FFFF olan. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFAFAD2 olan. |
| [getLightGray](#getLightGray--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFD3D3D3 olan. |
| [getLightGreen](#getLightGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF90EE90 olan. |
| [getLightPink](#getLightPink--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFB6C1 olan. |
| [getLightSalmon](#getLightSalmon--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFA07A olan. |
| [getLightSeaGreen](#getLightSeaGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF20B2AA olan. |
| [getLightSkyBlue](#getLightSkyBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF87CEFA olan. |
| [getLightSlateGray](#getLightSlateGray--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF778899 olan. |
| [getLightSteelBlue](#getLightSteelBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFB0C4DE olan. |
| [getLightYellow](#getLightYellow--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFFE0 olan. |
| [getLime](#getLime--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF00FF00 olan. |
| [getLimeGreen](#getLimeGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF32CD32 olan. |
| [getLinen](#getLinen--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFFAF0E6. |
| [getMagenta](#getMagenta--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF00FF. |
| [getMaroon](#getMaroon--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF800000. |
| [getMediumAquamarine](#getMediumAquamarine--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF66CDAA. |
| [getMediumBlue](#getMediumBlue--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF0000CD. |
| [getMediumOrchid](#getMediumOrchid--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFBA55D3. |
| [getMediumPurple](#getMediumPurple--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF9370DB. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF3CB371. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF7B68EE. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF00FA9A. |
| [getMediumTurquoise](#getMediumTurquoise--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF48D1CC. |
| [getMediumVioletRed](#getMediumVioletRed--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFC71585. |
| [getMidnightBlue](#getMidnightBlue--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF191970. |
| [getMintCream](#getMintCream--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFF5FFFA. |
| [getMistyRose](#getMistyRose--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFFFE4E1. |
| [getMoccasin](#getMoccasin--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFFFE4B5. |
| [getNavajoWhite](#getNavajoWhite--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFFFDEAD. |
| [getNavy](#getNavy--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF000080. |
| [getOldLace](#getOldLace--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFFDF5E6. |
| [getOlive](#getOlive--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF808000. |
| [getOliveDrab](#getOliveDrab--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF6B8E23. |
| [getOrange](#getOrange--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFFFA500. |
| [getOrangeRed](#getOrangeRed--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFFF4500. |
| [getOrchid](#getOrchid--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFDA70D6. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | Sistem tanımlı bir rengi alır; ARGB değeri #FFEEE8AA. |
| [getPaleGreen](#getPaleGreen--) | Sistem tanımlı bir rengi alır; ARGB değeri #FF98FB98. |
| [getPaleTurquoise](#getPaleTurquoise--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFAFEEEE'dir. |
| [getPaleVioletRed](#getPaleVioletRed--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFDB7093'dür. |
| [getPapayaWhip](#getPapayaWhip--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFEFD5'dir. |
| [getPatternColorSpace](#getPatternColorSpace--) | Deseni renk uzayını gösteren bir nesneyi alır. Yalnızca dahili kullanım. |
| [getPeachPuff](#getPeachPuff--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFDAB9'dur. |
| [getPeru](#getPeru--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFCD853F'dur. |
| [getPink](#getPink--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFC0CB'dir. |
| [getPlum](#getPlum--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFDDA0DD'dir. |
| [getPowderBlue](#getPowderBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFB0E0E6'dır. |
| [getPurple](#getPurple--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF800080'dir. |
| [getRed](#getRed--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF0000'dir. |
| [getRosyBrown](#getRosyBrown--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFBC8F8F'dir. |
| [getRoyalBlue](#getRoyalBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF4169E1'dir. |
| [getSaddleBrown](#getSaddleBrown--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF8B4513'dir. |
| [getSalmon](#getSalmon--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFA8072'dir. |
| [getSandyBrown](#getSandyBrown--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFF4A460'dir. |
| [getSeaGreen](#getSeaGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF2E8B57'dir. |
| [getSeaShell](#getSeaShell--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFF5EE'dir. |
| [getSienna](#getSienna--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFA0522D'dir. |
| [getSilver](#getSilver--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFC0C0C0'dir. |
| [getSkyBlue](#getSkyBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF87CEEB'dir. |
| [getSlateBlue](#getSlateBlue--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF6A5ACD'dir. |
| [getSlateGray](#getSlateGray--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF708090'dir. |
| [getSnow](#getSnow--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFAFA'dir. |
| [getSpringGreen](#getSpringGreen--) | Sistem tanımlı bir rengi alır ve ARGB değeri #FF00FF7F'dir. |
| [getSteelBlue](#getSteelBlue--) | ARGB değeri #FF4682B4 olan sistem tanımlı bir rengi alır. |
| [getTan](#getTan--) | ARGB değeri #FFD2B48C olan sistem tanımlı bir rengi alır. |
| [getTeal](#getTeal--) | ARGB değeri #FF008080 olan sistem tanımlı bir rengi alır. |
| [getThistle](#getThistle--) | ARGB değeri #FFD8BFD8 olan sistem tanımlı bir rengi alır. |
| [getTomato](#getTomato--) | ARGB değeri #FFFF6347 olan sistem tanımlı bir rengi alır. |
| [getTransparent](#getTransparent--) | Sistem tanımlı bir rengi alır. |
| [getTurquoise](#getTurquoise--) | ARGB değeri #FF40E0D0 olan sistem tanımlı bir rengi alır. |
| [getViolet](#getViolet--) | ARGB değeri #FFEE82EE olan sistem tanımlı bir rengi alır. |
| [getWheat](#getWheat--) | ARGB değeri #FFF5DEB3 olan sistem tanımlı bir rengi alır. |
| [getWhite](#getWhite--) | ARGB değeri #FFFFFFFF olan sistem tanımlı bir rengi alır. |
| [getWhiteSmoke](#getWhiteSmoke--) | ARGB değeri #FFF5F5F5 olan sistem tanımlı bir rengi alır. |
| [getYellow](#getYellow--) | ARGB değeri #FFFFFF00 olan sistem tanımlı bir rengi alır. |
| [getYellowGreen](#getYellowGreen--) | ARGB değeri #FF9ACD32 olan sistem tanımlı bir rengi alır. |
| [hashCode](#hashCode--) | Obje için bir hash kodu değeri döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} metodu, nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>İki nesne {@link java.lang.Object#equals(java.lang.Object)} metoduna göre eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı, eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde uygulanabilir olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode metodu, farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style=\"font-size:70%\"><sup>TM</sup></span>programlama dili tarafından zorunlu kılınmamıştır.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | İki Colors eşitse true döndürür. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | İki Renk eşit değilse true döndürür. |
| [parse](#parse-java.lang.String-) | Dizeden renk bileşenlerini ayıklar. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Desen renk uzayını belirten bir nesneyi ayarlar. Yalnızca dahili kullanım. |
| [toRgb](#toRgb--) | Rengi rgb'ye dönüştürür. |
| [toString](#toString--) | Dizeye dönüştürür. |

### Default {#Default}
```
public static final Color Default
```

Varsayılan rengi temsil eder.

### Empty {#Empty}
```
public static final Color Empty
```

Boş rengi temsil eder.

### Color {#Color--}
```
public Color()
```

Varsayılan yapıcı.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

Yapıcı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vektör |  | double[] dizi |

### deepClone {#deepClone--}
```
public Color deepClone()
```

Bu örneği kopyalar

**Returns:**
Color nesnesi

### equals {#equals-java.lang.Object-}
İki Colors eşitse true döndürür.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

RGB renk bileşenlerinden geçerli pdf Color nesnesi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r |  | Kırmızı renk bileşeni (değer 0 - 255). |
| g |  | Yeşil renk bileşeni (değer 0 - 255). |
| b |  | Mavi renk bileşeni (değer 0 - 255). |

**Returns:**
Her bileşen değeri [0..255] aralığında olan Renk nesnesi.

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

RGB renk bileşenlerinden geçerli pdf Color nesnesi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a |  | Alfa bileşen değeri (değer 0 - 255). |
| r |  | Kırmızı renk bileşeni (değer 0 - 255). |
| g |  | Yeşil renk bileşeni (değer 0 - 255). |
| b |  | Mavi renk bileşeni (değer 0 - 255). |

**Returns:**
Her bileşen değeri [0..255] aralığında olan Renk nesnesi.

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

CMYK renk bileşenlerinden geçerli pdf Color nesnesi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c |  | Camgöbeği renk bileşeni (değer 0 - 1). |
| m |  | Macenta renk bileşeni (değer 0 - 1). |
| y |  | Sarı renk bileşeni (değer 0 - 1). |
| k |  | Key renk bileşeni (değer 0 - 1). |

**Returns:**
Her bileşen değeri [0..1] aralığında olan Renk nesnesi.

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Gri renk bileşeninden geçerli pdf Color nesnesi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g |  | Gri renk bileşeni (değer 0 - 1). |

**Returns:**
Her bileşen değeri [0..1] aralığında olan Renk nesnesi.

### fromRgb {#fromRgb-java.awt.Color-}
java.awt.Color değerinden geçerli pdf Color nesnesi alır.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

RGB renk bileşenlerinden geçerli pdf Color nesnesi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r |  | Kırmızı renk bileşeni (değer 0 - 1). |
| g |  | Yeşil renk bileşeni (değer 0 - 1). |
| b |  | Mavi renk bileşeni (değer 0 - 1). |

**Returns:**
Her bileşen değeri [0..1] aralığında olan Renk nesnesi.

### getA {#getA--}
```
public double getA()
```

Alfa bileşen değerini alır

**Returns:**
double değer

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

ARGB değeri #FFF0F8FF olan sistem tanımlı rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

ARGB değeri #FFFAEBD7 olan sistem tanımlı rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

ARGB değeri #FF00FFFF olan sistem tanımlı rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

ARGB değeri #FF7FFFD4 olan sistem tanımlı rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFF0FFFF'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFF5F5DC'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFE4C4'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF000000'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFEBCD'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF0000FF'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF8A2BE2'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFA52A2A'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFDEB887'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF5F9EA0'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF7FFF00'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFD2691E'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Rengin temsil ettiği renk uzayını alır.

**Returns:**
ColorSpace nesnesi

### getCoral {#getCoral--}
```
public static Color getCoral()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF7F50'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF6495ED'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFF8DC'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFDC143C'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

ARGB değeri #FF00FFFF olan sistem tanımlı rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF00008B'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF008B8B'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFB8860B'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFA9A9A9'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF006400'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFBDB76B'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF8B008B'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF556B2F'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF8C00.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF9932CC.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF8B0000.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFE9967A.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF8FBC8F.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF483D8B.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF2F4F4F.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF00CED1.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF9400D3.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getData {#getData--}
```
public double[] getData()
```

Renk değeri.

**Returns:**
double değerlerden oluşan dizi

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF1493.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF00BFFF.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF696969.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF1E90FF.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFB22222.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFAF0.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF228B22.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF00FF.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFDCDCDC.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFF8F8FF.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getGold {#getGold--}
```
public static Color getGold()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFD700.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFDAA520.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getGray {#getGray--}
```
public static Color getGray()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF808080.

**Returns:**
Sistem tanımlı bir rengi temsil eden A yapısı.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF008000.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFADFF2F.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFF0FFF0 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF69B4 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFCD5C5C olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF4B0082 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFFF0 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFF0E68C olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFE6E6FA olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFF0F5 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF7CFC00 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFACD olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFADD8E6 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFF08080 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFE0FFFF olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFAFAD2 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFD3D3D3 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF90EE90 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFB6C1 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFA07A olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF20B2AA olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF87CEFA olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF778899 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFB0C4DE olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFFE0 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLime {#getLime--}
```
public static Color getLime()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF00FF00 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF32CD32 olan.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFFAF0E6.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF00FF.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF800000.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF66CDAA.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF0000CD.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFBA55D3.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF9370DB.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF3CB371.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF7B68EE.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF00FA9A.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF48D1CC.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFC71585.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF191970.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFF5FFFA.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFFFE4E1.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFFFE4B5.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFFFDEAD.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF000080.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFFDF5E6.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF808000.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF6B8E23.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFFFA500.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFFF4500.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFDA70D6.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FFEEE8AA.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

Sistem tanımlı bir rengi alır; ARGB değeri #FF98FB98.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFAFEEEE'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFDB7093'dür.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFEFD5'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

Deseni renk uzayını gösteren bir nesneyi alır. Yalnızca dahili kullanım.

**Returns:**
PatternColorSpace nesnesi

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFDAB9'dur.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFCD853F'dur.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPink {#getPink--}
```
public static Color getPink()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFC0CB'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFDDA0DD'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFB0E0E6'dır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF800080'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getRed {#getRed--}
```
public static Color getRed()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFF0000'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFBC8F8F'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF4169E1'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF8B4513'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFA8072'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFF4A460'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF2E8B57'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFF5EE'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFA0522D'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFC0C0C0'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF87CEEB'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF6A5ACD'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF708090'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FFFFFAFA'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

Sistem tanımlı bir rengi alır ve ARGB değeri #FF00FF7F'dir.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

ARGB değeri #FF4682B4 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getTan {#getTan--}
```
public static Color getTan()
```

ARGB değeri #FFD2B48C olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

ARGB değeri #FF008080 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

ARGB değeri #FFD8BFD8 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

ARGB değeri #FFFF6347 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

Sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

ARGB değeri #FF40E0D0 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

ARGB değeri #FFEE82EE olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

ARGB değeri #FFF5DEB3 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

ARGB değeri #FFFFFFFF olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

ARGB değeri #FFF5F5F5 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

ARGB değeri #FFFFFF00 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

ARGB değeri #FF9ACD32 olan sistem tanımlı bir rengi alır.

**Returns:**
Sistem tanımlı bir rengi temsil eden A.

### hashCode {#hashCode--}
```
public int hashCode()
```

Obje için bir hash kodu değeri döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} metodu, nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>İki nesne {@link java.lang.Object#equals(java.lang.Object)} metoduna göre eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı, eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde uygulanabilir olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode metodu, farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style=\"font-size:70%\"><sup>TM</sup></span>programlama dili tarafından zorunlu kılınmamıştır.)

**Returns:**
bu nesne için bir hash kodu değeri. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
İki Colors eşitse true döndürür.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
İki Renk eşit değilse true döndürür.

### parse {#parse-java.lang.String-}
Dizeden renk bileşenlerini ayıklar.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
Desen renk uzayını belirten bir nesneyi ayarlar. Yalnızca dahili kullanım.

### toRgb {#toRgb--}
```
public Color toRgb()
```

Rengi rgb'ye dönüştürür.

**Returns:**
Rgb renk değeri.

### toString {#toString--}
```
public String toString()
```

Dizeye dönüştürür.

**Returns:**
Renk nesnesinin dize temsili.
