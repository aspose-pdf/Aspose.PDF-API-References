---
title: "Ellipse"
linktitle: "Ellipse"
second_title: "Aspose.PDF for Java API Referansı"
description: "Elipsi temsil eder."
type: docs
weight: 40
url: /tr/java/com.aspose.pdf.drawing/ellipse/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Ellipse, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Ellipse

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Ellipse extends Shape
```

Elipsi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Ellipse](#Ellipse--) | Yalnızca dahili kullanım için |
| [Ellipse](#Ellipse-double-double-double-double-) | Yeni bir {@code Ellipse} sınıfı örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder. |
| [getBottom](#getBottom--) | Elipsin alt konumunu gösteren float değeri alır. |
| [getHeight](#getHeight--) | Elipsin yüksekliğini gösteren float değeri alır. |
| [getLeft](#getLeft--) | Elipsin sol konumunu gösteren float değeri alır. |
| [getWidth](#getWidth--) | Elipsin genişliğini gösteren float değerini alır. |
| [setBottom](#setBottom-double-) | Elipsin alt konumunu gösteren float değerini ayarlar. |
| [setHeight](#setHeight-double-) | Elipsin yüksekliğini gösteren float değerini ayarlar. |
| [setLeft](#setLeft-double-) | Elipsin sol konumunu gösteren float değerini ayarlar. |
| [setWidth](#setWidth-double-) | Elipsin genişliğini gösteren float değerini alır. |

### Ellipse {#Ellipse--}
```
public Ellipse()
```

Yalnızca dahili kullanım için

### Ellipse {#Ellipse-double-double-double-double-}
```
public Ellipse(double left, double bottom, double width, double height)
```

Yeni bir {@code Ellipse} sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol |  | Elipsin sol konumu. |
| alt |  | Elipsin alt konumu. |
| genişlik |  | Elipsin genişliği. |
| yükseklik |  | Elipsin yüksekliği. |

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

Elipsin alt konumunu gösteren float değeri alır.

**Returns:**
Elipsin alt konumunu gösteren değer.

### getHeight {#getHeight--}
```
public double getHeight()
```

Elipsin yüksekliğini gösteren float değeri alır.

**Returns:**
Elipsin yüksekliğini gösteren değer

### getLeft {#getLeft--}
```
public double getLeft()
```

Elipsin sol konumunu gösteren float değeri alır.

**Returns:**
Elipsin sol konumunu gösteren değer.

### getWidth {#getWidth--}
```
public double getWidth()
```

Elipsin genişliğini gösteren float değerini alır.

**Returns:**
Elipsin genişliğini gösteren değer.

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

Elipsin alt konumunu gösteren float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | elipsin alt konumunu gösteren. |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Elipsin yüksekliğini gösteren float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | elipsin yüksekliğini gösteren |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Elipsin sol konumunu gösteren float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | elipsin sol konumunu gösteren. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Elipsin genişliğini gösteren float değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | elipsin genişliğini gösteren. |
