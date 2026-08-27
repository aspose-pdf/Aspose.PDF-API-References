---
title: "Line"
linktitle: "Line"
second_title: "Aspose.PDF for Java API Referansı"
description: "Çizgiyi temsil eder."
type: docs
weight: 90
url: /tr/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Çizgiyi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Line](#Line--) | Yalnızca dahili kullanım için |
| [Line](#Line-float:A-) | Yeni bir {@code Line} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder. |
| [getPositionArray](#getPositionArray--) | Pozisyon dizisini gösteren nesneyi alır. Dizi, doğrudan çizginin her kontrol noktasının koordinatlarından oluşur. |
| [setPositionArray](#setPositionArray-float:A-) | Pozisyon dizisini gösteren nesneyi ayarlar. Dizi, doğrudan çizginin her kontrol noktasının koordinatlarından oluşur. |

### Line {#Line--}
```
public Line()
```

Yalnızca dahili kullanım için

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Yeni bir {@code Line} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| positionArray |  | Çizgi konum dizisi. |

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

Pozisyon dizisini gösteren nesneyi alır. Dizi, doğrudan çizginin her kontrol noktasının koordinatlarından oluşur.

**Returns:**
konum dizisini gösteren.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Pozisyon dizisini gösteren nesneyi ayarlar. Dizi, doğrudan çizginin her kontrol noktasının koordinatlarından oluşur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | konum dizisini gösteren. |
