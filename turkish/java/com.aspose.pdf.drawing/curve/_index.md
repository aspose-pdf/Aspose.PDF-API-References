---
title: "Eğri"
linktitle: "Eğri"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bezier eğrisini temsil eder."
type: docs
weight: 30
url: /tr/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Bezier eğrisini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Curve](#Curve--) | Yalnızca dahili kullanım için |
| [Curve](#Curve-float:A-) | Yeni bir {@code Curve} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder. |
| [getPositionArray](#getPositionArray--) | Bir float konum dizisini alır. |
| [setPositionArray](#setPositionArray-float:A-) | Bir float konum dizisini ayarlar. |

### Curve {#Curve--}
```
public Curve()
```

Yalnızca dahili kullanım için

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Yeni bir {@code Curve} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| positionArray |  | Eğrinin kontrol noktalarının konum dizisi. Dört kontrol noktası olmalıdır, bu yüzden dizinin uzunluğu sekiz olmalıdır. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Sığıyorsa true; aksi takdirde false.

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Bir float konum dizisini alır.

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Bir float konum dizisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float[] array |
