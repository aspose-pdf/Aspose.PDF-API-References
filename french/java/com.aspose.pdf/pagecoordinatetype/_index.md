---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Décrit le type de coordonnées de page. MediaBox = 0 CropBox = 1"
type: docs
weight: 3350
url: /fr/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

Décrit le type de coordonnées de page. MediaBox = 0 CropBox = 1

## Champs

| Champ | Description |
| --- | --- |
| [CropBox](#CropBox) | Le CropBox définit la région à laquelle le contenu de la page doit être découpé. |
| [MediaBox](#MediaBox) | Le MediaBox est utilisé pour spécifier la largeur et la hauteur de la page. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

Le CropBox définit la région à laquelle le contenu de la page doit être découpé.

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

Le MediaBox est utilisé pour spécifier la largeur et la hauteur de la page.

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static PageCoordinateType [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
