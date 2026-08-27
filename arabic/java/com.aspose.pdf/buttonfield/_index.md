---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تمثل حقل زر الضغط."
type: docs
weight: 440
url: /ar/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

الفئة تمثل حقل زر الضغط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ButtonField](#ButtonField--) | منشئ حقل الزر للمولد. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | منشئ حقل الزر للمولد. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | منشئ حقل الزر للمولد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | يضيف صورة إلى موارد الحقل ويرسمها. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | يضيف صورة إلى موارد الحقل ويرسمها. |
| [getAlternateCaption](#getAlternateCaption--) | يحصل على التسمية البديلة للزر التي يجب عرضها عندما يتم ضغط زر الفأرة داخل المنطقة النشطة. |
| [getAlternateIcon](#getAlternateIcon--) | يحصل على الأيقونة البديلة التي يجب عرضها عندما يتم ضغط زر الفأرة داخل المنطقة النشطة. |
| [getIconFit](#getIconFit--) | يحصل على كائن ملاءمة الأيقونة الذي يحدد كيفية عرض أيقونة التعليق التوضيحي داخل مستطيل التعليق التوضيحي. |
| [getICPosition](#getICPosition--) | يحصل على موضع تسمية الأيقونة. |
| [getNormalCaption](#getNormalCaption--) | يحصل على التسمية العادية. |
| [getNormalIcon](#getNormalIcon--) | يحصل على الأيقونة العادية للزر التي يجب عرضها عندما لا يكون هناك تفاعل مع المستخدم. |
| [getRolloverCaption](#getRolloverCaption--) | يحصل على التسمية المتغيرة للزر التي يجب عرضها عندما يمر المؤشر فوق المنطقة النشطة دون ضغط زر الفأرة. |
| [getRolloverIcon](#getRolloverIcon--) | يحصل على الأيقونة المتغيرة للزر التي يجب عرضها عندما يمر المؤشر فوق المنطقة النشطة دون ضغط زر الفأرة. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | يضبط التسمية البديلة للزر التي يجب عرضها عندما يتم ضغط زر الفأرة داخل المنطقة النشطة. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | يضبط الأيقونة البديلة التي يجب عرضها عندما يتم ضغط زر الفأرة داخل المنطقة النشطة. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | يضبط موضع تسمية الأيقونة. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | يضبط التسمية العادية. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | يضبط الأيقونة العادية للزر التي يجب عرضها عندما لا يكون هناك تفاعل مع المستخدم. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | يضبط التسمية المتغيرة للزر التي يجب عرضها عندما يمر المؤشر فوق المنطقة النشطة دون ضغط زر الفأرة. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | يضبط أيقونة التمرير للزر التي سيتم عرضها عندما يمر المستخدم بالمؤشر إلى المنطقة النشطة دون الضغط على زر الفأرة. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

منشئ حقل الزر للمولد.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
منشئ حقل الزر للمولد.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
منشئ حقل الزر للمولد.

### addImage {#addImage-java.awt.image.BufferedImage-}
يضيف صورة إلى موارد الحقل ويرسمها.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
يضيف صورة إلى موارد الحقل ويرسمها.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

يحصل على التسمية البديلة للزر التي يجب عرضها عندما يتم ضغط زر الفأرة داخل المنطقة النشطة.

**Returns:**
قيمة سلسلة

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

يحصل على الأيقونة البديلة التي يجب عرضها عندما يتم ضغط زر الفأرة داخل المنطقة النشطة.

**Returns:**
كائن XForm

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

يحصل على كائن ملاءمة الأيقونة الذي يحدد كيفية عرض أيقونة التعليق التوضيحي داخل مستطيل التعليق التوضيحي.

**Returns:**
كائن IconFit

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

يحصل على موضع تسمية الأيقونة.

**Returns:**
موضع تسمية الأيقونة. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

يحصل على التسمية العادية.

**Returns:**
قيمة سلسلة

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

يحصل على الأيقونة العادية للزر التي يجب عرضها عندما لا يكون هناك تفاعل مع المستخدم.

**Returns:**
كائن XForm

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

يحصل على التسمية المتغيرة للزر التي يجب عرضها عندما يمر المؤشر فوق المنطقة النشطة دون ضغط زر الفأرة.

**Returns:**
قيمة سلسلة

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

يحصل على الأيقونة المتغيرة للزر التي يجب عرضها عندما يمر المؤشر فوق المنطقة النشطة دون ضغط زر الفأرة.

**Returns:**
كائن XForm

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
يضبط التسمية البديلة للزر التي يجب عرضها عندما يتم ضغط زر الفأرة داخل المنطقة النشطة.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
يضبط الأيقونة البديلة التي يجب عرضها عندما يتم ضغط زر الفأرة داخل المنطقة النشطة.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
يضبط موضع تسمية الأيقونة.

### setNormalCaption {#setNormalCaption-java.lang.String-}
يضبط التسمية العادية.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
يضبط الأيقونة العادية للزر التي يجب عرضها عندما لا يكون هناك تفاعل مع المستخدم.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
يضبط التسمية المتغيرة للزر التي يجب عرضها عندما يمر المؤشر فوق المنطقة النشطة دون ضغط زر الفأرة.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
يضبط أيقونة التمرير للزر التي سيتم عرضها عندما يمر المستخدم بالمؤشر إلى المنطقة النشطة دون الضغط على زر الفأرة.
