---
title: "Shape"
linktitle: "Shape"
second_title: "Aspose.PDF for Java API Referansı"
description: "Şekli - temel grafik nesnesini temsil eder."
type: docs
weight: 130
url: /tr/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Şekli - temel grafik nesnesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Shape](#Shape--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder. |
| [getGraphInfo](#getGraphInfo--) | Grafik bilgilerini gösteren nesneyi alır, örneğin renk, çizgi genişliği, vb. |
| [getText](#getText--) | Şekil için metni alır veya ayarlar |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Grafik bilgilerini gösteren nesneyi ayarlar, örneğin renk, çizgi genişliği, vb. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Şekil için metni alır veya ayarlar |

### Shape {#Shape--}
```
public Shape()
```



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

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Grafik bilgilerini gösteren nesneyi alır, örneğin renk, çizgi genişliği, vb.

**Returns:**
grafik bilgilerini gösteren nesne.

### getText {#getText--}
```
public TextFragment getText()
```

Şekil için metni alır veya ayarlar

**Returns:**
TextFragment nesnesi

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Grafik bilgilerini gösteren nesneyi ayarlar, örneğin renk, çizgi genişliği, vb.

### setText {#setText-com.aspose.pdf.TextFragment-}
Şekil için metni alır veya ayarlar
