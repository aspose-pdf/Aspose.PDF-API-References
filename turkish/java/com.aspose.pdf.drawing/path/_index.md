---
title: "Yol"
linktitle: "Yol"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yayı temsil eder."
type: docs
weight: 100
url: /tr/java/com.aspose.pdf.drawing/path/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Path, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Path

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Path extends Shape
```

Yayı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Path](#Path--) | Yeni bir {@code Path} sınıfının örneğini başlatır. |
| [Path](#Path-com.aspose.pdf.drawing.Shape:A-) | Yeni bir {@code Path} sınıfının örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Öğenin verilen konteyner boyutlarına (dahil) sığıp sığmadığını kontrol eder. |
| [getShapes](#getShapes--) | <p> Şekiller koleksiyonunu alır veya ayarlar. </p> |
| [getShapesInternal](#getShapesInternal--) | Şekiller koleksiyonunu alır veya ayarlar. |

### Path {#Path--}
```
public Path()
```

Yeni bir {@code Path} sınıfının örneğini başlatır.

### Path {#Path-com.aspose.pdf.drawing.Shape:A-}
Yeni bir {@code Path} sınıfının örneğini başlatır.

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

### getShapes {#getShapes--}
```
public List < Shape > getShapes()
```

<p> Şekiller koleksiyonunu alır veya ayarlar. </p>

**Returns:**
{@code java.util.List<Shape> }nesne

### getShapesInternal {#getShapesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< Shape > getShapesInternal()
```

Şekiller koleksiyonunu alır veya ayarlar.

**Returns:**
dahili nesne
