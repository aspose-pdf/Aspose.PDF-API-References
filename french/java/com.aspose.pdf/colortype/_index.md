---
title: "ColorType"
linktitle: "ColorType"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Spécifie le type de couleur des éléments sur la page."
type: docs
weight: 710
url: /fr/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Spécifie le type de couleur des éléments sur la page.

## Champs

| Champ | Description |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Type de couleur noir et blanc. |
| [Grayscale](#Grayscale) | Type de couleur en niveaux de gris. |
| [Rgb](#Rgb) | Type de couleur RVB. |
| [Undefined](#Undefined) | Valeur de type de couleur indéfinie. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Renvoie le nom de la chaîne pour la valeur de l'énumération. </p> <hr> Exemple: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Type de couleur noir et blanc.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Type de couleur en niveaux de gris.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

Type de couleur RVB.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Valeur de type de couleur indéfinie.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Renvoie le nom de la chaîne pour la valeur de l'énumération. </p> <hr> Exemple: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur d'énumération |

**Returns:**
Nom de la valeur

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static ColorType [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
