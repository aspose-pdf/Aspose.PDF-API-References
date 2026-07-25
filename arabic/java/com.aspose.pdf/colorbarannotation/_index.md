---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل تعليقة ColorBarAnnotation. الخاصية Color يتم تجاهلها، وبدلاً من ذلك يتم استخدام لون ColorsOfCMYK. عند الإنشاء، نسبة العرض إلى الارتفاع تحدد الاتجاه."
type: docs
weight: 680
url: /ar/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

فئة تمثل تعليقة ColorBarAnnotation. يتم تجاهل الخاصية Color، ويتم استخدام لون ColorsOfCMYK بدلاً منها. عند الإنشاء، يحدد نسبة العرض إلى الارتفاع اتجاه التعليقة - أفقي أو عمودي. بعد ذلك، يتم التحقق من أن مستطيل التعليقة خارج TrimBox، وإذا لم يكن كذلك، يتم إزاحته إلى أقرب موقع خارج TrimBox مع مراعاة اتجاه التعليقة. يمكن تقليل العرض (الارتفاع) بحيث تتناسب التعليقة خارج TrimBox. إذا لم يتوفر مساحة للتخطيط، يمكن ضبط العرض/الارتفاع على الصفر (في هذه الحالة، تكون التعليقة موجودة على الصفحة ولكنها غير معروضة).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ينشئ تعليقة ColorBar جديدة على الصفحة المحددة. الافتراضي ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | ينشئ تعليقة ColorBar جديدة على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة والتحرك خارج TrimBox إذا لزم الأمر. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getColorOfCMYK](#getColorOfCMYK--) | يحصل أو يضبط اللون (واحد من cyan, magenta, yellow, black) الذي تُرسم به التعليقة. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | يحصل أو يضبط اللون (واحد من cyan, magenta, yellow, black) الذي تُرسم به التعليقة. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ينشئ تعليقة ColorBar جديدة على الصفحة المحددة. الافتراضي ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
ينشئ تعليقة ColorBar جديدة على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة والتحرك خارج TrimBox إذا لزم الأمر.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
قيمة int

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

يحصل أو يضبط اللون (واحد من cyan, magenta, yellow, black) الذي تُرسم به التعليقة.

**Returns:**
عنصر ColorsOfCMYK

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
يحصل أو يضبط اللون (واحد من cyan, magenta, yellow, black) الذي تُرسم به التعليقة.
