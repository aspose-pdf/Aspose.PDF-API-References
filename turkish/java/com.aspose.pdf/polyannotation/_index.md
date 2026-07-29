---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Poli-annotasyonlar için soyut temel sınıf."
type: docs
weight: 3890
url: /tr/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Poli-annotasyonlar için soyut temel sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Matris dönüşümüne göre Vertices içindeki noktaları günceller. |
| [getEndingStyle](#getEndingStyle--) | İkinci satır sonunun stilini alır. |
| [getIntent](#getIntent--) | Poligon veya çoklu çizgi açıklamasının amacını alır. |
| [getInteriorColor](#getInteriorColor--) | Açıklamanın satır sonlarını doldurmak için kullanılacak iç rengi alır. |
| [getMeasure](#getMeasure--) | Bu açıklama için belirtilen ölçü birimleri. |
| [getStartingStyle](#getStartingStyle--) | İlk satır sonunun stilini alır. |
| [getVertices](#getVertices--) | Her köşenin yatay ve dikey koordinatlarını temsil eden nokta dizisini alır. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | İkinci satır sonunun stilini ayarlar. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Poligon veya çoklu çizgi açıklamasının amacını ayarlar. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Açıklamanın satır sonlarını doldurmak için kullanılacak iç rengi ayarlar. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Bu açıklama için belirtilen ölçü birimleri. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | İlk satır sonunun stilini ayarlar. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Her köşenin yatay ve dikey koordinatlarını temsil eden nokta dizisini ayarlar. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Matris dönüşümüne göre Vertices içindeki noktaları günceller.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

İkinci satır sonunun stilini alır.

**Returns:**
LineEnding öğesi @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Poligon veya çoklu çizgi açıklamasının amacını alır.

**Returns:**
PolyIntent öğesi @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Açıklamanın satır sonlarını doldurmak için kullanılacak iç rengi alır.

**Returns:**
Color nesnesi

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Bu açıklama için belirtilen ölçü birimleri.

**Returns:**
Measure örneği

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

İlk satır sonunun stilini alır.

**Returns:**
LineEnding öğesi @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Her köşenin yatay ve dikey koordinatlarını temsil eden nokta dizisini alır.

**Returns:**
Point değerlerinin dizisi

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
İkinci satır sonunun stilini ayarlar.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Poligon veya çoklu çizgi açıklamasının amacını ayarlar.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Açıklamanın satır sonlarını doldurmak için kullanılacak iç rengi ayarlar.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Bu açıklama için belirtilen ölçü birimleri.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
İlk satır sonunun stilini ayarlar.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Her köşenin yatay ve dikey koordinatlarını temsil eden nokta dizisini ayarlar.
