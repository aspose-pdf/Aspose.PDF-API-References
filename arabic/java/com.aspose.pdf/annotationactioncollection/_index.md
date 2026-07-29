---
title: "AnnotationActionCollection"
linktitle: "AnnotationActionCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل مجموعة إجراءات التعليق التوضيحي."
type: docs
weight: 70
url: /ar/java/com.aspose.pdf/annotationactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseActionCollection com.aspose.pdf.AnnotationActionCollection, com.aspose.pdf.BaseActionCollection, com.aspose.pdf.AnnotationActionCollection

```
public final class AnnotationActionCollection extends BaseActionCollection
```

يمثل مجموعة إجراءات التعليق التوضيحي.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOnCalculate](#getOnCalculate--) | يحصل على إجراء لحساب قيمة الحقل. |
| [getOnClosePage](#getOnClosePage--) | يحصل على إجراء يتم تنفيذه عندما يتم إغلاق الصفحة التي تحتوي على التعليق. |
| [getOnEnter](#getOnEnter--) | يحصل على إجراء يتم تنفيذه عندما يدخل المؤشر إلى المنطقة النشطة للتعليق. |
| [getOnExit](#getOnExit--) | يحصل على إجراء يتم تنفيذه عندما يخرج المؤشر من المنطقة النشطة للتعليق. |
| [getOnFormat](#getOnFormat--) | يحصل على إجراء يتم تنفيذه لتنسيق قيمة الحقل. |
| [getOnHidePage](#getOnHidePage--) | يحصل على إجراء يتم تنفيذه عندما لا تكون الصفحة التي تحتوي على التعليق مرئية بعد الآن في واجهة مستخدم تطبيق العارض. |
| [getOnLostFocus](#getOnLostFocus--) | يحصل على إجراء يتم تنفيذه عندما يفقد التعليق تركيز الإدخال. |
| [getOnModifyCharacter](#getOnModifyCharacter--) | يحصل على إجراء يتم تنفيذه عندما يقوم المستخدم بتعديل حرف في الحقل. |
| [getOnOpenPage](#getOnOpenPage--) | يحصل على إجراء يتم تنفيذه عندما تُفتح الصفحة التي تحتوي على التعليق. |
| [getOnPressMouseBtn](#getOnPressMouseBtn--) | يحصل على إجراء يتم تنفيذه عندما يُضغط زر الفأرة داخل المنطقة النشطة للتعليق. |
| [getOnReceiveFocus](#getOnReceiveFocus--) | يحصل على إجراء يتم تنفيذه عندما يتلقى التعليق تركيز الإدخال. |
| [getOnReleaseMouseBtn](#getOnReleaseMouseBtn--) | يحصل على إجراء يتم تنفيذه عندما يُفرج عن زر الفأرة داخل المنطقة النشطة للتعليق. |
| [getOnShowPage](#getOnShowPage--) | احصل على إجراء يتم تنفيذه عندما تصبح الصفحة التي تحتوي على التعليق مرئية في واجهة مستخدم تطبيق العارض. |
| [getOnValidate](#getOnValidate--) | يحصل على إجراء يتم تنفيذه عندما يغيّر المستخدم محتويات الحقل. |
| [setOnCalculate](#setOnCalculate-com.aspose.pdf.PdfAction-) | يضبط إجراءً لحساب قيمة الحقل. |
| [setOnClosePage](#setOnClosePage-com.aspose.pdf.PdfAction-) | يضبط إجراءً يتم تنفيذه عندما تُغلق الصفحة التي تحتوي على التعليق. |
| [setOnEnter](#setOnEnter-com.aspose.pdf.PdfAction-) | يضبط إجراءً يتم تنفيذه عندما يدخل المؤشر إلى المنطقة النشطة للتعليق. |
| [setOnExit](#setOnExit-com.aspose.pdf.PdfAction-) | يضبط إجراءً يتم تنفيذه عندما يخرج المؤشر من المنطقة النشطة للتعليق. |
| [setOnFormat](#setOnFormat-com.aspose.pdf.PdfAction-) | يضبط إجراءً يتم تنفيذه لتنسيق قيمة الحقل. |
| [setOnHidePage](#setOnHidePage-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما تصبح الصفحة التي تحتوي على التعليق التوضيحي غير مرئية في واجهة مستخدم تطبيق العارض. |
| [setOnLostFocus](#setOnLostFocus-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما يفقد التعليق التوضيحي تركيز الإدخال. |
| [setOnModifyCharacter](#setOnModifyCharacter-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما يقوم المستخدم بتعديل حرف في الحقل. |
| [setOnOpenPage](#setOnOpenPage-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما تُفتح الصفحة التي تحتوي على التعليق التوضيحي. |
| [setOnPressMouseBtn](#setOnPressMouseBtn-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما يُضغط زر الفأرة داخل المنطقة النشطة للتعليق التوضيحي. |
| [setOnReceiveFocus](#setOnReceiveFocus-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما يتلقى التعليق التوضيحي تركيز الإدخال. |
| [setOnReleaseMouseBtn](#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما يُفرج عن زر الفأرة داخل المنطقة النشطة للتعليق التوضيحي. |
| [setOnShowPage](#setOnShowPage-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما تصبح الصفحة التي تحتوي على التعليق التوضيحي مرئية في واجهة مستخدم تطبيق العارض. |
| [setOnValidate](#setOnValidate-com.aspose.pdf.PdfAction-) | يحدد إجراءً يتم تنفيذه عندما يغيّر المستخدم محتويات الحقل. |

### getOnCalculate {#getOnCalculate--}
```
public PdfAction getOnCalculate()
```

يحصل على إجراء لحساب قيمة الحقل.

**Returns:**
إجراء لحساب قيمة الحقل.

### getOnClosePage {#getOnClosePage--}
```
public PdfAction getOnClosePage()
```

يحصل على إجراء يتم تنفيذه عندما يتم إغلاق الصفحة التي تحتوي على التعليق.

**Returns:**
كائن PdfAction

### getOnEnter {#getOnEnter--}
```
public PdfAction getOnEnter()
```

يحصل على إجراء يتم تنفيذه عندما يدخل المؤشر إلى المنطقة النشطة للتعليق.

**Returns:**
كائن PdfAction

### getOnExit {#getOnExit--}
```
public PdfAction getOnExit()
```

يحصل على إجراء يتم تنفيذه عندما يخرج المؤشر من المنطقة النشطة للتعليق.

**Returns:**
كائن PdfAction

### getOnFormat {#getOnFormat--}
```
public PdfAction getOnFormat()
```

يحصل على إجراء يتم تنفيذه لتنسيق قيمة الحقل.

**Returns:**
إجراء يتم تنفيذه لتنسيق قيمة الحقل.

### getOnHidePage {#getOnHidePage--}
```
public PdfAction getOnHidePage()
```

يحصل على إجراء يتم تنفيذه عندما لا تكون الصفحة التي تحتوي على التعليق مرئية بعد الآن في واجهة مستخدم تطبيق العارض.

**Returns:**
كائن PdfAction

### getOnLostFocus {#getOnLostFocus--}
```
public PdfAction getOnLostFocus()
```

يحصل على إجراء يتم تنفيذه عندما يفقد التعليق تركيز الإدخال.

**Returns:**
كائن PdfAction

### getOnModifyCharacter {#getOnModifyCharacter--}
```
public PdfAction getOnModifyCharacter()
```

يحصل على إجراء يتم تنفيذه عندما يقوم المستخدم بتعديل حرف في الحقل.

**Returns:**
إجراء يتم تنفيذه عندما يقوم المستخدم بتعديل حرف في الحقل.

### getOnOpenPage {#getOnOpenPage--}
```
public PdfAction getOnOpenPage()
```

يحصل على إجراء يتم تنفيذه عندما تُفتح الصفحة التي تحتوي على التعليق.

**Returns:**
كائن PdfAction

### getOnPressMouseBtn {#getOnPressMouseBtn--}
```
public PdfAction getOnPressMouseBtn()
```

يحصل على إجراء يتم تنفيذه عندما يُضغط زر الفأرة داخل المنطقة النشطة للتعليق.

**Returns:**
كائن PdfAction

### getOnReceiveFocus {#getOnReceiveFocus--}
```
public PdfAction getOnReceiveFocus()
```

يحصل على إجراء يتم تنفيذه عندما يتلقى التعليق تركيز الإدخال.

**Returns:**
كائن PdfAction

### getOnReleaseMouseBtn {#getOnReleaseMouseBtn--}
```
public PdfAction getOnReleaseMouseBtn()
```

يحصل على إجراء يتم تنفيذه عندما يُفرج عن زر الفأرة داخل المنطقة النشطة للتعليق.

**Returns:**
كائن PdfAction

### getOnShowPage {#getOnShowPage--}
```
public PdfAction getOnShowPage()
```

احصل على إجراء يتم تنفيذه عندما تصبح الصفحة التي تحتوي على التعليق مرئية في واجهة مستخدم تطبيق العارض.

**Returns:**
كائن PdfAction

### getOnValidate {#getOnValidate--}
```
public PdfAction getOnValidate()
```

يحصل على إجراء يتم تنفيذه عندما يغيّر المستخدم محتويات الحقل.

**Returns:**
إجراء يتم تنفيذه عندما يغيّر المستخدم محتويات الحقل.

### setOnCalculate {#setOnCalculate-com.aspose.pdf.PdfAction-}
يضبط إجراءً لحساب قيمة الحقل.

### setOnClosePage {#setOnClosePage-com.aspose.pdf.PdfAction-}
يضبط إجراءً يتم تنفيذه عندما تُغلق الصفحة التي تحتوي على التعليق.

### setOnEnter {#setOnEnter-com.aspose.pdf.PdfAction-}
يضبط إجراءً يتم تنفيذه عندما يدخل المؤشر إلى المنطقة النشطة للتعليق.

### setOnExit {#setOnExit-com.aspose.pdf.PdfAction-}
يضبط إجراءً يتم تنفيذه عندما يخرج المؤشر من المنطقة النشطة للتعليق.

### setOnFormat {#setOnFormat-com.aspose.pdf.PdfAction-}
يضبط إجراءً يتم تنفيذه لتنسيق قيمة الحقل.

### setOnHidePage {#setOnHidePage-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما تصبح الصفحة التي تحتوي على التعليق التوضيحي غير مرئية في واجهة مستخدم تطبيق العارض.

### setOnLostFocus {#setOnLostFocus-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما يفقد التعليق التوضيحي تركيز الإدخال.

### setOnModifyCharacter {#setOnModifyCharacter-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما يقوم المستخدم بتعديل حرف في الحقل.

### setOnOpenPage {#setOnOpenPage-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما تُفتح الصفحة التي تحتوي على التعليق التوضيحي.

### setOnPressMouseBtn {#setOnPressMouseBtn-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما يُضغط زر الفأرة داخل المنطقة النشطة للتعليق التوضيحي.

### setOnReceiveFocus {#setOnReceiveFocus-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما يتلقى التعليق التوضيحي تركيز الإدخال.

### setOnReleaseMouseBtn {#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما يُفرج عن زر الفأرة داخل المنطقة النشطة للتعليق التوضيحي.

### setOnShowPage {#setOnShowPage-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما تصبح الصفحة التي تحتوي على التعليق التوضيحي مرئية في واجهة مستخدم تطبيق العارض.

### setOnValidate {#setOnValidate-com.aspose.pdf.PdfAction-}
يحدد إجراءً يتم تنفيذه عندما يغيّر المستخدم محتويات الحقل.
