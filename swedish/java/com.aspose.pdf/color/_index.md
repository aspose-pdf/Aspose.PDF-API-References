---
title: "Färg"
linktitle: "Färg"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för färgvärde som kan uttryckas i olika färgrymder."
type: docs
weight: 670
url: /sv/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

Representerar en klass för färgvärde som kan uttryckas i olika färgrymder.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Default](#Default) | Representerar standardfärgen. |
| [Empty](#Empty) | Representerar tom färg. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Color](#Color--) | Standardkonstruktor. |
| [Color](#Color-double:A-) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klonar detta objekt |
| [equals](#equals-java.lang.Object-) | Returnerar true om två färger är lika. |
| [fromArgb](#fromArgb-int-int-int-) | Hämtar ett giltigt pdf‑färgobjekt från RGB‑färgkomponenter. |
| [fromArgb](#fromArgb-int-int-int-int-) | Hämtar ett giltigt pdf‑färgobjekt från RGB‑färgkomponenter. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | Hämtar ett giltigt pdf‑färgobjekt från CMYK‑färgkomponenter. |
| [fromGray](#fromGray-double-) | Hämtar ett giltigt pdf‑färgobjekt från grå färgkomponent. |
| [fromRgb](#fromRgb-java.awt.Color-) | Hämtar ett giltigt pdf‑färgobjekt från java.awt.Color‑värde. |
| [fromRgb](#fromRgb-double-double-double-) | Hämtar ett giltigt pdf‑färgobjekt från RGB‑färgkomponenter. |
| [getA](#getA--) | Hämtar alfakomponentens värde |
| [getAliceBlue](#getAliceBlue--) | Hämtar ett systemdefinierat färgvärde med ARGB‑värdet #FFF0F8FF. |
| [getAntiqueWhite](#getAntiqueWhite--) | Hämtar ett systemdefinierat färgvärde med ARGB‑värdet #FFFAEBD7. |
| [getAqua](#getAqua--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FFFF. |
| [getAquamarine](#getAquamarine--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF7FFFD4. |
| [getAzure](#getAzure--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF0FFFF. |
| [getBeige](#getBeige--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF5F5DC. |
| [getBisque](#getBisque--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFE4C4. |
| [getBlack](#getBlack--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF000000. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFEBCD. |
| [getBlue](#getBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF0000FF. |
| [getBlueViolet](#getBlueViolet--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8A2BE2. |
| [getBrown](#getBrown--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFA52A2A. |
| [getBurlyWood](#getBurlyWood--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDEB887. |
| [getCadetBlue](#getCadetBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF5F9EA0. |
| [getChartreuse](#getChartreuse--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF7FFF00. |
| [getChocolate](#getChocolate--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFD2691E. |
| [getColorSpace](#getColorSpace--) | Hämtar färgrymden som färgen representerar. |
| [getCoral](#getCoral--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF7F50. |
| [getCornflowerBlue](#getCornflowerBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF6495ED. |
| [getCornsilk](#getCornsilk--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFF8DC. |
| [getCrimson](#getCrimson--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDC143C. |
| [getCyan](#getCyan--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FFFF. |
| [getDarkBlue](#getDarkBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00008B. |
| [getDarkCyan](#getDarkCyan--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF008B8B. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFB8860B. |
| [getDarkGray](#getDarkGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFA9A9A9. |
| [getDarkGreen](#getDarkGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF006400. |
| [getDarkKhaki](#getDarkKhaki--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFBDB76B. |
| [getDarkMagenta](#getDarkMagenta--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8B008B. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF556B2F. |
| [getDarkOrange](#getDarkOrange--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF9932CC. |
| [getDarkRed](#getDarkRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF9400D3. |
| [getData](#getData--) | Färgvärde. |
| [getDeepPink](#getDeepPink--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00BFFF. |
| [getDimGray](#getDimGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFB22222. |
| [getFloralWhite](#getFloralWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFAF0. |
| [getForestGreen](#getForestGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF228B22. |
| [getFuchsia](#getFuchsia--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF00FF. |
| [getGainsboro](#getGainsboro--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDCDCDC. |
| [getGhostWhite](#getGhostWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF8F8FF. |
| [getGold](#getGold--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFD700. |
| [getGoldenrod](#getGoldenrod--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDAA520. |
| [getGray](#getGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF808080. |
| [getGreen](#getGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF008000. |
| [getGreenYellow](#getGreenYellow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFADFF2F. |
| [getHoneydew](#getHoneydew--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF0FFF0. |
| [getHotPink](#getHotPink--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF69B4. |
| [getIndianRed](#getIndianRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFCD5C5C. |
| [getIndigo](#getIndigo--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF4B0082. |
| [getIvory](#getIvory--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFFF0. |
| [getKhaki](#getKhaki--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF0E68C. |
| [getLavender](#getLavender--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFE6E6FA. |
| [getLavenderBlush](#getLavenderBlush--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFF0F5. |
| [getLawnGreen](#getLawnGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF7CFC00. |
| [getLemonChiffon](#getLemonChiffon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFACD. |
| [getLightBlue](#getLightBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFADD8E6. |
| [getLightCoral](#getLightCoral--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF08080. |
| [getLightCyan](#getLightCyan--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFE0FFFF. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFAFAD2. |
| [getLightGray](#getLightGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFD3D3D3. |
| [getLightGreen](#getLightGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF90EE90. |
| [getLightPink](#getLightPink--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFB6C1. |
| [getLightSalmon](#getLightSalmon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFA07A. |
| [getLightSeaGreen](#getLightSeaGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF20B2AA. |
| [getLightSkyBlue](#getLightSkyBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF87CEFA. |
| [getLightSlateGray](#getLightSlateGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF778899. |
| [getLightSteelBlue](#getLightSteelBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFB0C4DE. |
| [getLightYellow](#getLightYellow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFFE0. |
| [getLime](#getLime--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FF00. |
| [getLimeGreen](#getLimeGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF32CD32. |
| [getLinen](#getLinen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFAF0E6. |
| [getMagenta](#getMagenta--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF00FF. |
| [getMaroon](#getMaroon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF800000. |
| [getMediumAquamarine](#getMediumAquamarine--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF66CDAA. |
| [getMediumBlue](#getMediumBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF0000CD. |
| [getMediumOrchid](#getMediumOrchid--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFBA55D3. |
| [getMediumPurple](#getMediumPurple--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF9370DB. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF3CB371. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF7B68EE. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FA9A. |
| [getMediumTurquoise](#getMediumTurquoise--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF48D1CC. |
| [getMediumVioletRed](#getMediumVioletRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFC71585. |
| [getMidnightBlue](#getMidnightBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF191970. |
| [getMintCream](#getMintCream--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF5FFFA. |
| [getMistyRose](#getMistyRose--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFE4E1. |
| [getMoccasin](#getMoccasin--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFE4B5. |
| [getNavajoWhite](#getNavajoWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFDEAD. |
| [getNavy](#getNavy--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF000080. |
| [getOldLace](#getOldLace--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFDF5E6. |
| [getOlive](#getOlive--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF808000. |
| [getOliveDrab](#getOliveDrab--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF6B8E23. |
| [getOrange](#getOrange--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFA500. |
| [getOrangeRed](#getOrangeRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF4500. |
| [getOrchid](#getOrchid--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDA70D6. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFEEE8AA. |
| [getPaleGreen](#getPaleGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF98FB98. |
| [getPaleTurquoise](#getPaleTurquoise--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFAFEEEE. |
| [getPaleVioletRed](#getPaleVioletRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDB7093. |
| [getPapayaWhip](#getPapayaWhip--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFEFD5. |
| [getPatternColorSpace](#getPatternColorSpace--) | Hämtar ett objekt som indikerar mönsterfärgrymden. Endast för internt bruk. |
| [getPeachPuff](#getPeachPuff--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFDAB9. |
| [getPeru](#getPeru--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFCD853F. |
| [getPink](#getPink--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFC0CB. |
| [getPlum](#getPlum--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDDA0DD. |
| [getPowderBlue](#getPowderBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFB0E0E6. |
| [getPurple](#getPurple--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF800080. |
| [getRed](#getRed--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF0000. |
| [getRosyBrown](#getRosyBrown--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFBC8F8F. |
| [getRoyalBlue](#getRoyalBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF4169E1. |
| [getSaddleBrown](#getSaddleBrown--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8B4513. |
| [getSalmon](#getSalmon--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFA8072. |
| [getSandyBrown](#getSandyBrown--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF4A460. |
| [getSeaGreen](#getSeaGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF2E8B57. |
| [getSeaShell](#getSeaShell--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFF5EE. |
| [getSienna](#getSienna--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFA0522D. |
| [getSilver](#getSilver--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFC0C0C0. |
| [getSkyBlue](#getSkyBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF87CEEB. |
| [getSlateBlue](#getSlateBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF6A5ACD. |
| [getSlateGray](#getSlateGray--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF708090. |
| [getSnow](#getSnow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFAFA. |
| [getSpringGreen](#getSpringGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FF7F. |
| [getSteelBlue](#getSteelBlue--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF4682B4. |
| [getTan](#getTan--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFD2B48C. |
| [getTeal](#getTeal--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF008080. |
| [getThistle](#getThistle--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFD8BFD8. |
| [getTomato](#getTomato--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF6347. |
| [getTransparent](#getTransparent--) | Hämtar en systemdefinierad färg. |
| [getTurquoise](#getTurquoise--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF40E0D0. |
| [getViolet](#getViolet--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFEE82EE. |
| [getWheat](#getWheat--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF5DEB3. |
| [getWhite](#getWhite--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFFFF. |
| [getWhiteSmoke](#getWhiteSmoke--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF5F5F5. |
| [getYellow](#getYellow--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFF00. |
| [getYellowGreen](#getYellowGreen--) | Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF9ACD32. |
| [hashCode](#hashCode--) | Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är olika enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera distinkta heltalsresultat. Däremot bör programmeraren vara medveten om att producera distinkta heltalsresultat för olika objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} distinkta heltal för distinkta objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style="font-size:70%"><sup>TM</sup></span>programspråket.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Returnerar true om två färger är lika. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Returnerar true om två Colors inte är lika. |
| [parse](#parse-java.lang.String-) | Extraherar färgkomponenter från strängen. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Ställer in ett objekt som indikerar mönstrets färgrymd. Endast för internt bruk |
| [toRgb](#toRgb--) | Konverterar färg till rgb. |
| [toString](#toString--) | Konverterar till sträng. |

### Default {#Default}
```
public static final Color Default
```

Representerar standardfärgen.

### Empty {#Empty}
```
public static final Color Empty
```

Representerar tom färg.

### Color {#Color--}
```
public Color()
```

Standardkonstruktor.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

Konstruktör

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vektor |  | double[] array |

### deepClone {#deepClone--}
```
public Color deepClone()
```

Klonar detta objekt

**Returns:**
Color‑objekt

### equals {#equals-java.lang.Object-}
Returnerar true om två färger är lika.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

Hämtar ett giltigt pdf‑färgobjekt från RGB‑färgkomponenter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r |  | Den röda färgkomponenten (värde 0 - 255). |
| g |  | Den gröna färgkomponenten (värde 0 - 255). |
| b |  | Den blå färgkomponenten (värde 0 - 255). |

**Returns:**
Färgobjekt med varje komponentvärde i intervallet [0..255].

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

Hämtar ett giltigt pdf‑färgobjekt från RGB‑färgkomponenter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a |  | Alfakomponentvärdet (värde 0 - 255). |
| r |  | Den röda färgkomponenten (värde 0 - 255). |
| g |  | Den gröna färgkomponenten (värde 0 - 255). |
| b |  | Den blå färgkomponenten (värde 0 - 255). |

**Returns:**
Färgobjekt med varje komponentvärde i intervallet [0..255].

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

Hämtar ett giltigt pdf‑färgobjekt från CMYK‑färgkomponenter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c |  | Den cyanfärgkomponenten (värde 0 - 1). |
| m |  | Den magentafärgkomponenten (värde 0 - 1). |
| y |  | Den gula färgkomponenten (värde 0 - 1). |
| k |  | Den nyckelfärgkomponenten (värde 0 - 1). |

**Returns:**
Färgobjekt med varje komponentvärde i intervallet [0..1].

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Hämtar ett giltigt pdf‑färgobjekt från grå färgkomponent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g |  | Den grå färgkomponenten (värde 0 - 1). |

**Returns:**
Färgobjekt med varje komponentvärde i intervallet [0..1].

### fromRgb {#fromRgb-java.awt.Color-}
Hämtar ett giltigt pdf‑färgobjekt från java.awt.Color‑värde.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

Hämtar ett giltigt pdf‑färgobjekt från RGB‑färgkomponenter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r |  | Den röda färgkomponenten (värde 0 - 1). |
| g |  | Den gröna färgkomponenten (värde 0 - 1). |
| b |  | Den blå färgkomponenten (värde 0 - 1). |

**Returns:**
Färgobjekt med varje komponentvärde i intervallet [0..1].

### getA {#getA--}
```
public double getA()
```

Hämtar alfakomponentens värde

**Returns:**
double-värde

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

Hämtar ett systemdefinierat färgvärde med ARGB‑värdet #FFF0F8FF.

**Returns:**
En som representerar en systemdefinierad färg.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

Hämtar ett systemdefinierat färgvärde med ARGB‑värdet #FFFAEBD7.

**Returns:**
En som representerar en systemdefinierad färg.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FFFF.

**Returns:**
En som representerar en systemdefinierad färg.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF7FFFD4.

**Returns:**
En som representerar en systemdefinierad färg.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF0FFFF.

**Returns:**
En som representerar en systemdefinierad färg.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF5F5DC.

**Returns:**
En som representerar en systemdefinierad färg.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFE4C4.

**Returns:**
En som representerar en systemdefinierad färg.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF000000.

**Returns:**
En som representerar en systemdefinierad färg.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFEBCD.

**Returns:**
En som representerar en systemdefinierad färg.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF0000FF.

**Returns:**
En som representerar en systemdefinierad färg.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8A2BE2.

**Returns:**
En som representerar en systemdefinierad färg.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFA52A2A.

**Returns:**
En som representerar en systemdefinierad färg.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDEB887.

**Returns:**
En som representerar en systemdefinierad färg.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF5F9EA0.

**Returns:**
En som representerar en systemdefinierad färg.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF7FFF00.

**Returns:**
En som representerar en systemdefinierad färg.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFD2691E.

**Returns:**
En som representerar en systemdefinierad färg.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Hämtar färgrymden som färgen representerar.

**Returns:**
ColorSpace-objekt

### getCoral {#getCoral--}
```
public static Color getCoral()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF7F50.

**Returns:**
En som representerar en systemdefinierad färg.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF6495ED.

**Returns:**
En som representerar en systemdefinierad färg.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFF8DC.

**Returns:**
En som representerar en systemdefinierad färg.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDC143C.

**Returns:**
En som representerar en systemdefinierad färg.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FFFF.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00008B.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF008B8B.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFB8860B.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFA9A9A9.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF006400.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFBDB76B.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8B008B.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF556B2F.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF8C00.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF9932CC.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8B0000.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFE9967A.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8FBC8F.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF483D8B.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF2F4F4F.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00CED1.

**Returns:**
En som representerar en systemdefinierad färg.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF9400D3.

**Returns:**
En som representerar en systemdefinierad färg.

### getData {#getData--}
```
public double[] getData()
```

Färgvärde.

**Returns:**
array av doublevärden

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF1493.

**Returns:**
En som representerar en systemdefinierad färg.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00BFFF.

**Returns:**
En som representerar en systemdefinierad färg.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF696969.

**Returns:**
En som representerar en systemdefinierad färg.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF1E90FF.

**Returns:**
En som representerar en systemdefinierad färg.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFB22222.

**Returns:**
En som representerar en systemdefinierad färg.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFAF0.

**Returns:**
En som representerar en systemdefinierad färg.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF228B22.

**Returns:**
En som representerar en systemdefinierad färg.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF00FF.

**Returns:**
En som representerar en systemdefinierad färg.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDCDCDC.

**Returns:**
En som representerar en systemdefinierad färg.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF8F8FF.

**Returns:**
En som representerar en systemdefinierad färg.

### getGold {#getGold--}
```
public static Color getGold()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFD700.

**Returns:**
En som representerar en systemdefinierad färg.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDAA520.

**Returns:**
En som representerar en systemdefinierad färg.

### getGray {#getGray--}
```
public static Color getGray()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF808080.

**Returns:**
En struktur som representerar en systemdefinierad färg.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF008000.

**Returns:**
En som representerar en systemdefinierad färg.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFADFF2F.

**Returns:**
En som representerar en systemdefinierad färg.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF0FFF0.

**Returns:**
En som representerar en systemdefinierad färg.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF69B4.

**Returns:**
En som representerar en systemdefinierad färg.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFCD5C5C.

**Returns:**
En som representerar en systemdefinierad färg.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF4B0082.

**Returns:**
En som representerar en systemdefinierad färg.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFFF0.

**Returns:**
En som representerar en systemdefinierad färg.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF0E68C.

**Returns:**
En som representerar en systemdefinierad färg.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFE6E6FA.

**Returns:**
En som representerar en systemdefinierad färg.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFF0F5.

**Returns:**
En som representerar en systemdefinierad färg.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF7CFC00.

**Returns:**
En som representerar en systemdefinierad färg.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFACD.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFADD8E6.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF08080.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFE0FFFF.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFAFAD2.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFD3D3D3.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF90EE90.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFB6C1.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFA07A.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF20B2AA.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF87CEFA.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF778899.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFB0C4DE.

**Returns:**
En som representerar en systemdefinierad färg.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFFE0.

**Returns:**
En som representerar en systemdefinierad färg.

### getLime {#getLime--}
```
public static Color getLime()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FF00.

**Returns:**
En som representerar en systemdefinierad färg.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF32CD32.

**Returns:**
En som representerar en systemdefinierad färg.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFAF0E6.

**Returns:**
En som representerar en systemdefinierad färg.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF00FF.

**Returns:**
En som representerar en systemdefinierad färg.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF800000.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF66CDAA.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF0000CD.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFBA55D3.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF9370DB.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF3CB371.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF7B68EE.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FA9A.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF48D1CC.

**Returns:**
En som representerar en systemdefinierad färg.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFC71585.

**Returns:**
En som representerar en systemdefinierad färg.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF191970.

**Returns:**
En som representerar en systemdefinierad färg.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF5FFFA.

**Returns:**
En som representerar en systemdefinierad färg.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFE4E1.

**Returns:**
En som representerar en systemdefinierad färg.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFE4B5.

**Returns:**
En som representerar en systemdefinierad färg.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFDEAD.

**Returns:**
En som representerar en systemdefinierad färg.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF000080.

**Returns:**
En som representerar en systemdefinierad färg.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFDF5E6.

**Returns:**
En som representerar en systemdefinierad färg.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF808000.

**Returns:**
En som representerar en systemdefinierad färg.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF6B8E23.

**Returns:**
En som representerar en systemdefinierad färg.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFA500.

**Returns:**
En som representerar en systemdefinierad färg.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF4500.

**Returns:**
En som representerar en systemdefinierad färg.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDA70D6.

**Returns:**
En som representerar en systemdefinierad färg.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFEEE8AA.

**Returns:**
En som representerar en systemdefinierad färg.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF98FB98.

**Returns:**
En som representerar en systemdefinierad färg.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFAFEEEE.

**Returns:**
En som representerar en systemdefinierad färg.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDB7093.

**Returns:**
En som representerar en systemdefinierad färg.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFEFD5.

**Returns:**
En som representerar en systemdefinierad färg.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

Hämtar ett objekt som indikerar mönsterfärgrymden. Endast för internt bruk.

**Returns:**
PatternColorSpace-objekt

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFDAB9.

**Returns:**
En som representerar en systemdefinierad färg.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFCD853F.

**Returns:**
En som representerar en systemdefinierad färg.

### getPink {#getPink--}
```
public static Color getPink()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFC0CB.

**Returns:**
En som representerar en systemdefinierad färg.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFDDA0DD.

**Returns:**
En som representerar en systemdefinierad färg.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFB0E0E6.

**Returns:**
En som representerar en systemdefinierad färg.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF800080.

**Returns:**
En som representerar en systemdefinierad färg.

### getRed {#getRed--}
```
public static Color getRed()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF0000.

**Returns:**
En som representerar en systemdefinierad färg.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFBC8F8F.

**Returns:**
En som representerar en systemdefinierad färg.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF4169E1.

**Returns:**
En som representerar en systemdefinierad färg.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF8B4513.

**Returns:**
En som representerar en systemdefinierad färg.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFA8072.

**Returns:**
En som representerar en systemdefinierad färg.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF4A460.

**Returns:**
En som representerar en systemdefinierad färg.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF2E8B57.

**Returns:**
En som representerar en systemdefinierad färg.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFF5EE.

**Returns:**
En som representerar en systemdefinierad färg.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFA0522D.

**Returns:**
En som representerar en systemdefinierad färg.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFC0C0C0.

**Returns:**
En som representerar en systemdefinierad färg.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF87CEEB.

**Returns:**
En som representerar en systemdefinierad färg.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF6A5ACD.

**Returns:**
En som representerar en systemdefinierad färg.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF708090.

**Returns:**
En som representerar en systemdefinierad färg.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFAFA.

**Returns:**
En som representerar en systemdefinierad färg.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF00FF7F.

**Returns:**
En som representerar en systemdefinierad färg.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF4682B4.

**Returns:**
En som representerar en systemdefinierad färg.

### getTan {#getTan--}
```
public static Color getTan()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFD2B48C.

**Returns:**
En som representerar en systemdefinierad färg.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF008080.

**Returns:**
En som representerar en systemdefinierad färg.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFD8BFD8.

**Returns:**
En som representerar en systemdefinierad färg.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFF6347.

**Returns:**
En som representerar en systemdefinierad färg.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

Hämtar en systemdefinierad färg.

**Returns:**
En som representerar en systemdefinierad färg.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF40E0D0.

**Returns:**
En som representerar en systemdefinierad färg.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFEE82EE.

**Returns:**
En som representerar en systemdefinierad färg.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF5DEB3.

**Returns:**
En som representerar en systemdefinierad färg.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFFFF.

**Returns:**
En som representerar en systemdefinierad färg.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFF5F5F5.

**Returns:**
En som representerar en systemdefinierad färg.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FFFFFF00.

**Returns:**
En som representerar en systemdefinierad färg.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

Hämtar en systemdefinierad färg som har ett ARGB‑värde på #FF9ACD32.

**Returns:**
En som representerar en systemdefinierad färg.

### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är olika enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera distinkta heltalsresultat. Däremot bör programmeraren vara medveten om att producera distinkta heltalsresultat för olika objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} distinkta heltal för distinkta objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style="font-size:70%"><sup>TM</sup></span>programspråket.)

**Returns:**
ett hash‑kodvärde för detta objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Returnerar true om två färger är lika.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Returnerar true om två Colors inte är lika.

### parse {#parse-java.lang.String-}
Extraherar färgkomponenter från strängen.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
Ställer in ett objekt som indikerar mönstrets färgrymd. Endast för internt bruk

### toRgb {#toRgb--}
```
public Color toRgb()
```

Konverterar färg till rgb.

**Returns:**
Rgb-färgvärde.

### toString {#toString--}
```
public String toString()
```

Konverterar till sträng.

**Returns:**
Strängrepresentation av Color-objektet.
