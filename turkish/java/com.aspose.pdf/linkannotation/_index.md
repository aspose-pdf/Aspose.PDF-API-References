---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Belge içinde başka bir konuma bir hiper metin bağlantısını veya gerçekleştirilecek bir eylemi temsil eder."
type: docs
weight: 2760
url: /tr/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Belge içinde başka bir konuma bir hiper metin bağlantısını veya gerçekleştirilecek bir eylemi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Belirtilen sayfada yeni Link açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [getAction](#getAction--) | Bağlantı açıklaması etkinleştirildiğinde gerçekleştirilecek eylemi al. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getDestination](#getDestination--) | Açıklama etkinleştirildiğinde gösterilecek hedefi al. |
| [getHighlighting](#getHighlighting--) | Fare düğmesi aktif alan içinde basıldığında veya tutulduğunda kullanılacak görsel efekti al. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Bağlantı açıklaması etkinleştirildiğinde gerçekleştirilecek eylemi ayarlar. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Açıklama etkinleştirildiğinde gösterilecek hedefi ayarlar. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Fare düğmesi aktif alan içinde basıldığında veya tutulduğunda kullanılacak görsel efekti ayarlar. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Belirtilen sayfada yeni Link açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Bağlantı açıklaması etkinleştirildiğinde gerçekleştirilecek eylemi al.

**Returns:**
PdfAction değeri

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Açıklama etkinleştirildiğinde gösterilecek hedefi al.

**Returns:**
IAppointment değeri

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Fare düğmesi aktif alan içinde basıldığında veya tutulduğunda kullanılacak görsel efekti al.

**Returns:**
HighlightingMode öğesi @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Bağlantı açıklaması etkinleştirildiğinde gerçekleştirilecek eylemi ayarlar.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Açıklama etkinleştirildiğinde gösterilecek hedefi ayarlar.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Fare düğmesi aktif alan içinde basıldığında veya tutulduğunda kullanılacak görsel efekti ayarlar.
