---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesindeki bir noktaya eklenmiş \\\"yapışkan not\\\" olan bir metin açıklamasını temsil eder."
type: docs
weight: 4920
url: /tr/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

PDF belgesindeki bir noktaya eklenmiş "yapışkan not" olan bir metin açıklamasını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | TextAnnotation örneği oluştur |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | TextAnnotation örneği oluştur |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | TextAnnotation örneği oluştur |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Temel sınıftaki tanımı boş bir gövdeyle geçersiz kılar. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getIcon](#getIcon--) | Açıklamayı görüntülerken kullanılacak bir simge alır. |
| [getOpen](#getOpen--) | Açıklamanın başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrağı alır. |
| [setIcon](#setIcon-int-) | Açıklamayı görüntülerken kullanılacak bir simge ayarlar. |
| [setOpen](#setOpen-boolean-) | Açıklamanın başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrağı ayarlar. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

TextAnnotation örneği oluştur

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
TextAnnotation örneği oluştur

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
TextAnnotation örneği oluştur

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Temel sınıftaki tanımı boş bir gövdeyle geçersiz kılar.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType değeri @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Açıklamayı görüntülerken kullanılacak bir simge alır.

**Returns:**
TextIcon değeri @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Açıklamanın başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrağı alır.

**Returns:**
boolean değer

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Açıklamayı görüntülerken kullanılacak bir simge ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | TextIcon değeri @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Açıklamanın başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
