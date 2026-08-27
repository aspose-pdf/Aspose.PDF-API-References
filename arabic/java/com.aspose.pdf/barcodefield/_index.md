---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل حقل الباركود."
type: docs
weight: 250
url: /ar/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

فئة تمثّل حقل الباركود.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | ينشئ مثيلاً جديداً من الفئة {@code BarcodeField}. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ينشئ مثيلاً جديداً من الفئة {@code BarcodeField}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCaption](#getCaption--) | يحصل على تسمية كائن الباركود. |
| [getECC](#getECC--) | يحصل على قيمة عددية تمثل معامل تصحيح الخطأ. بالنسبة لـ PDF417، يجب أن تكون من 0 إلى 8. بالنسبة لـ QRCode، يجب أن تكون من 0 إلى 3 (0 لـ 'L'، 1 لـ 'M'، 2 لـ 'Q'، و3 لـ 'H'). |
| [getResolution](#getResolution--) | يحصل على الدقة، بوحدة النقاط لكل بوصة (dpi)، التي يُعرض بها كائن الباركود. |
| [getSymbology](#getSymbology--) | يحدد أي تقنية باركود أو رموز تُستخدم في هذه التعليقة، راجع {@code Symbology} للتفاصيل. |
| [getXSymHeight](#getXSymHeight--) | يحصل على المسافة العمودية بين وحدتي باركود، مقاسة بالبكسل. يجب أن تكون نسبة XSymHeight/XSymWidth قيمة عددية صحيحة. بالنسبة لـ PDF417، نطاق النسبة المقبول هو من 1 إلى 4. بالنسبة لـ QRCode و DataMatrix، يجب أن تكون هذه النسبة دائماً 1. |
| [getXSymWidth](#getXSymWidth--) | يحصل على المسافة الأفقية، بالبكسل، بين وحدتي باركود. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
ينشئ مثيلاً جديداً من الفئة {@code BarcodeField}.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ينشئ مثيلاً جديداً من الفئة {@code BarcodeField}.

### getCaption {#getCaption--}
```
public String getCaption()
```

يحصل على تسمية كائن الباركود.

**Returns:**
قيمة سلسلة

### getECC {#getECC--}
```
public int getECC()
```

يحصل على قيمة عددية تمثل معامل تصحيح الخطأ. بالنسبة لـ PDF417، يجب أن تكون من 0 إلى 8. بالنسبة لـ QRCode، يجب أن تكون من 0 إلى 3 (0 لـ 'L'، 1 لـ 'M'، 2 لـ 'Q'، و3 لـ 'H').

**Returns:**
قيمة int

### getResolution {#getResolution--}
```
public int getResolution()
```

يحصل على الدقة، بوحدة النقاط لكل بوصة (dpi)، التي يُعرض بها كائن الباركود.

**Returns:**
قيمة int

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

يحدد أي تقنية باركود أو رموز تُستخدم في هذه التعليقة، راجع {@code Symbology} للتفاصيل.

**Returns:**
عنصر Symbology @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

يحصل على المسافة العمودية بين وحدتي باركود، مقاسة بالبكسل. يجب أن تكون نسبة XSymHeight/XSymWidth قيمة عددية صحيحة. بالنسبة لـ PDF417، نطاق النسبة المقبول هو من 1 إلى 4. بالنسبة لـ QRCode و DataMatrix، يجب أن تكون هذه النسبة دائماً 1.

**Returns:**
قيمة int

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

يحصل على المسافة الأفقية، بالبكسل، بين وحدتي باركود.

**Returns:**
قيمة int
