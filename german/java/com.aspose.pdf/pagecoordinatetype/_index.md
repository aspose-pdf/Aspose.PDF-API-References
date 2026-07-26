---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Beschreibt den Seitencoordinate-Typ. MediaBox = 0 CropBox = 1"
type: docs
weight: 3350
url: /de/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

Beschreibt den Seitencoordinate-Typ. MediaBox = 0 CropBox = 1

## Felder

| Feld | Beschreibung |
| --- | --- |
| [CropBox](#CropBox) | Der CropBox definiert den Bereich, zu dem der Seiteninhalt zugeschnitten werden soll. |
| [MediaBox](#MediaBox) | Die MediaBox wird verwendet, um die Breite und Höhe der Seite anzugeben. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück. |
| [values](#values--) | Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält. |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

Der CropBox definiert den Bereich, zu dem der Seiteninhalt zugeschnitten werden soll.

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

Die MediaBox wird verwendet, um die Breite und Höhe der Seite anzugeben.

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück.

### values {#values--}
```
public static PageCoordinateType [] values()
```

Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält.

**Returns:**
ein Array, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält
