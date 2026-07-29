---
title: "Color"
linktitle: "Color"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para valor de color que puede expresarse en diferentes espacios de color."
type: docs
weight: 670
url: /es/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

Representa una clase para valor de color que puede expresarse en diferentes espacios de color.

## Campos

| Campo | Descripción |
| --- | --- |
| [Default](#Default) | Representa el color predeterminado. |
| [Empty](#Empty) | Representa un color vacío. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Color](#Color--) | Constructor predeterminado. |
| [Color](#Color-double:A-) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clona esta instancia |
| [equals](#equals-java.lang.Object-) | Devuelve true si dos Colors son iguales. |
| [fromArgb](#fromArgb-int-int-int-) | Obtiene un objeto pdf Color válido a partir de los componentes de color RGB. |
| [fromArgb](#fromArgb-int-int-int-int-) | Obtiene un objeto pdf Color válido a partir de los componentes de color RGB. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | Obtiene un objeto pdf Color válido a partir de los componentes de color CMYK. |
| [fromGray](#fromGray-double-) | Obtiene un objeto pdf Color válido a partir del componente de color gris. |
| [fromRgb](#fromRgb-java.awt.Color-) | Obtiene un objeto pdf Color válido a partir del valor java.awt.Color. |
| [fromRgb](#fromRgb-double-double-double-) | Obtiene un objeto pdf Color válido a partir de los componentes de color RGB. |
| [getA](#getA--) | Obtiene el valor del componente alfa |
| [getAliceBlue](#getAliceBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF0F8FF. |
| [getAntiqueWhite](#getAntiqueWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFAEBD7. |
| [getAqua](#getAqua--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FFFF. |
| [getAquamarine](#getAquamarine--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF7FFFD4. |
| [getAzure](#getAzure--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF0FFFF. |
| [getBeige](#getBeige--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF5F5DC. |
| [getBisque](#getBisque--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFE4C4. |
| [getBlack](#getBlack--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF000000. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFEBCD. |
| [getBlue](#getBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF0000FF. |
| [getBlueViolet](#getBlueViolet--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8A2BE2. |
| [getBrown](#getBrown--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFA52A2A. |
| [getBurlyWood](#getBurlyWood--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDEB887. |
| [getCadetBlue](#getCadetBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF5F9EA0. |
| [getChartreuse](#getChartreuse--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF7FFF00. |
| [getChocolate](#getChocolate--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFD2691E. |
| [getColorSpace](#getColorSpace--) | Obtiene el espacio de color que representa el color. |
| [getCoral](#getCoral--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF7F50. |
| [getCornflowerBlue](#getCornflowerBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF6495ED. |
| [getCornsilk](#getCornsilk--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFF8DC. |
| [getCrimson](#getCrimson--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDC143C. |
| [getCyan](#getCyan--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FFFF. |
| [getDarkBlue](#getDarkBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00008B. |
| [getDarkCyan](#getDarkCyan--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF008B8B. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFB8860B. |
| [getDarkGray](#getDarkGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFA9A9A9. |
| [getDarkGreen](#getDarkGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF006400. |
| [getDarkKhaki](#getDarkKhaki--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFBDB76B. |
| [getDarkMagenta](#getDarkMagenta--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8B008B. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF556B2F. |
| [getDarkOrange](#getDarkOrange--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF9932CC. |
| [getDarkRed](#getDarkRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF9400D3. |
| [getData](#getData--) | Valor de color. |
| [getDeepPink](#getDeepPink--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00BFFF. |
| [getDimGray](#getDimGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFB22222. |
| [getFloralWhite](#getFloralWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFAF0. |
| [getForestGreen](#getForestGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF228B22. |
| [getFuchsia](#getFuchsia--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF00FF. |
| [getGainsboro](#getGainsboro--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDCDCDC. |
| [getGhostWhite](#getGhostWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF8F8FF. |
| [getGold](#getGold--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFD700. |
| [getGoldenrod](#getGoldenrod--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDAA520. |
| [getGray](#getGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF808080. |
| [getGreen](#getGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF008000. |
| [getGreenYellow](#getGreenYellow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFADFF2F. |
| [getHoneydew](#getHoneydew--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF0FFF0. |
| [getHotPink](#getHotPink--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF69B4. |
| [getIndianRed](#getIndianRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFCD5C5C. |
| [getIndigo](#getIndigo--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF4B0082. |
| [getIvory](#getIvory--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFFF0. |
| [getKhaki](#getKhaki--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF0E68C. |
| [getLavender](#getLavender--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFE6E6FA. |
| [getLavenderBlush](#getLavenderBlush--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFF0F5. |
| [getLawnGreen](#getLawnGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF7CFC00. |
| [getLemonChiffon](#getLemonChiffon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFACD. |
| [getLightBlue](#getLightBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFADD8E6. |
| [getLightCoral](#getLightCoral--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF08080. |
| [getLightCyan](#getLightCyan--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFE0FFFF. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFAFAD2. |
| [getLightGray](#getLightGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFD3D3D3. |
| [getLightGreen](#getLightGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF90EE90. |
| [getLightPink](#getLightPink--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFB6C1. |
| [getLightSalmon](#getLightSalmon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFA07A. |
| [getLightSeaGreen](#getLightSeaGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF20B2AA. |
| [getLightSkyBlue](#getLightSkyBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF87CEFA. |
| [getLightSlateGray](#getLightSlateGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF778899. |
| [getLightSteelBlue](#getLightSteelBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFB0C4DE. |
| [getLightYellow](#getLightYellow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFFE0. |
| [getLime](#getLime--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FF00. |
| [getLimeGreen](#getLimeGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF32CD32. |
| [getLinen](#getLinen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFAF0E6. |
| [getMagenta](#getMagenta--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF00FF. |
| [getMaroon](#getMaroon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF800000. |
| [getMediumAquamarine](#getMediumAquamarine--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF66CDAA. |
| [getMediumBlue](#getMediumBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF0000CD. |
| [getMediumOrchid](#getMediumOrchid--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFBA55D3. |
| [getMediumPurple](#getMediumPurple--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF9370DB. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF3CB371. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF7B68EE. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FA9A. |
| [getMediumTurquoise](#getMediumTurquoise--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF48D1CC. |
| [getMediumVioletRed](#getMediumVioletRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFC71585. |
| [getMidnightBlue](#getMidnightBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF191970. |
| [getMintCream](#getMintCream--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF5FFFA. |
| [getMistyRose](#getMistyRose--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFE4E1. |
| [getMoccasin](#getMoccasin--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFE4B5. |
| [getNavajoWhite](#getNavajoWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFDEAD. |
| [getNavy](#getNavy--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF000080. |
| [getOldLace](#getOldLace--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFDF5E6. |
| [getOlive](#getOlive--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF808000. |
| [getOliveDrab](#getOliveDrab--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF6B8E23. |
| [getOrange](#getOrange--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFA500. |
| [getOrangeRed](#getOrangeRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF4500. |
| [getOrchid](#getOrchid--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDA70D6. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFEEE8AA. |
| [getPaleGreen](#getPaleGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF98FB98. |
| [getPaleTurquoise](#getPaleTurquoise--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFAFEEEE. |
| [getPaleVioletRed](#getPaleVioletRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDB7093. |
| [getPapayaWhip](#getPapayaWhip--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFEFD5. |
| [getPatternColorSpace](#getPatternColorSpace--) | Obtiene un objeto que indica el espacio de color del patrón. Solo uso interno. |
| [getPeachPuff](#getPeachPuff--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFDAB9. |
| [getPeru](#getPeru--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFCD853F. |
| [getPink](#getPink--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFC0CB. |
| [getPlum](#getPlum--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDDA0DD. |
| [getPowderBlue](#getPowderBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFB0E0E6. |
| [getPurple](#getPurple--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF800080. |
| [getRed](#getRed--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF0000. |
| [getRosyBrown](#getRosyBrown--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFBC8F8F. |
| [getRoyalBlue](#getRoyalBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF4169E1. |
| [getSaddleBrown](#getSaddleBrown--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8B4513. |
| [getSalmon](#getSalmon--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFA8072. |
| [getSandyBrown](#getSandyBrown--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF4A460. |
| [getSeaGreen](#getSeaGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF2E8B57. |
| [getSeaShell](#getSeaShell--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFF5EE. |
| [getSienna](#getSienna--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFA0522D. |
| [getSilver](#getSilver--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFC0C0C0. |
| [getSkyBlue](#getSkyBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF87CEEB. |
| [getSlateBlue](#getSlateBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF6A5ACD. |
| [getSlateGray](#getSlateGray--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF708090. |
| [getSnow](#getSnow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFAFA. |
| [getSpringGreen](#getSpringGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FF7F. |
| [getSteelBlue](#getSteelBlue--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF4682B4. |
| [getTan](#getTan--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFD2B48C. |
| [getTeal](#getTeal--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF008080. |
| [getThistle](#getThistle--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFD8BFD8. |
| [getTomato](#getTomato--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF6347. |
| [getTransparent](#getTransparent--) | Obtiene un color definido por el sistema. |
| [getTurquoise](#getTurquoise--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF40E0D0. |
| [getViolet](#getViolet--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFEE82EE. |
| [getWheat](#getWheat--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF5DEB3. |
| [getWhite](#getWhite--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFFFF. |
| [getWhiteSmoke](#getWhiteSmoke--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF5F5F5. |
| [getYellow](#getYellow--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFF00. |
| [getYellowGreen](#getYellowGreen--) | Obtiene un color definido por el sistema que tiene un valor ARGB de #FF9ACD32. |
| [hashCode](#hashCode--) | Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique ninguna información utilizada en comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>requerido</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto normalmente se implementa convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Devuelve true si dos Colors son iguales. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Devuelve true si dos Colors no son iguales. |
| [parse](#parse-java.lang.String-) | Extrae los componentes de color de la cadena. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Establece un objeto que indica el espacio de color del patrón. Solo uso interno |
| [toRgb](#toRgb--) | Convierte el color a rgb. |
| [toString](#toString--) | Convierte a cadena. |

### Default {#Default}
```
public static final Color Default
```

Representa el color predeterminado.

### Empty {#Empty}
```
public static final Color Empty
```

Representa un color vacío.

### Color {#Color--}
```
public Color()
```

Constructor predeterminado.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

Constructor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vector |  | matriz double[] |

### deepClone {#deepClone--}
```
public Color deepClone()
```

Clona esta instancia

**Returns:**
Objeto Color

### equals {#equals-java.lang.Object-}
Devuelve true si dos Colors son iguales.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

Obtiene un objeto pdf Color válido a partir de los componentes de color RGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r |  | El componente de color Rojo (valor 0 - 255). |
| g |  | El componente de color Verde (valor 0 - 255). |
| b |  | El componente de color Azul (valor 0 - 255). |

**Returns:**
Objeto Color con el valor de cada componente en el rango [0..255].

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

Obtiene un objeto pdf Color válido a partir de los componentes de color RGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a |  | El valor del componente alfa (valor 0 - 255). |
| r |  | El componente de color Rojo (valor 0 - 255). |
| g |  | El componente de color Verde (valor 0 - 255). |
| b |  | El componente de color Azul (valor 0 - 255). |

**Returns:**
Objeto Color con el valor de cada componente en el rango [0..255].

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

Obtiene un objeto pdf Color válido a partir de los componentes de color CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c |  | El componente de color Cian (valor 0 - 1). |
| m |  | El componente de color Magenta (valor 0 - 1). |
| y |  | El componente de color Amarillo (valor 0 - 1). |
| k |  | El componente de color Key (valor 0 - 1). |

**Returns:**
Objeto Color con el valor de cada componente en el rango [0..1].

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Obtiene un objeto pdf Color válido a partir del componente de color gris.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g |  | El componente de color Gris (valor 0 - 1). |

**Returns:**
Objeto Color con el valor de cada componente en el rango [0..1].

### fromRgb {#fromRgb-java.awt.Color-}
Obtiene un objeto pdf Color válido a partir del valor java.awt.Color.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

Obtiene un objeto pdf Color válido a partir de los componentes de color RGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r |  | El componente de color Rojo (valor 0 - 1). |
| g |  | El componente de color Verde (valor 0 - 1). |
| b |  | El componente de color Azul (valor 0 - 1). |

**Returns:**
Objeto Color con el valor de cada componente en el rango [0..1].

### getA {#getA--}
```
public double getA()
```

Obtiene el valor del componente alfa

**Returns:**
valor double

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF0F8FF.

**Returns:**
Un color que representa un color definido por el sistema.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFAEBD7.

**Returns:**
Un color que representa un color definido por el sistema.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FFFF.

**Returns:**
Un color que representa un color definido por el sistema.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF7FFFD4.

**Returns:**
Un color que representa un color definido por el sistema.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF0FFFF.

**Returns:**
Un color que representa un color definido por el sistema.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF5F5DC.

**Returns:**
Un color que representa un color definido por el sistema.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFE4C4.

**Returns:**
Un color que representa un color definido por el sistema.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF000000.

**Returns:**
Un color que representa un color definido por el sistema.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFEBCD.

**Returns:**
Un color que representa un color definido por el sistema.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF0000FF.

**Returns:**
Un color que representa un color definido por el sistema.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8A2BE2.

**Returns:**
Un color que representa un color definido por el sistema.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFA52A2A.

**Returns:**
Un color que representa un color definido por el sistema.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDEB887.

**Returns:**
Un color que representa un color definido por el sistema.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF5F9EA0.

**Returns:**
Un color que representa un color definido por el sistema.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF7FFF00.

**Returns:**
Un color que representa un color definido por el sistema.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFD2691E.

**Returns:**
Un color que representa un color definido por el sistema.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Obtiene el espacio de color que representa el color.

**Returns:**
Objeto ColorSpace

### getCoral {#getCoral--}
```
public static Color getCoral()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF7F50.

**Returns:**
Un color que representa un color definido por el sistema.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF6495ED.

**Returns:**
Un color que representa un color definido por el sistema.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFF8DC.

**Returns:**
Un color que representa un color definido por el sistema.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDC143C.

**Returns:**
Un color que representa un color definido por el sistema.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FFFF.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00008B.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF008B8B.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFB8860B.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFA9A9A9.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF006400.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFBDB76B.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8B008B.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF556B2F.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF8C00.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF9932CC.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8B0000.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFE9967A.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8FBC8F.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF483D8B.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF2F4F4F.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00CED1.

**Returns:**
Un color que representa un color definido por el sistema.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF9400D3.

**Returns:**
Un color que representa un color definido por el sistema.

### getData {#getData--}
```
public double[] getData()
```

Valor de color.

**Returns:**
arreglo de valores double

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF1493.

**Returns:**
Un color que representa un color definido por el sistema.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00BFFF.

**Returns:**
Un color que representa un color definido por el sistema.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF696969.

**Returns:**
Un color que representa un color definido por el sistema.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF1E90FF.

**Returns:**
Un color que representa un color definido por el sistema.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFB22222.

**Returns:**
Un color que representa un color definido por el sistema.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFAF0.

**Returns:**
Un color que representa un color definido por el sistema.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF228B22.

**Returns:**
Un color que representa un color definido por el sistema.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF00FF.

**Returns:**
Un color que representa un color definido por el sistema.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDCDCDC.

**Returns:**
Un color que representa un color definido por el sistema.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF8F8FF.

**Returns:**
Un color que representa un color definido por el sistema.

### getGold {#getGold--}
```
public static Color getGold()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFD700.

**Returns:**
Un color que representa un color definido por el sistema.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDAA520.

**Returns:**
Un color que representa un color definido por el sistema.

### getGray {#getGray--}
```
public static Color getGray()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF808080.

**Returns:**
Una estructura que representa un color definido por el sistema.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF008000.

**Returns:**
Un color que representa un color definido por el sistema.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFADFF2F.

**Returns:**
Un color que representa un color definido por el sistema.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF0FFF0.

**Returns:**
Un color que representa un color definido por el sistema.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF69B4.

**Returns:**
Un color que representa un color definido por el sistema.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFCD5C5C.

**Returns:**
Un color que representa un color definido por el sistema.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF4B0082.

**Returns:**
Un color que representa un color definido por el sistema.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFFF0.

**Returns:**
Un color que representa un color definido por el sistema.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF0E68C.

**Returns:**
Un color que representa un color definido por el sistema.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFE6E6FA.

**Returns:**
Un color que representa un color definido por el sistema.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFF0F5.

**Returns:**
Un color que representa un color definido por el sistema.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF7CFC00.

**Returns:**
Un color que representa un color definido por el sistema.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFACD.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFADD8E6.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF08080.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFE0FFFF.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFAFAD2.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFD3D3D3.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF90EE90.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFB6C1.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFA07A.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF20B2AA.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF87CEFA.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF778899.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFB0C4DE.

**Returns:**
Un color que representa un color definido por el sistema.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFFE0.

**Returns:**
Un color que representa un color definido por el sistema.

### getLime {#getLime--}
```
public static Color getLime()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FF00.

**Returns:**
Un color que representa un color definido por el sistema.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF32CD32.

**Returns:**
Un color que representa un color definido por el sistema.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFAF0E6.

**Returns:**
Un color que representa un color definido por el sistema.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF00FF.

**Returns:**
Un color que representa un color definido por el sistema.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF800000.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF66CDAA.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF0000CD.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFBA55D3.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF9370DB.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF3CB371.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF7B68EE.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FA9A.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF48D1CC.

**Returns:**
Un color que representa un color definido por el sistema.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFC71585.

**Returns:**
Un color que representa un color definido por el sistema.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF191970.

**Returns:**
Un color que representa un color definido por el sistema.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF5FFFA.

**Returns:**
Un color que representa un color definido por el sistema.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFE4E1.

**Returns:**
Un color que representa un color definido por el sistema.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFE4B5.

**Returns:**
Un color que representa un color definido por el sistema.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFDEAD.

**Returns:**
Un color que representa un color definido por el sistema.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF000080.

**Returns:**
Un color que representa un color definido por el sistema.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFDF5E6.

**Returns:**
Un color que representa un color definido por el sistema.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF808000.

**Returns:**
Un color que representa un color definido por el sistema.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF6B8E23.

**Returns:**
Un color que representa un color definido por el sistema.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFA500.

**Returns:**
Un color que representa un color definido por el sistema.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF4500.

**Returns:**
Un color que representa un color definido por el sistema.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDA70D6.

**Returns:**
Un color que representa un color definido por el sistema.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFEEE8AA.

**Returns:**
Un color que representa un color definido por el sistema.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF98FB98.

**Returns:**
Un color que representa un color definido por el sistema.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFAFEEEE.

**Returns:**
Un color que representa un color definido por el sistema.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDB7093.

**Returns:**
Un color que representa un color definido por el sistema.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFEFD5.

**Returns:**
Un color que representa un color definido por el sistema.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

Obtiene un objeto que indica el espacio de color del patrón. Solo uso interno.

**Returns:**
Objeto PatternColorSpace

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFDAB9.

**Returns:**
Un color que representa un color definido por el sistema.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFCD853F.

**Returns:**
Un color que representa un color definido por el sistema.

### getPink {#getPink--}
```
public static Color getPink()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFC0CB.

**Returns:**
Un color que representa un color definido por el sistema.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFDDA0DD.

**Returns:**
Un color que representa un color definido por el sistema.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFB0E0E6.

**Returns:**
Un color que representa un color definido por el sistema.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF800080.

**Returns:**
Un color que representa un color definido por el sistema.

### getRed {#getRed--}
```
public static Color getRed()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF0000.

**Returns:**
Un color que representa un color definido por el sistema.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFBC8F8F.

**Returns:**
Un color que representa un color definido por el sistema.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF4169E1.

**Returns:**
Un color que representa un color definido por el sistema.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF8B4513.

**Returns:**
Un color que representa un color definido por el sistema.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFA8072.

**Returns:**
Un color que representa un color definido por el sistema.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF4A460.

**Returns:**
Un color que representa un color definido por el sistema.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF2E8B57.

**Returns:**
Un color que representa un color definido por el sistema.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFF5EE.

**Returns:**
Un color que representa un color definido por el sistema.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFA0522D.

**Returns:**
Un color que representa un color definido por el sistema.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFC0C0C0.

**Returns:**
Un color que representa un color definido por el sistema.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF87CEEB.

**Returns:**
Un color que representa un color definido por el sistema.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF6A5ACD.

**Returns:**
Un color que representa un color definido por el sistema.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF708090.

**Returns:**
Un color que representa un color definido por el sistema.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFAFA.

**Returns:**
Un color que representa un color definido por el sistema.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF00FF7F.

**Returns:**
Un color que representa un color definido por el sistema.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF4682B4.

**Returns:**
Un color que representa un color definido por el sistema.

### getTan {#getTan--}
```
public static Color getTan()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFD2B48C.

**Returns:**
Un color que representa un color definido por el sistema.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF008080.

**Returns:**
Un color que representa un color definido por el sistema.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFD8BFD8.

**Returns:**
Un color que representa un color definido por el sistema.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFF6347.

**Returns:**
Un color que representa un color definido por el sistema.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

Obtiene un color definido por el sistema.

**Returns:**
Un color que representa un color definido por el sistema.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF40E0D0.

**Returns:**
Un color que representa un color definido por el sistema.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFEE82EE.

**Returns:**
Un color que representa un color definido por el sistema.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF5DEB3.

**Returns:**
Un color que representa un color definido por el sistema.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFFFF.

**Returns:**
Un color que representa un color definido por el sistema.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFF5F5F5.

**Returns:**
Un color que representa un color definido por el sistema.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FFFFFF00.

**Returns:**
Un color que representa un color definido por el sistema.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

Obtiene un color definido por el sistema que tiene un valor ARGB de #FF9ACD32.

**Returns:**
Un color que representa un color definido por el sistema.

### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique ninguna información utilizada en comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>requerido</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto normalmente se implementa convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Devuelve true si dos Colors son iguales.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Devuelve true si dos Colors no son iguales.

### parse {#parse-java.lang.String-}
Extrae los componentes de color de la cadena.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
Establece un objeto que indica el espacio de color del patrón. Solo uso interno

### toRgb {#toRgb--}
```
public Color toRgb()
```

Convierte el color a rgb.

**Returns:**
Valor de color Rgb.

### toString {#toString--}
```
public String toString()
```

Convierte a cadena.

**Returns:**
Representación en cadena del objeto Color.
