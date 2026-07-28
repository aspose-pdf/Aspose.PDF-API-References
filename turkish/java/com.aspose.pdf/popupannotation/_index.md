---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metni giriş ve düzenleme için bir açılır pencerede gösteren açılır ek açıklamayı temsil eder."
type: docs
weight: 3930
url: /tr/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Metni giriş ve düzenleme için bir açılır pencerede gösteren açılır ek açıklamayı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Yapıcı. Generator içinde kullanmak için. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Belirtilen sayfada yeni Popup açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getOpen](#getOpen--) | Pop-up açıklamasının başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrağı alır. |
| [getParent](#getParent--) | Bu pop-up açıklamasıyla ilişkilendirilecek üst açıklamayı alır. Bu giriş mevcutsa, üst açıklamanın Contents, M, C ve T girdileri, pop-up açıklamasının kendi girdilerinin üzerine yazılır. |
| [setOpen](#setOpen-boolean-) | Pop-up açıklamasının başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrağı ayarlar. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Bu pop-up açıklamasıyla ilişkilendirilecek üst açıklamayı ayarlar. Bu giriş mevcutsa, üst açıklamanın Contents, M, C ve T girdileri, pop-up açıklamasının kendi girdilerinin üzerine yazılır. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Yapıcı. Generator içinde kullanmak için.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Belirtilen sayfada yeni Popup açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Pop-up açıklamasının başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrağı alır.

**Returns:**
boolean değer

### getParent {#getParent--}
```
public Annotation getParent()
```

Bu pop-up açıklamasıyla ilişkilendirilecek üst açıklamayı alır. Bu giriş mevcutsa, üst açıklamanın Contents, M, C ve T girdileri, pop-up açıklamasının kendi girdilerinin üzerine yazılır.

**Returns:**
MarkupAnnotation nesnesi

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Pop-up açıklamasının başlangıçta açık olarak görüntülenip görüntülenmeyeceğini belirten bir bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Bu pop-up açıklamasıyla ilişkilendirilecek üst açıklamayı ayarlar. Bu giriş mevcutsa, üst açıklamanın Contents, M, C ve T girdileri, pop-up açıklamasının kendi girdilerinin üzerine yazılır.
