---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Serbest el \\\"scribble\\\" bir veya daha fazla ayrı yoldan oluşur."
type: docs
weight: 2430
url: /tr/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Bir veya daha fazla ayrı yoldan oluşan serbest el "karalama"yı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Generator için Ink ek açıklaması oluşturucusu. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Belirtilen sayfada yeni Ink ek açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | InkList'teki noktaları, matris dönüşümüne göre günceller. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getCapStyle](#getCapStyle--) | ink ek açıklaması çizgi uçlarının stilini al. |
| [getInkList](#getInkList--) | <p> Bağımsız çizgiler olan ve Point[] dizileriyle temsil edilen jestlerin listesini alır. </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Mürekkep ek açıklama satır sonlarının stilini ayarla. |
| [setInkList](#setInkList-java.util.List-) | Bağımsız satırlar olan ve Point[] dizileriyle temsil edilen hareketlerin listesini ayarlar. |
| [updateAppearance](#updateAppearance--) | Metin değiştirildikten/taşındıktan sonra Görünümü günceller. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Generator için Ink ek açıklaması oluşturucusu.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Belirtilen sayfada yeni Ink ek açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
InkList'teki noktaları, matris dönüşümüne göre günceller.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

ink ek açıklaması çizgi uçlarının stilini al.

**Returns:**
CapStyle öğesi @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Bağımsız çizgiler olan ve Point[] dizileriyle temsil edilen jestlerin listesini alır. </p>

**Returns:**
{@code List<Point[]>} nesnesi

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Mürekkep ek açıklama satır sonlarının stilini ayarla.

### setInkList {#setInkList-java.util.List-}
Bağımsız satırlar olan ve Point[] dizileriyle temsil edilen hareketlerin listesini ayarlar.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Metin değiştirildikten/taşındıktan sonra Görünümü günceller.
