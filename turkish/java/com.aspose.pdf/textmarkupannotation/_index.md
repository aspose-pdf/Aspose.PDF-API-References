---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin işaretleme ek açıklamaları için soyut temel sınıf."
type: docs
weight: 5180
url: /tr/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Metin işaretleme ek açıklamaları için soyut temel sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | QuadPoints'ı, matris dönüşümüne göre günceller. |
| [getMarkedText](#getMarkedText--) | İşaretleme açıklaması altındaki metni dize olarak alır. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | İşaretleme açıklaması altındaki metni {@code TextFragmentCollection} olarak alır. |
| [getQuadPoints](#getQuadPoints--) | n dörtgenin koordinatlarını belirten nokta dizisini alır. Her dörtgen, açıklamanın altındaki metinde bir kelimeyi veya ardışık kelimeler grubunu kapsar. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | n dörtgenin koordinatlarını belirten nokta dizisini ayarlar. Her dörtgen, açıklamanın altındaki metinde bir kelimeyi veya ardışık kelimeler grubunu kapsar. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
QuadPoints'ı, matris dönüşümüne göre günceller.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

İşaretleme açıklaması altındaki metni dize olarak alır.

**Returns:**
İşaretleme açıklaması altında bulunan metni içeren dize.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

İşaretleme açıklaması altındaki metni {@code TextFragmentCollection} olarak alır.

**Returns:**
{@code TextFragmentCollection} içinde işaretleme açıklaması altında bulunan {@code TextFragment}s.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

n dörtgenin koordinatlarını belirten nokta dizisini alır. Her dörtgen, açıklamanın altındaki metinde bir kelimeyi veya ardışık kelimeler grubunu kapsar.

**Returns:**
Point değerlerinin dizisi

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
n dörtgenin koordinatlarını belirten nokta dizisini ayarlar. Her dörtgen, açıklamanın altındaki metinde bir kelimeyi veya ardışık kelimeler grubunu kapsar.
