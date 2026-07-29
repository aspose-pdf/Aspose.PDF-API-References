---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Widget açıklamasını temsil eden sınıf."
type: docs
weight: 5540
url: /tr/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Widget açıklamasını temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Ek açıklama oluştur (Generator için kullanılır) |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Ziyaretçiyi kabul eder. |
| [getAnnotationActions](#getAnnotationActions--) | Ek açıklama eylemlerini alır. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getCheckedStateName](#getCheckedStateName--) | Mevcut durum adlarına göre "checked" durumunun adını döndürür. |
| [getDefaultAppearance](#getDefaultAppearance--) | Alanının varsayılan görünümünü alır. |
| [getExportable](#getExportable--) | Alanının dışa aktarılabilir bayrağını alır. |
| [getHighlighting](#getHighlighting--) | Ek açıklama vurgulama modu. |
| [getOnActivated](#getOnActivated--) | Ek açıklama etkinleştirildiğinde gerçekleştirilecek bir eylemi al. |
| [getParent](#getParent--) | Ek açıklama üst öğesini al. |
| [getReadOnly](#getReadOnly--) | Alanının yalnızca okunur durumunu al. |
| [getRequired](#getRequired--) | Alanının gerekli durumunu al. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Alanının varsayılan görünümünü ayarlar. |
| [setExportable](#setExportable-boolean-) | Alanının yalnızca okunur durumunu ayarlar. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Ek açıklama vurgulama modu. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Ek açıklama etkinleştirildiğinde gerçekleştirilecek bir eylemi ayarla. |
| [setReadOnly](#setReadOnly-boolean-) | Alanının yalnızca okunur durumunu ayarlar. |
| [setRequired](#setRequired-boolean-) | Alanının yalnızca okunur durumunu ayarlar. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Ek açıklama oluştur (Generator için kullanılır)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Ziyaretçiyi kabul eder.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Ek açıklama eylemlerini alır.

**Returns:**
AnnotationActionCollection nesnesi

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Mevcut durum adlarına göre "checked" durumunun adını döndürür.

**Returns:**
Bu ek açıklama için "checked" durumunun adı.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Alanının varsayılan görünümünü alır.

**Returns:**
DefaultAppearance nesnesi

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Alanının dışa aktarılabilir bayrağını alır.

**Returns:**
boolean değer

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Ek açıklama vurgulama modu.

**Returns:**
HighlightingMode değeri @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Ek açıklama etkinleştirildiğinde gerçekleştirilecek bir eylemi al.

**Returns:**
PdfAction nesnesi

### getParent {#getParent--}
```
public Field getParent()
```

Ek açıklama üst öğesini al.

**Returns:**
Field nesnesi

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Alanının yalnızca okunur durumunu al.

**Returns:**
boolean değer

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Alanının gerekli durumunu al.

**Returns:**
boolean değer

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Alanının varsayılan görünümünü ayarlar.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Alanının yalnızca okunur durumunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Ek açıklama vurgulama modu.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Ek açıklama etkinleştirildiğinde gerçekleştirilecek bir eylemi ayarla.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Alanının yalnızca okunur durumunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Alanının yalnızca okunur durumunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
