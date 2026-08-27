---
title: "Couleur"
linktitle: "Couleur"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour la valeur de couleur qui peut être exprimée dans différents espaces colorimétriques."
type: docs
weight: 670
url: /fr/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

Représente une classe pour la valeur de couleur qui peut être exprimée dans différents espaces colorimétriques.

## Champs

| Champ | Description |
| --- | --- |
| [Default](#Default) | Représente la couleur par défaut. |
| [Empty](#Empty) | Représente une couleur vide. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Color](#Color--) | Constructeur par défaut. |
| [Color](#Color-double:A-) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone cette instance |
| [equals](#equals-java.lang.Object-) | Renvoie true si deux Colors sont égaux. |
| [fromArgb](#fromArgb-int-int-int-) | Obtient un objet pdf Color valide à partir des composants de couleur RVB. |
| [fromArgb](#fromArgb-int-int-int-int-) | Obtient un objet pdf Color valide à partir des composants de couleur RVB. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | Obtient un objet pdf Color valide à partir des composants de couleur CMYK. |
| [fromGray](#fromGray-double-) | Obtient un objet pdf Color valide à partir du composant de couleur gris. |
| [fromRgb](#fromRgb-java.awt.Color-) | Obtient un objet pdf Color valide à partir de la valeur java.awt.Color. |
| [fromRgb](#fromRgb-double-double-double-) | Obtient un objet pdf Color valide à partir des composants de couleur RVB. |
| [getA](#getA--) | Obtient la valeur du composant alpha |
| [getAliceBlue](#getAliceBlue--) | Obtient une couleur définie par le système ayant une valeur ARGB de #FFF0F8FF. |
| [getAntiqueWhite](#getAntiqueWhite--) | Obtient une couleur définie par le système ayant une valeur ARGB de #FFFAEBD7. |
| [getAqua](#getAqua--) | Obtient une couleur définie par le système ayant une valeur ARGB de #FF00FFFF. |
| [getAquamarine](#getAquamarine--) | Obtient une couleur définie par le système ayant une valeur ARGB de #FF7FFFD4. |
| [getAzure](#getAzure--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF0FFFF. |
| [getBeige](#getBeige--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF5F5DC. |
| [getBisque](#getBisque--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFE4C4. |
| [getBlack](#getBlack--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF000000. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFEBCD. |
| [getBlue](#getBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF0000FF. |
| [getBlueViolet](#getBlueViolet--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF8A2BE2. |
| [getBrown](#getBrown--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFA52A2A. |
| [getBurlyWood](#getBurlyWood--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFDEB887. |
| [getCadetBlue](#getCadetBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF5F9EA0. |
| [getChartreuse](#getChartreuse--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF7FFF00. |
| [getChocolate](#getChocolate--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFD2691E. |
| [getColorSpace](#getColorSpace--) | Obtient l'espace de couleur que la couleur représente. |
| [getCoral](#getCoral--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF7F50. |
| [getCornflowerBlue](#getCornflowerBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF6495ED. |
| [getCornsilk](#getCornsilk--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFF8DC. |
| [getCrimson](#getCrimson--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFDC143C. |
| [getCyan](#getCyan--) | Obtient une couleur définie par le système ayant une valeur ARGB de #FF00FFFF. |
| [getDarkBlue](#getDarkBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF00008B. |
| [getDarkCyan](#getDarkCyan--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF008B8B. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFB8860B. |
| [getDarkGray](#getDarkGray--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFA9A9A9. |
| [getDarkGreen](#getDarkGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF006400. |
| [getDarkKhaki](#getDarkKhaki--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFBDB76B. |
| [getDarkMagenta](#getDarkMagenta--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF8B008B. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF556B2F. |
| [getDarkOrange](#getDarkOrange--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF9932CC. |
| [getDarkRed](#getDarkRed--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF9400D3. |
| [getData](#getData--) | Valeur de couleur. |
| [getDeepPink](#getDeepPink--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF00BFFF. |
| [getDimGray](#getDimGray--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFB22222. |
| [getFloralWhite](#getFloralWhite--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFAF0. |
| [getForestGreen](#getForestGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF228B22. |
| [getFuchsia](#getFuchsia--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF00FF. |
| [getGainsboro](#getGainsboro--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFDCDCDC. |
| [getGhostWhite](#getGhostWhite--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF8F8FF. |
| [getGold](#getGold--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFD700. |
| [getGoldenrod](#getGoldenrod--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFDAA520. |
| [getGray](#getGray--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF808080. |
| [getGreen](#getGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF008000. |
| [getGreenYellow](#getGreenYellow--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFADFF2F. |
| [getHoneydew](#getHoneydew--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF0FFF0. |
| [getHotPink](#getHotPink--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF69B4. |
| [getIndianRed](#getIndianRed--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFCD5C5C. |
| [getIndigo](#getIndigo--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF4B0082. |
| [getIvory](#getIvory--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFFF0. |
| [getKhaki](#getKhaki--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF0E68C. |
| [getLavender](#getLavender--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFE6E6FA. |
| [getLavenderBlush](#getLavenderBlush--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFF0F5. |
| [getLawnGreen](#getLawnGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF7CFC00. |
| [getLemonChiffon](#getLemonChiffon--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFACD. |
| [getLightBlue](#getLightBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFADD8E6. |
| [getLightCoral](#getLightCoral--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF08080. |
| [getLightCyan](#getLightCyan--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFE0FFFF. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFAFAD2. |
| [getLightGray](#getLightGray--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFD3D3D3. |
| [getLightGreen](#getLightGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF90EE90. |
| [getLightPink](#getLightPink--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFB6C1. |
| [getLightSalmon](#getLightSalmon--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFA07A. |
| [getLightSeaGreen](#getLightSeaGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF20B2AA. |
| [getLightSkyBlue](#getLightSkyBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF87CEFA. |
| [getLightSlateGray](#getLightSlateGray--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF778899. |
| [getLightSteelBlue](#getLightSteelBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFB0C4DE. |
| [getLightYellow](#getLightYellow--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFFE0. |
| [getLime](#getLime--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF00FF00. |
| [getLimeGreen](#getLimeGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF32CD32. |
| [getLinen](#getLinen--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFFAF0E6. |
| [getMagenta](#getMagenta--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF00FF. |
| [getMaroon](#getMaroon--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF800000. |
| [getMediumAquamarine](#getMediumAquamarine--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF66CDAA. |
| [getMediumBlue](#getMediumBlue--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF0000CD. |
| [getMediumOrchid](#getMediumOrchid--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFBA55D3. |
| [getMediumPurple](#getMediumPurple--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF9370DB. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF3CB371. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF7B68EE. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF00FA9A. |
| [getMediumTurquoise](#getMediumTurquoise--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF48D1CC. |
| [getMediumVioletRed](#getMediumVioletRed--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFC71585. |
| [getMidnightBlue](#getMidnightBlue--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF191970. |
| [getMintCream](#getMintCream--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFF5FFFA. |
| [getMistyRose](#getMistyRose--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFFFE4E1. |
| [getMoccasin](#getMoccasin--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFFFE4B5. |
| [getNavajoWhite](#getNavajoWhite--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFFFDEAD. |
| [getNavy](#getNavy--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF000080. |
| [getOldLace](#getOldLace--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFFDF5E6. |
| [getOlive](#getOlive--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF808000. |
| [getOliveDrab](#getOliveDrab--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF6B8E23. |
| [getOrange](#getOrange--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFFFA500. |
| [getOrangeRed](#getOrangeRed--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFFF4500. |
| [getOrchid](#getOrchid--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFDA70D6. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | Obtient une couleur définie par le système dont la valeur ARGB est #FFEEE8AA. |
| [getPaleGreen](#getPaleGreen--) | Obtient une couleur définie par le système dont la valeur ARGB est #FF98FB98. |
| [getPaleTurquoise](#getPaleTurquoise--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFAFEEEE. |
| [getPaleVioletRed](#getPaleVioletRed--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFDB7093. |
| [getPapayaWhip](#getPapayaWhip--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFEFD5. |
| [getPatternColorSpace](#getPatternColorSpace--) | Obtient un objet qui indique l'espace colorimétrique du motif. Usage interne uniquement. |
| [getPeachPuff](#getPeachPuff--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFDAB9. |
| [getPeru](#getPeru--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFCD853F. |
| [getPink](#getPink--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFC0CB. |
| [getPlum](#getPlum--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFDDA0DD. |
| [getPowderBlue](#getPowderBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFB0E0E6. |
| [getPurple](#getPurple--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF800080. |
| [getRed](#getRed--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF0000. |
| [getRosyBrown](#getRosyBrown--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFBC8F8F. |
| [getRoyalBlue](#getRoyalBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF4169E1. |
| [getSaddleBrown](#getSaddleBrown--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF8B4513. |
| [getSalmon](#getSalmon--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFA8072. |
| [getSandyBrown](#getSandyBrown--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF4A460. |
| [getSeaGreen](#getSeaGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF2E8B57. |
| [getSeaShell](#getSeaShell--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFF5EE. |
| [getSienna](#getSienna--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFA0522D. |
| [getSilver](#getSilver--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFC0C0C0. |
| [getSkyBlue](#getSkyBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF87CEEB. |
| [getSlateBlue](#getSlateBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF6A5ACD. |
| [getSlateGray](#getSlateGray--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF708090. |
| [getSnow](#getSnow--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFAFA. |
| [getSpringGreen](#getSpringGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF00FF7F. |
| [getSteelBlue](#getSteelBlue--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF4682B4. |
| [getTan](#getTan--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFD2B48C. |
| [getTeal](#getTeal--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF008080. |
| [getThistle](#getThistle--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFD8BFD8. |
| [getTomato](#getTomato--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF6347. |
| [getTransparent](#getTransparent--) | Obtient une couleur définie par le système. |
| [getTurquoise](#getTurquoise--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF40E0D0. |
| [getViolet](#getViolet--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFEE82EE. |
| [getWheat](#getWheat--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF5DEB3. |
| [getWhite](#getWhite--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFFFF. |
| [getWhiteSmoke](#getWhiteSmoke--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFF5F5F5. |
| [getYellow](#getYellow--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFF00. |
| [getYellowGreen](#getYellowGreen--) | Obtient une couleur définie par le système qui a une valeur ARGB de #FF9ACD32. |
| [hashCode](#hashCode--) | Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit toujours renvoyer le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont inégaux selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets inégaux peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Ceci est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Renvoie true si deux Colors sont égaux. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Renvoie true si deux Colors ne sont pas égaux. |
| [parse](#parse-java.lang.String-) | Extrait les composants de couleur de la chaîne. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Définit un objet qui indique l'espace colorimétrique du motif. Usage interne uniquement |
| [toRgb](#toRgb--) | Convertit la couleur en rgb. |
| [toString](#toString--) | Convertit en chaîne. |

### Default {#Default}
```
public static final Color Default
```

Représente la couleur par défaut.

### Empty {#Empty}
```
public static final Color Empty
```

Représente une couleur vide.

### Color {#Color--}
```
public Color()
```

Constructeur par défaut.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

Constructeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vecteur |  | tableau double[] |

### deepClone {#deepClone--}
```
public Color deepClone()
```

Clone cette instance

**Returns:**
Objet Color

### equals {#equals-java.lang.Object-}
Renvoie true si deux Colors sont égaux.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

Obtient un objet pdf Color valide à partir des composants de couleur RVB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r |  | Le composant couleur Rouge (valeur 0 - 255). |
| g |  | Le composant couleur Vert (valeur 0 - 255). |
| b |  | Le composant couleur bleu (valeur 0 - 255). |

**Returns:**
Objet Color avec chaque valeur de composant dans la plage [0..255].

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

Obtient un objet pdf Color valide à partir des composants de couleur RVB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a |  | La valeur du composant alpha (valeur 0 - 255). |
| r |  | Le composant couleur Rouge (valeur 0 - 255). |
| g |  | Le composant couleur Vert (valeur 0 - 255). |
| b |  | Le composant couleur bleu (valeur 0 - 255). |

**Returns:**
Objet Color avec chaque valeur de composant dans la plage [0..255].

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

Obtient un objet pdf Color valide à partir des composants de couleur CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c |  | Le composant couleur cyan (valeur 0 - 1). |
| m |  | Le composant couleur magenta (valeur 0 - 1). |
| y |  | Le composant couleur jaune (valeur 0 - 1). |
| k |  | Le composant couleur Key (valeur 0 - 1). |

**Returns:**
Objet Color avec chaque valeur de composant dans la plage [0..1].

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Obtient un objet pdf Color valide à partir du composant de couleur gris.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g |  | Le composant couleur gris (valeur 0 - 1). |

**Returns:**
Objet Color avec chaque valeur de composant dans la plage [0..1].

### fromRgb {#fromRgb-java.awt.Color-}
Obtient un objet pdf Color valide à partir de la valeur java.awt.Color.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

Obtient un objet pdf Color valide à partir des composants de couleur RVB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r |  | Le composant couleur rouge (valeur 0 - 1). |
| g |  | Le composant couleur vert (valeur 0 - 1). |
| b |  | Le composant couleur bleu (valeur 0 - 1). |

**Returns:**
Objet Color avec chaque valeur de composant dans la plage [0..1].

### getA {#getA--}
```
public double getA()
```

Obtient la valeur du composant alpha

**Returns:**
valeur double

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

Obtient une couleur définie par le système ayant une valeur ARGB de #FFF0F8FF.

**Returns:**
A représentant une couleur définie par le système.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

Obtient une couleur définie par le système ayant une valeur ARGB de #FFFAEBD7.

**Returns:**
A représentant une couleur définie par le système.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

Obtient une couleur définie par le système ayant une valeur ARGB de #FF00FFFF.

**Returns:**
A représentant une couleur définie par le système.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

Obtient une couleur définie par le système ayant une valeur ARGB de #FF7FFFD4.

**Returns:**
A représentant une couleur définie par le système.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF0FFFF.

**Returns:**
A représentant une couleur définie par le système.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF5F5DC.

**Returns:**
A représentant une couleur définie par le système.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFE4C4.

**Returns:**
A représentant une couleur définie par le système.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF000000.

**Returns:**
A représentant une couleur définie par le système.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFEBCD.

**Returns:**
A représentant une couleur définie par le système.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF0000FF.

**Returns:**
A représentant une couleur définie par le système.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF8A2BE2.

**Returns:**
A représentant une couleur définie par le système.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFA52A2A.

**Returns:**
A représentant une couleur définie par le système.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFDEB887.

**Returns:**
A représentant une couleur définie par le système.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF5F9EA0.

**Returns:**
A représentant une couleur définie par le système.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF7FFF00.

**Returns:**
A représentant une couleur définie par le système.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFD2691E.

**Returns:**
A représentant une couleur définie par le système.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Obtient l'espace de couleur que la couleur représente.

**Returns:**
Objet ColorSpace

### getCoral {#getCoral--}
```
public static Color getCoral()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF7F50.

**Returns:**
A représentant une couleur définie par le système.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF6495ED.

**Returns:**
A représentant une couleur définie par le système.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFF8DC.

**Returns:**
A représentant une couleur définie par le système.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFDC143C.

**Returns:**
A représentant une couleur définie par le système.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

Obtient une couleur définie par le système ayant une valeur ARGB de #FF00FFFF.

**Returns:**
A représentant une couleur définie par le système.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF00008B.

**Returns:**
A représentant une couleur définie par le système.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF008B8B.

**Returns:**
A représentant une couleur définie par le système.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFB8860B.

**Returns:**
A représentant une couleur définie par le système.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFA9A9A9.

**Returns:**
A représentant une couleur définie par le système.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF006400.

**Returns:**
A représentant une couleur définie par le système.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFBDB76B.

**Returns:**
A représentant une couleur définie par le système.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF8B008B.

**Returns:**
A représentant une couleur définie par le système.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF556B2F.

**Returns:**
A représentant une couleur définie par le système.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF8C00.

**Returns:**
A représentant une couleur définie par le système.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF9932CC.

**Returns:**
A représentant une couleur définie par le système.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF8B0000.

**Returns:**
A représentant une couleur définie par le système.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFE9967A.

**Returns:**
A représentant une couleur définie par le système.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF8FBC8F.

**Returns:**
A représentant une couleur définie par le système.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF483D8B.

**Returns:**
A représentant une couleur définie par le système.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF2F4F4F.

**Returns:**
A représentant une couleur définie par le système.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF00CED1.

**Returns:**
A représentant une couleur définie par le système.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF9400D3.

**Returns:**
A représentant une couleur définie par le système.

### getData {#getData--}
```
public double[] getData()
```

Valeur de couleur.

**Returns:**
tableau de valeurs double

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF1493.

**Returns:**
A représentant une couleur définie par le système.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF00BFFF.

**Returns:**
A représentant une couleur définie par le système.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF696969.

**Returns:**
A représentant une couleur définie par le système.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF1E90FF.

**Returns:**
A représentant une couleur définie par le système.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFB22222.

**Returns:**
A représentant une couleur définie par le système.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFAF0.

**Returns:**
A représentant une couleur définie par le système.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF228B22.

**Returns:**
A représentant une couleur définie par le système.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF00FF.

**Returns:**
A représentant une couleur définie par le système.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFDCDCDC.

**Returns:**
A représentant une couleur définie par le système.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF8F8FF.

**Returns:**
A représentant une couleur définie par le système.

### getGold {#getGold--}
```
public static Color getGold()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFD700.

**Returns:**
A représentant une couleur définie par le système.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFDAA520.

**Returns:**
A représentant une couleur définie par le système.

### getGray {#getGray--}
```
public static Color getGray()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF808080.

**Returns:**
Une structure représentant une couleur définie par le système.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF008000.

**Returns:**
A représentant une couleur définie par le système.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFADFF2F.

**Returns:**
A représentant une couleur définie par le système.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF0FFF0.

**Returns:**
A représentant une couleur définie par le système.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF69B4.

**Returns:**
A représentant une couleur définie par le système.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFCD5C5C.

**Returns:**
A représentant une couleur définie par le système.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF4B0082.

**Returns:**
A représentant une couleur définie par le système.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFFF0.

**Returns:**
A représentant une couleur définie par le système.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF0E68C.

**Returns:**
A représentant une couleur définie par le système.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFE6E6FA.

**Returns:**
A représentant une couleur définie par le système.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFF0F5.

**Returns:**
A représentant une couleur définie par le système.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF7CFC00.

**Returns:**
A représentant une couleur définie par le système.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFACD.

**Returns:**
A représentant une couleur définie par le système.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFADD8E6.

**Returns:**
A représentant une couleur définie par le système.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF08080.

**Returns:**
A représentant une couleur définie par le système.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFE0FFFF.

**Returns:**
A représentant une couleur définie par le système.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFAFAD2.

**Returns:**
A représentant une couleur définie par le système.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFD3D3D3.

**Returns:**
A représentant une couleur définie par le système.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF90EE90.

**Returns:**
A représentant une couleur définie par le système.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFB6C1.

**Returns:**
A représentant une couleur définie par le système.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFA07A.

**Returns:**
A représentant une couleur définie par le système.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF20B2AA.

**Returns:**
A représentant une couleur définie par le système.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF87CEFA.

**Returns:**
A représentant une couleur définie par le système.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF778899.

**Returns:**
A représentant une couleur définie par le système.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFB0C4DE.

**Returns:**
A représentant une couleur définie par le système.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFFE0.

**Returns:**
A représentant une couleur définie par le système.

### getLime {#getLime--}
```
public static Color getLime()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF00FF00.

**Returns:**
A représentant une couleur définie par le système.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF32CD32.

**Returns:**
A représentant une couleur définie par le système.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFFAF0E6.

**Returns:**
A représentant une couleur définie par le système.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF00FF.

**Returns:**
A représentant une couleur définie par le système.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF800000.

**Returns:**
A représentant une couleur définie par le système.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF66CDAA.

**Returns:**
A représentant une couleur définie par le système.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF0000CD.

**Returns:**
A représentant une couleur définie par le système.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFBA55D3.

**Returns:**
A représentant une couleur définie par le système.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF9370DB.

**Returns:**
A représentant une couleur définie par le système.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF3CB371.

**Returns:**
A représentant une couleur définie par le système.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF7B68EE.

**Returns:**
A représentant une couleur définie par le système.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF00FA9A.

**Returns:**
A représentant une couleur définie par le système.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF48D1CC.

**Returns:**
A représentant une couleur définie par le système.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFC71585.

**Returns:**
A représentant une couleur définie par le système.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF191970.

**Returns:**
A représentant une couleur définie par le système.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFF5FFFA.

**Returns:**
A représentant une couleur définie par le système.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFFFE4E1.

**Returns:**
A représentant une couleur définie par le système.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFFFE4B5.

**Returns:**
A représentant une couleur définie par le système.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFFFDEAD.

**Returns:**
A représentant une couleur définie par le système.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF000080.

**Returns:**
A représentant une couleur définie par le système.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFFDF5E6.

**Returns:**
A représentant une couleur définie par le système.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF808000.

**Returns:**
A représentant une couleur définie par le système.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF6B8E23.

**Returns:**
A représentant une couleur définie par le système.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFFFA500.

**Returns:**
A représentant une couleur définie par le système.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFFF4500.

**Returns:**
A représentant une couleur définie par le système.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFDA70D6.

**Returns:**
A représentant une couleur définie par le système.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FFEEE8AA.

**Returns:**
A représentant une couleur définie par le système.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

Obtient une couleur définie par le système dont la valeur ARGB est #FF98FB98.

**Returns:**
A représentant une couleur définie par le système.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFAFEEEE.

**Returns:**
A représentant une couleur définie par le système.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFDB7093.

**Returns:**
A représentant une couleur définie par le système.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFEFD5.

**Returns:**
A représentant une couleur définie par le système.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

Obtient un objet qui indique l'espace colorimétrique du motif. Usage interne uniquement.

**Returns:**
Objet PatternColorSpace

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFDAB9.

**Returns:**
A représentant une couleur définie par le système.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFCD853F.

**Returns:**
A représentant une couleur définie par le système.

### getPink {#getPink--}
```
public static Color getPink()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFC0CB.

**Returns:**
A représentant une couleur définie par le système.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFDDA0DD.

**Returns:**
A représentant une couleur définie par le système.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFB0E0E6.

**Returns:**
A représentant une couleur définie par le système.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF800080.

**Returns:**
A représentant une couleur définie par le système.

### getRed {#getRed--}
```
public static Color getRed()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF0000.

**Returns:**
A représentant une couleur définie par le système.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFBC8F8F.

**Returns:**
A représentant une couleur définie par le système.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF4169E1.

**Returns:**
A représentant une couleur définie par le système.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF8B4513.

**Returns:**
A représentant une couleur définie par le système.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFA8072.

**Returns:**
A représentant une couleur définie par le système.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF4A460.

**Returns:**
A représentant une couleur définie par le système.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF2E8B57.

**Returns:**
A représentant une couleur définie par le système.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFF5EE.

**Returns:**
A représentant une couleur définie par le système.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFA0522D.

**Returns:**
A représentant une couleur définie par le système.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFC0C0C0.

**Returns:**
A représentant une couleur définie par le système.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF87CEEB.

**Returns:**
A représentant une couleur définie par le système.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF6A5ACD.

**Returns:**
A représentant une couleur définie par le système.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF708090.

**Returns:**
A représentant une couleur définie par le système.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFAFA.

**Returns:**
A représentant une couleur définie par le système.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF00FF7F.

**Returns:**
A représentant une couleur définie par le système.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF4682B4.

**Returns:**
A représentant une couleur définie par le système.

### getTan {#getTan--}
```
public static Color getTan()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFD2B48C.

**Returns:**
A représentant une couleur définie par le système.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF008080.

**Returns:**
A représentant une couleur définie par le système.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFD8BFD8.

**Returns:**
A représentant une couleur définie par le système.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFF6347.

**Returns:**
A représentant une couleur définie par le système.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

Obtient une couleur définie par le système.

**Returns:**
A représentant une couleur définie par le système.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF40E0D0.

**Returns:**
A représentant une couleur définie par le système.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFEE82EE.

**Returns:**
A représentant une couleur définie par le système.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF5DEB3.

**Returns:**
A représentant une couleur définie par le système.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFFFF.

**Returns:**
A représentant une couleur définie par le système.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFF5F5F5.

**Returns:**
A représentant une couleur définie par le système.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FFFFFF00.

**Returns:**
A représentant une couleur définie par le système.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

Obtient une couleur définie par le système qui a une valeur ARGB de #FF9ACD32.

**Returns:**
A représentant une couleur définie par le système.

### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie une valeur de code de hachage pour l'objet. Cette méthode est prise en charge pour le bénéfice des tables de hachage telles que celles fournies par {@link java.util.HashMap}. <p> Le contrat général de {@code hashCode} est : <ul> <li>Chaque fois qu'elle est invoquée sur le même objet plus d'une fois pendant l'exécution d'une application Java, la méthode {@code hashCode} doit toujours renvoyer le même entier, à condition qu'aucune information utilisée dans les comparaisons {@code equals} sur l'objet ne soit modifiée. Cet entier n'a pas besoin de rester identique d'une exécution d'une application à une autre exécution de la même application. <li>Si deux objets sont égaux selon la méthode {@code equals(Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets doit produire le même résultat entier. <li>Il n'est <em>pas</em> requis que si deux objets sont inégaux selon la méthode {@link java.lang.Object#equals(java.lang.Object)}, alors appeler la méthode {@code hashCode} sur chacun des deux objets produise des résultats entiers distincts. Cependant, le programmeur doit être conscient que produire des résultats entiers distincts pour des objets inégaux peut améliorer les performances des tables de hachage. </ul> <p> Autant que cela soit raisonnablement praticable, la méthode hashCode définie par la classe {@code Object} renvoie des entiers distincts pour des objets distincts. (Ceci est généralement implémenté en convertissant l'adresse interne de l'objet en un entier, mais cette technique d'implémentation n'est pas requise par le langage de programmation Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
une valeur de code de hachage pour cet objet. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Renvoie true si deux Colors sont égaux.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Renvoie true si deux Colors ne sont pas égaux.

### parse {#parse-java.lang.String-}
Extrait les composants de couleur de la chaîne.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
Définit un objet qui indique l'espace colorimétrique du motif. Usage interne uniquement

### toRgb {#toRgb--}
```
public Color toRgb()
```

Convertit la couleur en rgb.

**Returns:**
Valeur couleur Rgb.

### toString {#toString--}
```
public String toString()
```

Convertit en chaîne.

**Returns:**
Représentation sous forme de chaîne de l'objet Color.
