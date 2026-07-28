---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Caret açıklamasını temsil eden sınıf."
type: docs
weight: 470
url: /tr/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Caret açıklamasını temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Generator içinde usign için yapıcı. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Belirtilen sayfada yeni Caret ek açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getFrame](#getFrame--) | Caret dikdörtgenini alır. |
| [getSymbol](#getSymbol--) | Caret ile ilişkili sembolü alır. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Caret dikdörtgenini ayarlar. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | İçe aktarma için çıktı sayfa boyutunu ayarlar. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Generator içinde usign için yapıcı.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Belirtilen sayfada yeni Caret ek açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Caret dikdörtgenini alır.

**Returns:**
caret dikdörtgeni.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Caret ile ilişkili sembolü alır. {@code CaretSymbol}

**Returns:**
CaretSymbol öğesi @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Caret dikdörtgenini ayarlar.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
İçe aktarma için çıktı sayfa boyutunu ayarlar.
