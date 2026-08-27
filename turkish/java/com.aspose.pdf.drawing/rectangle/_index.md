---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Aspose.PDF for Java API Referansı"
description: "Dikdörtgeni temsil eder."
type: docs
weight: 120
url: /tr/java/com.aspose.pdf.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Rectangle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Rectangle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Rectangle extends Shape
```

Dikdörtgeni temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Rectangle](#Rectangle--) | Yapıcı |
| [Rectangle](#Rectangle-float-float-float-float-) | Yeni bir {@code Rectangle} sınıfı örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder. |
| [getBottom](#getBottom--) | Dikdörtgenin alt konumunu gösteren float değeri alır. |
| [getHeight](#getHeight--) | Dikdörtgenin yüksekliğini gösteren float değeri alır. |
| [getLeft](#getLeft--) | Dikdörtgenin sol konumunu gösteren float değeri alır. |
| [getRoundedCornerRadius](#getRoundedCornerRadius--) | Dikdörtgen köşelerinin yarıçapını gösteren float değeri alır. |
| [getWidth](#getWidth--) | Dikdörtgenin genişliğini gösteren float değeri alır. |
| [setBottom](#setBottom-double-) | Dikdörtgenin alt konumunu gösteren float değerini ayarlar. |
| [setHeight](#setHeight-double-) | Dikdörtgenin yüksekliğini gösteren float değerini ayarlar. |
| [setLeft](#setLeft-double-) | Dikdörtgenin sol konumunu gösteren float değerini ayarlar. |
| [setRoundedCornerRadius](#setRoundedCornerRadius-double-) | Dikdörtgen köşelerinin yarıçapını gösteren float değerini ayarlar. |
| [setWidth](#setWidth-double-) | Dikdörtgenin genişliğini gösteren float değerini ayarlar. |

### Rectangle {#Rectangle--}
```
public Rectangle()
```

Yapıcı

### Rectangle {#Rectangle-float-float-float-float-}
```
public Rectangle(float left, float bottom, float width, float height)
```

Yeni bir {@code Rectangle} sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol |  | Dikdörtgenin sol konumu. |
| alt |  | Dikdörtgenin alt konumu. |
| genişlik |  | Dikdörtgenin genişliği. |
| yükseklik |  | Dikdörtgenin yüksekliği. |

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

### getBottom {#getBottom--}
```
public double getBottom()
```

Dikdörtgenin alt konumunu gösteren float değeri alır.

**Returns:**
Dikdörtgenin alt konumunu gösteren değer.

### getHeight {#getHeight--}
```
public double getHeight()
```

Dikdörtgenin yüksekliğini gösteren float değeri alır.

**Returns:**
Dikdörtgenin yüksekliğini gösteren değer.

### getLeft {#getLeft--}
```
public double getLeft()
```

Dikdörtgenin sol konumunu gösteren float değeri alır.

**Returns:**
dikdörtgenin sol konumunu gösteren float değer.

### getRoundedCornerRadius {#getRoundedCornerRadius--}
```
public double getRoundedCornerRadius()
```

Dikdörtgen köşelerinin yarıçapını gösteren float değeri alır.

**Returns:**
dikdörtgen köşelerinin yarıçapını gösteren değer.

### getWidth {#getWidth--}
```
public double getWidth()
```

Dikdörtgenin genişliğini gösteren float değeri alır.

**Returns:**
dikdörtgenin genişliğini gösteren değer.

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

Dikdörtgenin alt konumunu gösteren float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Dikdörtgenin alt konumunu gösteren değer. |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Dikdörtgenin yüksekliğini gösteren float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Dikdörtgenin yüksekliğini gösteren değer. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Dikdörtgenin sol konumunu gösteren float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | dikdörtgenin sol konumunu gösteren float değer. |

### setRoundedCornerRadius {#setRoundedCornerRadius-double-}
```
public void setRoundedCornerRadius(double value)
```

Dikdörtgen köşelerinin yarıçapını gösteren float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | dikdörtgen köşelerinin yarıçapını gösterir. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Dikdörtgenin genişliğini gösteren float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | dikdörtgenin genişliğini gösterir. |
