---
title: "Cor"
linktitle: "Cor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para valor de cor que pode ser expressado em diferentes espaços de cor."
type: docs
weight: 670
url: /pt/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

Representa uma classe para valor de cor que pode ser expressado em diferentes espaços de cor.

## Campos

| Campo | Descrição |
| --- | --- |
| [Default](#Default) | Representa a cor padrão. |
| [Empty](#Empty) | Representa cor vazia. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Color](#Color--) | Construtor padrão. |
| [Color](#Color-double:A-) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Clona esta instância |
| [equals](#equals-java.lang.Object-) | Retorna true se duas Colors forem iguais. |
| [fromArgb](#fromArgb-int-int-int-) | Obtém um objeto pdf Color válido a partir dos componentes de cor RGB. |
| [fromArgb](#fromArgb-int-int-int-int-) | Obtém um objeto pdf Color válido a partir dos componentes de cor RGB. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | Obtém um objeto pdf Color válido a partir dos componentes de cor CMYK. |
| [fromGray](#fromGray-double-) | Obtém um objeto pdf Color válido a partir do componente de cor Gray. |
| [fromRgb](#fromRgb-java.awt.Color-) | Obtém um objeto pdf Color válido a partir do valor java.awt.Color. |
| [fromRgb](#fromRgb-double-double-double-) | Obtém um objeto pdf Color válido a partir dos componentes de cor RGB. |
| [getA](#getA--) | Obtém o valor do componente alfa |
| [getAliceBlue](#getAliceBlue--) | Obtém uma cor definida pelo sistema que tem o valor ARGB #FFF0F8FF. |
| [getAntiqueWhite](#getAntiqueWhite--) | Obtém uma cor definida pelo sistema que tem o valor ARGB #FFFAEBD7. |
| [getAqua](#getAqua--) | Obtém uma cor definida pelo sistema que tem o valor ARGB #FF00FFFF. |
| [getAquamarine](#getAquamarine--) | Obtém uma cor definida pelo sistema que tem o valor ARGB #FF7FFFD4. |
| [getAzure](#getAzure--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF0FFFF. |
| [getBeige](#getBeige--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF5F5DC. |
| [getBisque](#getBisque--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFE4C4. |
| [getBlack](#getBlack--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF000000. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFEBCD. |
| [getBlue](#getBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF0000FF. |
| [getBlueViolet](#getBlueViolet--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8A2BE2. |
| [getBrown](#getBrown--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFA52A2A. |
| [getBurlyWood](#getBurlyWood--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDEB887. |
| [getCadetBlue](#getCadetBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF5F9EA0. |
| [getChartreuse](#getChartreuse--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF7FFF00. |
| [getChocolate](#getChocolate--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFD2691E. |
| [getColorSpace](#getColorSpace--) | Obtém o espaço de cor que a cor representa. |
| [getCoral](#getCoral--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF7F50. |
| [getCornflowerBlue](#getCornflowerBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF6495ED. |
| [getCornsilk](#getCornsilk--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFF8DC. |
| [getCrimson](#getCrimson--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDC143C. |
| [getCyan](#getCyan--) | Obtém uma cor definida pelo sistema que tem o valor ARGB #FF00FFFF. |
| [getDarkBlue](#getDarkBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00008B. |
| [getDarkCyan](#getDarkCyan--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF008B8B. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFB8860B. |
| [getDarkGray](#getDarkGray--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFA9A9A9. |
| [getDarkGreen](#getDarkGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF006400. |
| [getDarkKhaki](#getDarkKhaki--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFBDB76B. |
| [getDarkMagenta](#getDarkMagenta--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8B008B. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF556B2F. |
| [getDarkOrange](#getDarkOrange--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF9932CC. |
| [getDarkRed](#getDarkRed--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF9400D3. |
| [getData](#getData--) | Valor da cor. |
| [getDeepPink](#getDeepPink--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00BFFF. |
| [getDimGray](#getDimGray--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFB22222. |
| [getFloralWhite](#getFloralWhite--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFAF0. |
| [getForestGreen](#getForestGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF228B22. |
| [getFuchsia](#getFuchsia--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF00FF. |
| [getGainsboro](#getGainsboro--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDCDCDC. |
| [getGhostWhite](#getGhostWhite--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF8F8FF. |
| [getGold](#getGold--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFD700. |
| [getGoldenrod](#getGoldenrod--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDAA520. |
| [getGray](#getGray--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF808080. |
| [getGreen](#getGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF008000. |
| [getGreenYellow](#getGreenYellow--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFADFF2F. |
| [getHoneydew](#getHoneydew--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF0FFF0. |
| [getHotPink](#getHotPink--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF69B4. |
| [getIndianRed](#getIndianRed--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFCD5C5C. |
| [getIndigo](#getIndigo--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF4B0082. |
| [getIvory](#getIvory--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFFF0. |
| [getKhaki](#getKhaki--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF0E68C. |
| [getLavender](#getLavender--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFE6E6FA. |
| [getLavenderBlush](#getLavenderBlush--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFF0F5. |
| [getLawnGreen](#getLawnGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF7CFC00. |
| [getLemonChiffon](#getLemonChiffon--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFACD. |
| [getLightBlue](#getLightBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFADD8E6. |
| [getLightCoral](#getLightCoral--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF08080. |
| [getLightCyan](#getLightCyan--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFE0FFFF. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFAFAD2. |
| [getLightGray](#getLightGray--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFD3D3D3. |
| [getLightGreen](#getLightGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF90EE90. |
| [getLightPink](#getLightPink--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFB6C1. |
| [getLightSalmon](#getLightSalmon--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFA07A. |
| [getLightSeaGreen](#getLightSeaGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF20B2AA. |
| [getLightSkyBlue](#getLightSkyBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF87CEFA. |
| [getLightSlateGray](#getLightSlateGray--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF778899. |
| [getLightSteelBlue](#getLightSteelBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFB0C4DE. |
| [getLightYellow](#getLightYellow--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFFE0. |
| [getLime](#getLime--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00FF00. |
| [getLimeGreen](#getLimeGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF32CD32. |
| [getLinen](#getLinen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFAF0E6. |
| [getMagenta](#getMagenta--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF00FF. |
| [getMaroon](#getMaroon--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF800000. |
| [getMediumAquamarine](#getMediumAquamarine--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF66CDAA. |
| [getMediumBlue](#getMediumBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF0000CD. |
| [getMediumOrchid](#getMediumOrchid--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFBA55D3. |
| [getMediumPurple](#getMediumPurple--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF9370DB. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF3CB371. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF7B68EE. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00FA9A. |
| [getMediumTurquoise](#getMediumTurquoise--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF48D1CC. |
| [getMediumVioletRed](#getMediumVioletRed--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFC71585. |
| [getMidnightBlue](#getMidnightBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF191970. |
| [getMintCream](#getMintCream--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF5FFFA. |
| [getMistyRose](#getMistyRose--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFE4E1. |
| [getMoccasin](#getMoccasin--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFE4B5. |
| [getNavajoWhite](#getNavajoWhite--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFDEAD. |
| [getNavy](#getNavy--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF000080. |
| [getOldLace](#getOldLace--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFDF5E6. |
| [getOlive](#getOlive--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF808000. |
| [getOliveDrab](#getOliveDrab--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF6B8E23. |
| [getOrange](#getOrange--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFA500. |
| [getOrangeRed](#getOrangeRed--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF4500. |
| [getOrchid](#getOrchid--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDA70D6. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFEEE8AA. |
| [getPaleGreen](#getPaleGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF98FB98. |
| [getPaleTurquoise](#getPaleTurquoise--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFAFEEEE. |
| [getPaleVioletRed](#getPaleVioletRed--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDB7093. |
| [getPapayaWhip](#getPapayaWhip--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFEFD5. |
| [getPatternColorSpace](#getPatternColorSpace--) | Obtém um objeto que indica o espaço de cores do padrão. Uso interno apenas |
| [getPeachPuff](#getPeachPuff--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFDAB9. |
| [getPeru](#getPeru--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFCD853F. |
| [getPink](#getPink--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFC0CB. |
| [getPlum](#getPlum--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDDA0DD. |
| [getPowderBlue](#getPowderBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFB0E0E6. |
| [getPurple](#getPurple--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF800080. |
| [getRed](#getRed--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF0000. |
| [getRosyBrown](#getRosyBrown--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFBC8F8F. |
| [getRoyalBlue](#getRoyalBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF4169E1. |
| [getSaddleBrown](#getSaddleBrown--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8B4513. |
| [getSalmon](#getSalmon--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFA8072. |
| [getSandyBrown](#getSandyBrown--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF4A460. |
| [getSeaGreen](#getSeaGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF2E8B57. |
| [getSeaShell](#getSeaShell--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFF5EE. |
| [getSienna](#getSienna--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFA0522D. |
| [getSilver](#getSilver--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFC0C0C0. |
| [getSkyBlue](#getSkyBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF87CEEB. |
| [getSlateBlue](#getSlateBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF6A5ACD. |
| [getSlateGray](#getSlateGray--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF708090. |
| [getSnow](#getSnow--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFAFA. |
| [getSpringGreen](#getSpringGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00FF7F. |
| [getSteelBlue](#getSteelBlue--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF4682B4. |
| [getTan](#getTan--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFD2B48C. |
| [getTeal](#getTeal--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF008080. |
| [getThistle](#getThistle--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFD8BFD8. |
| [getTomato](#getTomato--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF6347. |
| [getTransparent](#getTransparent--) | Obtém uma cor definida pelo sistema. |
| [getTurquoise](#getTurquoise--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF40E0D0. |
| [getViolet](#getViolet--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFEE82EE. |
| [getWheat](#getWheat--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF5DEB3. |
| [getWhite](#getWhite--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFFFF. |
| [getWhiteSmoke](#getWhiteSmoke--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF5F5F5. |
| [getYellow](#getYellow--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFF00. |
| [getYellowGreen](#getYellowGreen--) | Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF9ACD32. |
| [hashCode](#hashCode--) | Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho das tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Retorna true se duas Colors forem iguais. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Retorna verdadeiro se duas Cores não forem iguais. |
| [parse](#parse-java.lang.String-) | Extrai os componentes de cor da string. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Define um objeto que indica o espaço de cores do padrão. Uso interno apenas |
| [toRgb](#toRgb--) | Converte cor para rgb. |
| [toString](#toString--) | Converte para string. |

### Default {#Default}
```
public static final Color Default
```

Representa a cor padrão.

### Empty {#Empty}
```
public static final Color Empty
```

Representa cor vazia.

### Color {#Color--}
```
public Color()
```

Construtor padrão.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

Construtor

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vetor |  | array double[] |

### deepClone {#deepClone--}
```
public Color deepClone()
```

Clona esta instância

**Returns:**
Objeto Color

### equals {#equals-java.lang.Object-}
Retorna true se duas Colors forem iguais.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

Obtém um objeto pdf Color válido a partir dos componentes de cor RGB.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| r |  | O componente de cor Vermelho (valor 0 - 255). |
| g |  | O componente de cor Verde (valor 0 - 255). |
| b |  | O componente de cor Azul (valor 0 - 255). |

**Returns:**
Objeto Color com o valor de cada componente no intervalo [0..255].

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

Obtém um objeto pdf Color válido a partir dos componentes de cor RGB.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a |  | O valor do componente alfa (valor 0 - 255). |
| r |  | O componente de cor Vermelho (valor 0 - 255). |
| g |  | O componente de cor Verde (valor 0 - 255). |
| b |  | O componente de cor Azul (valor 0 - 255). |

**Returns:**
Objeto Color com o valor de cada componente no intervalo [0..255].

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

Obtém um objeto pdf Color válido a partir dos componentes de cor CMYK.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c |  | O componente de cor Ciano (valor 0 - 1). |
| m |  | O componente de cor Magenta (valor 0 - 1). |
| y |  | O componente de cor Amarelo (valor 0 - 1). |
| k |  | O componente de cor Preto (valor 0 - 1). |

**Returns:**
Objeto Color com o valor de cada componente no intervalo [0..1].

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Obtém um objeto pdf Color válido a partir do componente de cor Gray.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| g |  | O componente de cor Cinza (valor 0 - 1). |

**Returns:**
Objeto Color com o valor de cada componente no intervalo [0..1].

### fromRgb {#fromRgb-java.awt.Color-}
Obtém um objeto pdf Color válido a partir do valor java.awt.Color.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

Obtém um objeto pdf Color válido a partir dos componentes de cor RGB.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| r |  | O componente de cor Vermelho (valor 0 - 1). |
| g |  | O componente de cor Verde (valor 0 - 1). |
| b |  | O componente de cor Azul (valor 0 - 1). |

**Returns:**
Objeto Color com o valor de cada componente no intervalo [0..1].

### getA {#getA--}
```
public double getA()
```

Obtém o valor do componente alfa

**Returns:**
valor double

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

Obtém uma cor definida pelo sistema que tem o valor ARGB #FFF0F8FF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

Obtém uma cor definida pelo sistema que tem o valor ARGB #FFFAEBD7.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

Obtém uma cor definida pelo sistema que tem o valor ARGB #FF00FFFF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

Obtém uma cor definida pelo sistema que tem o valor ARGB #FF7FFFD4.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF0FFFF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF5F5DC.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFE4C4.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF000000.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFEBCD.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF0000FF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8A2BE2.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFA52A2A.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDEB887.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF5F9EA0.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF7FFF00.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFD2691E.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Obtém o espaço de cor que a cor representa.

**Returns:**
Objeto ColorSpace

### getCoral {#getCoral--}
```
public static Color getCoral()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF7F50.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF6495ED.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFF8DC.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDC143C.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

Obtém uma cor definida pelo sistema que tem o valor ARGB #FF00FFFF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00008B.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF008B8B.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFB8860B.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFA9A9A9.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF006400.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFBDB76B.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8B008B.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF556B2F.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF8C00.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF9932CC.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8B0000.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFE9967A.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8FBC8F.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF483D8B.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF2F4F4F.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00CED1.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF9400D3.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getData {#getData--}
```
public double[] getData()
```

Valor da cor.

**Returns:**
array de valores double

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF1493.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00BFFF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF696969.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF1E90FF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFB22222.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFAF0.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF228B22.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF00FF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDCDCDC.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF8F8FF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getGold {#getGold--}
```
public static Color getGold()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFD700.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDAA520.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getGray {#getGray--}
```
public static Color getGray()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF808080.

**Returns:**
Uma estrutura que representa uma cor definida pelo sistema.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF008000.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFADFF2F.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF0FFF0.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF69B4.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFCD5C5C.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF4B0082.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFFF0.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF0E68C.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFE6E6FA.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFF0F5.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF7CFC00.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFACD.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFADD8E6.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF08080.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFE0FFFF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFAFAD2.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFD3D3D3.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF90EE90.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFB6C1.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFA07A.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF20B2AA.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF87CEFA.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF778899.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFB0C4DE.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFFE0.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLime {#getLime--}
```
public static Color getLime()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00FF00.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF32CD32.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFAF0E6.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF00FF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF800000.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF66CDAA.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF0000CD.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFBA55D3.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF9370DB.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF3CB371.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF7B68EE.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00FA9A.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF48D1CC.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFC71585.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF191970.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF5FFFA.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFE4E1.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFE4B5.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFDEAD.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF000080.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFDF5E6.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF808000.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF6B8E23.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFA500.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF4500.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDA70D6.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFEEE8AA.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF98FB98.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFAFEEEE.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDB7093.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFEFD5.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

Obtém um objeto que indica o espaço de cores do padrão. Uso interno apenas

**Returns:**
Objeto PatternColorSpace

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFDAB9.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFCD853F.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPink {#getPink--}
```
public static Color getPink()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFC0CB.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFDDA0DD.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFB0E0E6.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF800080.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getRed {#getRed--}
```
public static Color getRed()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF0000.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFBC8F8F.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF4169E1.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF8B4513.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFA8072.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF4A460.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF2E8B57.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFF5EE.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFA0522D.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFC0C0C0.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF87CEEB.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF6A5ACD.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF708090.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFAFA.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF00FF7F.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF4682B4.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getTan {#getTan--}
```
public static Color getTan()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFD2B48C.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF008080.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFD8BFD8.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFF6347.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

Obtém uma cor definida pelo sistema.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF40E0D0.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFEE82EE.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF5DEB3.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFFFF.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFF5F5F5.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FFFFFF00.

**Returns:**
Um que representa uma cor definida pelo sistema.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

Obtém uma cor definida pelo sistema que tem um valor ARGB de #FF9ACD32.

**Returns:**
Um que representa uma cor definida pelo sistema.

### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho das tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
um valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Retorna true se duas Colors forem iguais.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Retorna verdadeiro se duas Cores não forem iguais.

### parse {#parse-java.lang.String-}
Extrai os componentes de cor da string.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
Define um objeto que indica o espaço de cores do padrão. Uso interno apenas

### toRgb {#toRgb--}
```
public Color toRgb()
```

Converte cor para rgb.

**Returns:**
Valor de cor Rgb.

### toString {#toString--}
```
public String toString()
```

Converte para string.

**Returns:**
Representação em string do objeto Color.
