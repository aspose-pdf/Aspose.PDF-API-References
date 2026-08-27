---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "Aspose.PDF för Java API-referens"
description: "Beskriver sidkoordinattyp. MediaBox = 0 CropBox = 1"
type: docs
weight: 3350
url: /sv/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

Beskriver sidkoordinattyp. MediaBox = 0 CropBox = 1

## Fält

| Fält | Beskrivning |
| --- | --- |
| [CropBox](#CropBox) | CropBox definierar regionen som sidans innehåll ska beskäras till. |
| [MediaBox](#MediaBox) | MediaBox används för att ange sidans bredd och höjd. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

CropBox definierar regionen som sidans innehåll ska beskäras till.

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

MediaBox används för att ange sidans bredd och höjd.

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static PageCoordinateType [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
