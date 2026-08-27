---
title: "Colore"
linktitle: "Colore"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per valore di colore che può essere espresso in diversi spazi colore."
type: docs
weight: 670
url: /it/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

Rappresenta una classe per valore di colore che può essere espresso in diversi spazi colore.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Default](#Default) | Rappresenta il colore predefinito. |
| [Empty](#Empty) | Rappresenta il colore vuoto. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Color](#Color--) | Costruttore predefinito. |
| [Color](#Color-double:A-) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona questa istanza |
| [equals](#equals-java.lang.Object-) | Restituisce true se due colori sono uguali. |
| [fromArgb](#fromArgb-int-int-int-) | Ottiene un oggetto Color PDF valido dai componenti di colore RGB. |
| [fromArgb](#fromArgb-int-int-int-int-) | Ottiene un oggetto Color PDF valido dai componenti di colore RGB. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | Ottiene un oggetto Color PDF valido dai componenti di colore CMYK. |
| [fromGray](#fromGray-double-) | Ottiene un oggetto Color PDF valido dal componente di colore grigio. |
| [fromRgb](#fromRgb-java.awt.Color-) | Ottiene un oggetto Color PDF valido dal valore java.awt.Color. |
| [fromRgb](#fromRgb-double-double-double-) | Ottiene un oggetto Color PDF valido dai componenti di colore RGB. |
| [getA](#getA--) | Ottiene il valore del componente alfa |
| [getAliceBlue](#getAliceBlue--) | Restituisce un colore definito dal sistema con valore ARGB #FFF0F8FF. |
| [getAntiqueWhite](#getAntiqueWhite--) | Restituisce un colore definito dal sistema con valore ARGB #FFFAEBD7. |
| [getAqua](#getAqua--) | Restituisce un colore definito dal sistema con valore ARGB #FF00FFFF. |
| [getAquamarine](#getAquamarine--) | Restituisce un colore definito dal sistema con valore ARGB #FF7FFFD4. |
| [getAzure](#getAzure--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF0FFFF. |
| [getBeige](#getBeige--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF5F5DC. |
| [getBisque](#getBisque--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFE4C4. |
| [getBlack](#getBlack--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF000000. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFEBCD. |
| [getBlue](#getBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF0000FF. |
| [getBlueViolet](#getBlueViolet--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8A2BE2. |
| [getBrown](#getBrown--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFA52A2A. |
| [getBurlyWood](#getBurlyWood--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDEB887. |
| [getCadetBlue](#getCadetBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF5F9EA0. |
| [getChartreuse](#getChartreuse--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF7FFF00. |
| [getChocolate](#getChocolate--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFD2691E. |
| [getColorSpace](#getColorSpace--) | Ottiene lo spazio colore che il colore rappresenta. |
| [getCoral](#getCoral--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF7F50. |
| [getCornflowerBlue](#getCornflowerBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF6495ED. |
| [getCornsilk](#getCornsilk--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFF8DC. |
| [getCrimson](#getCrimson--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDC143C. |
| [getCyan](#getCyan--) | Restituisce un colore definito dal sistema con valore ARGB #FF00FFFF. |
| [getDarkBlue](#getDarkBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00008B. |
| [getDarkCyan](#getDarkCyan--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF008B8B. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFB8860B. |
| [getDarkGray](#getDarkGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFA9A9A9. |
| [getDarkGreen](#getDarkGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF006400. |
| [getDarkKhaki](#getDarkKhaki--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFBDB76B. |
| [getDarkMagenta](#getDarkMagenta--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8B008B. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF556B2F. |
| [getDarkOrange](#getDarkOrange--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF9932CC. |
| [getDarkRed](#getDarkRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF9400D3. |
| [getData](#getData--) | Valore colore. |
| [getDeepPink](#getDeepPink--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00BFFF. |
| [getDimGray](#getDimGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFB22222. |
| [getFloralWhite](#getFloralWhite--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFAF0. |
| [getForestGreen](#getForestGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF228B22. |
| [getFuchsia](#getFuchsia--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF00FF. |
| [getGainsboro](#getGainsboro--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDCDCDC. |
| [getGhostWhite](#getGhostWhite--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF8F8FF. |
| [getGold](#getGold--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFD700. |
| [getGoldenrod](#getGoldenrod--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDAA520. |
| [getGray](#getGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF808080. |
| [getGreen](#getGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF008000. |
| [getGreenYellow](#getGreenYellow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFADFF2F. |
| [getHoneydew](#getHoneydew--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF0FFF0. |
| [getHotPink](#getHotPink--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF69B4. |
| [getIndianRed](#getIndianRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFCD5C5C. |
| [getIndigo](#getIndigo--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF4B0082. |
| [getIvory](#getIvory--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFFF0. |
| [getKhaki](#getKhaki--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF0E68C. |
| [getLavender](#getLavender--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFE6E6FA. |
| [getLavenderBlush](#getLavenderBlush--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFF0F5. |
| [getLawnGreen](#getLawnGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF7CFC00. |
| [getLemonChiffon](#getLemonChiffon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFACD. |
| [getLightBlue](#getLightBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFADD8E6. |
| [getLightCoral](#getLightCoral--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF08080. |
| [getLightCyan](#getLightCyan--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFE0FFFF. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFAFAD2. |
| [getLightGray](#getLightGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFD3D3D3. |
| [getLightGreen](#getLightGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF90EE90. |
| [getLightPink](#getLightPink--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFB6C1. |
| [getLightSalmon](#getLightSalmon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFA07A. |
| [getLightSeaGreen](#getLightSeaGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF20B2AA. |
| [getLightSkyBlue](#getLightSkyBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF87CEFA. |
| [getLightSlateGray](#getLightSlateGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF778899. |
| [getLightSteelBlue](#getLightSteelBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFB0C4DE. |
| [getLightYellow](#getLightYellow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFFE0. |
| [getLime](#getLime--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00FF00. |
| [getLimeGreen](#getLimeGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF32CD32. |
| [getLinen](#getLinen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFAF0E6. |
| [getMagenta](#getMagenta--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF00FF. |
| [getMaroon](#getMaroon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF800000. |
| [getMediumAquamarine](#getMediumAquamarine--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF66CDAA. |
| [getMediumBlue](#getMediumBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF0000CD. |
| [getMediumOrchid](#getMediumOrchid--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFBA55D3. |
| [getMediumPurple](#getMediumPurple--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF9370DB. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF3CB371. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF7B68EE. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00FA9A. |
| [getMediumTurquoise](#getMediumTurquoise--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF48D1CC. |
| [getMediumVioletRed](#getMediumVioletRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFC71585. |
| [getMidnightBlue](#getMidnightBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF191970. |
| [getMintCream](#getMintCream--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF5FFFA. |
| [getMistyRose](#getMistyRose--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFE4E1. |
| [getMoccasin](#getMoccasin--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFE4B5. |
| [getNavajoWhite](#getNavajoWhite--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFDEAD. |
| [getNavy](#getNavy--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF000080. |
| [getOldLace](#getOldLace--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFDF5E6. |
| [getOlive](#getOlive--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF808000. |
| [getOliveDrab](#getOliveDrab--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF6B8E23. |
| [getOrange](#getOrange--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFA500. |
| [getOrangeRed](#getOrangeRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF4500. |
| [getOrchid](#getOrchid--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDA70D6. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFEEE8AA. |
| [getPaleGreen](#getPaleGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF98FB98. |
| [getPaleTurquoise](#getPaleTurquoise--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFAFEEEE. |
| [getPaleVioletRed](#getPaleVioletRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDB7093. |
| [getPapayaWhip](#getPapayaWhip--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFEFD5. |
| [getPatternColorSpace](#getPatternColorSpace--) | Ottiene un oggetto che indica lo spazio colore del modello. Uso interno solo. |
| [getPeachPuff](#getPeachPuff--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFDAB9. |
| [getPeru](#getPeru--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFCD853F. |
| [getPink](#getPink--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFC0CB. |
| [getPlum](#getPlum--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDDA0DD. |
| [getPowderBlue](#getPowderBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFB0E0E6. |
| [getPurple](#getPurple--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF800080. |
| [getRed](#getRed--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF0000. |
| [getRosyBrown](#getRosyBrown--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFBC8F8F. |
| [getRoyalBlue](#getRoyalBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF4169E1. |
| [getSaddleBrown](#getSaddleBrown--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8B4513. |
| [getSalmon](#getSalmon--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFA8072. |
| [getSandyBrown](#getSandyBrown--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF4A460. |
| [getSeaGreen](#getSeaGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF2E8B57. |
| [getSeaShell](#getSeaShell--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFF5EE. |
| [getSienna](#getSienna--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFA0522D. |
| [getSilver](#getSilver--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFC0C0C0. |
| [getSkyBlue](#getSkyBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF87CEEB. |
| [getSlateBlue](#getSlateBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF6A5ACD. |
| [getSlateGray](#getSlateGray--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF708090. |
| [getSnow](#getSnow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFAFA. |
| [getSpringGreen](#getSpringGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00FF7F. |
| [getSteelBlue](#getSteelBlue--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF4682B4. |
| [getTan](#getTan--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFD2B48C. |
| [getTeal](#getTeal--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF008080. |
| [getThistle](#getThistle--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFD8BFD8. |
| [getTomato](#getTomato--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF6347. |
| [getTransparent](#getTransparent--) | Ottiene un colore definito dal sistema. |
| [getTurquoise](#getTurquoise--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF40E0D0. |
| [getViolet](#getViolet--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFEE82EE. |
| [getWheat](#getWheat--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF5DEB3. |
| [getWhite](#getWhite--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFFFF. |
| [getWhiteSmoke](#getWhiteSmoke--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF5F5F5. |
| [getYellow](#getYellow--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFF00. |
| [getYellowGreen](#getYellowGreen--) | Ottiene un colore definito dal sistema che ha un valore ARGB di #FF9ACD32. |
| [hashCode](#hashCode--) | Restituisce un valore di codice hash per l'oggetto. Questo metodo è supportato a beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve necessariamente rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, il programmatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Restituisce true se due colori sono uguali. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Restituisce true se due Colors non sono uguali. |
| [parse](#parse-java.lang.String-) | Estrae i componenti di colore dalla stringa. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Imposta un oggetto che indica il colorspace del pattern. Solo uso interno. |
| [toRgb](#toRgb--) | Converte il colore in rgb. |
| [toString](#toString--) | Converte in stringa. |

### Default {#Default}
```
public static final Color Default
```

Rappresenta il colore predefinito.

### Empty {#Empty}
```
public static final Color Empty
```

Rappresenta il colore vuoto.

### Color {#Color--}
```
public Color()
```

Costruttore predefinito.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

Costruttore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vettore |  | array double[] |

### deepClone {#deepClone--}
```
public Color deepClone()
```

Clona questa istanza

**Returns:**
oggetto Color

### equals {#equals-java.lang.Object-}
Restituisce true se due colori sono uguali.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

Ottiene un oggetto Color PDF valido dai componenti di colore RGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| r |  | Il componente di colore Rosso (valore 0 - 255). |
| g |  | Il componente di colore Verde (valore 0 - 255). |
| b |  | Il componente colore Blu (valore 0 - 255). |

**Returns:**
Oggetto colore con il valore di ciascun componente nell'intervallo [0..255].

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

Ottiene un oggetto Color PDF valido dai componenti di colore RGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a |  | Il valore del componente alfa (valore 0 - 255). |
| r |  | Il componente di colore Rosso (valore 0 - 255). |
| g |  | Il componente di colore Verde (valore 0 - 255). |
| b |  | Il componente colore Blu (valore 0 - 255). |

**Returns:**
Oggetto colore con il valore di ciascun componente nell'intervallo [0..255].

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

Ottiene un oggetto Color PDF valido dai componenti di colore CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c |  | Il componente colore Ciano (valore 0 - 1). |
| m |  | Il componente colore Magenta (valore 0 - 1). |
| y |  | Il componente colore Giallo (valore 0 - 1). |
| k |  | Il componente colore Key (valore 0 - 1). |

**Returns:**
Oggetto colore con il valore di ciascun componente nell'intervallo [0..1].

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Ottiene un oggetto Color PDF valido dal componente di colore grigio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g |  | Il componente colore Grigio (valore 0 - 1). |

**Returns:**
Oggetto colore con il valore di ciascun componente nell'intervallo [0..1].

### fromRgb {#fromRgb-java.awt.Color-}
Ottiene un oggetto Color PDF valido dal valore java.awt.Color.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

Ottiene un oggetto Color PDF valido dai componenti di colore RGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| r |  | Il componente colore Rosso (valore 0 - 1). |
| g |  | Il componente colore Verde (valore 0 - 1). |
| b |  | Il componente colore Blu (valore 0 - 1). |

**Returns:**
Oggetto colore con il valore di ciascun componente nell'intervallo [0..1].

### getA {#getA--}
```
public double getA()
```

Ottiene il valore del componente alfa

**Returns:**
valore double

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

Restituisce un colore definito dal sistema con valore ARGB #FFF0F8FF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

Restituisce un colore definito dal sistema con valore ARGB #FFFAEBD7.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

Restituisce un colore definito dal sistema con valore ARGB #FF00FFFF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

Restituisce un colore definito dal sistema con valore ARGB #FF7FFFD4.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF0FFFF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF5F5DC.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFE4C4.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF000000.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFEBCD.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF0000FF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8A2BE2.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFA52A2A.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDEB887.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF5F9EA0.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF7FFF00.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFD2691E.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Ottiene lo spazio colore che il colore rappresenta.

**Returns:**
Oggetto ColorSpace

### getCoral {#getCoral--}
```
public static Color getCoral()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF7F50.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF6495ED.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFF8DC.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDC143C.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

Restituisce un colore definito dal sistema con valore ARGB #FF00FFFF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00008B.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF008B8B.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFB8860B.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFA9A9A9.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF006400.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFBDB76B.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8B008B.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF556B2F.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF8C00.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF9932CC.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8B0000.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFE9967A.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8FBC8F.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF483D8B.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF2F4F4F.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00CED1.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF9400D3.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getData {#getData--}
```
public double[] getData()
```

Valore colore.

**Returns:**
array di valori double

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF1493.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00BFFF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF696969.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF1E90FF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFB22222.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFAF0.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF228B22.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF00FF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDCDCDC.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF8F8FF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getGold {#getGold--}
```
public static Color getGold()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFD700.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDAA520.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getGray {#getGray--}
```
public static Color getGray()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF808080.

**Returns:**
Una struttura che rappresenta un colore definito dal sistema.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF008000.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFADFF2F.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF0FFF0.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF69B4.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFCD5C5C.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF4B0082.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFFF0.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF0E68C.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFE6E6FA.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFF0F5.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF7CFC00.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFACD.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFADD8E6.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF08080.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFE0FFFF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFAFAD2.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFD3D3D3.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF90EE90.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFB6C1.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFA07A.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF20B2AA.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF87CEFA.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF778899.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFB0C4DE.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFFE0.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLime {#getLime--}
```
public static Color getLime()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00FF00.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF32CD32.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFAF0E6.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF00FF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF800000.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF66CDAA.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF0000CD.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFBA55D3.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF9370DB.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF3CB371.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF7B68EE.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00FA9A.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF48D1CC.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFC71585.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF191970.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF5FFFA.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFE4E1.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFE4B5.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFDEAD.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF000080.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFDF5E6.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF808000.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF6B8E23.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFA500.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF4500.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDA70D6.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFEEE8AA.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF98FB98.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFAFEEEE.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDB7093.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFEFD5.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

Ottiene un oggetto che indica lo spazio colore del modello. Uso interno solo.

**Returns:**
Oggetto PatternColorSpace

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFDAB9.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFCD853F.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPink {#getPink--}
```
public static Color getPink()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFC0CB.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFDDA0DD.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFB0E0E6.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF800080.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getRed {#getRed--}
```
public static Color getRed()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF0000.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFBC8F8F.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF4169E1.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF8B4513.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFA8072.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF4A460.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF2E8B57.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFF5EE.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFA0522D.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFC0C0C0.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF87CEEB.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF6A5ACD.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF708090.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFAFA.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF00FF7F.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF4682B4.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getTan {#getTan--}
```
public static Color getTan()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFD2B48C.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF008080.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFD8BFD8.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFF6347.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

Ottiene un colore definito dal sistema.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF40E0D0.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFEE82EE.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF5DEB3.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFFFF.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFF5F5F5.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FFFFFF00.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

Ottiene un colore definito dal sistema che ha un valore ARGB di #FF9ACD32.

**Returns:**
Un valore che rappresenta un colore definito dal sistema.

### hashCode {#hashCode--}
```
public int hashCode()
```

Restituisce un valore di codice hash per l'oggetto. Questo metodo è supportato a beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve necessariamente rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, il programmatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
un valore di hash code per questo oggetto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Restituisce true se due colori sono uguali.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Restituisce true se due Colors non sono uguali.

### parse {#parse-java.lang.String-}
Estrae i componenti di colore dalla stringa.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
Imposta un oggetto che indica il colorspace del pattern. Solo uso interno.

### toRgb {#toRgb--}
```
public Color toRgb()
```

Converte il colore in rgb.

**Returns:**
Valore colore Rgb.

### toString {#toString--}
```
public String toString()
```

Converte in stringa.

**Returns:**
Rappresentazione stringa dell'oggetto Color.
