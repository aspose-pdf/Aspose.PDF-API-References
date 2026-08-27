---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل حقل زر الاختيار."
type: docs
weight: 4080
url: /ar/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

فئة تمثل حقل زر الاختيار.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | منشئ لفئة RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | منشئ لفئة RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | يضبط حقل زر الراديو. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | يضيف حقل خيار جديد إلى حقل RadioButton. |
| [addOption](#addOption-java.lang.String-) | أضف خيارًا إلى زر الراديو. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | أضف إلى خيار زر الراديو باستخدام مستطيل محدد. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> يحصل أو يضبط العلامة التي تسمح لزر الراديو بعدم وجود قيمة مختارة. إذا كان {@code }، يجب أن يكون زر راديو واحد محددًا في جميع الأوقات؛ اختيار الزر المحدد حاليًا لا يؤثر. إذا كان {@code }، فإن النقر على الزر المحدد يلغي تحديده، تاركًا لا زر محدد. </p> <hr> قد يتجاهل بعض قارئات PDF (بما في ذلك Adobe Acrobat) حالة العلامة. |
| [getOptions](#getOptions--) | يحصل على مجموعة الخيارات لزر الراديو. |
| [getPageIndex](#getPageIndex--) | يحصل على فهرس الصفحة التي تحتوي على حقل RadioButton هذا. |
| [getSelected](#getSelected--) | يحصل على فهرس العنصر المحدد. يبدأ ترقيم العناصر من 1. |
| [getStyle](#getStyle--) | نمط صندوق الحقل. |
| [getValue](#getValue--) | يحصل على قيمة الحقل. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> يحصل أو يضبط العلامة التي تسمح لزر الراديو بعدم وجود قيمة مختارة. إذا كان {@code }، يجب أن يكون زر راديو واحد محددًا في جميع الأوقات؛ اختيار الزر المحدد حاليًا لا يؤثر. إذا كان {@code }، فإن النقر على الزر المحدد يلغي تحديده، تاركًا لا زر محدد. </p> <hr> قد يتجاهل بعض قارئات PDF (بما في ذلك Adobe Acrobat) حالة العلامة. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | نقل جميع العناصر الفرعية لزر الراديو إلى المواقع المحددة على الصفحة. |
| [setSelected](#setSelected-int-) | يضبط فهرس العنصر المحدد. يبدأ ترقيم العناصر من 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | نمط صندوق الحقل. |
| [setValue](#setValue-java.lang.String-) | يضبط قيمة الحقل. |
| [updateAppearances](#updateAppearances--) | تحديث قيمة المظهر. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
منشئ لفئة RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
منشئ لفئة RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
يضبط حقل زر الراديو.

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
يضيف حقل خيار جديد إلى حقل RadioButton.

### addOption {#addOption-java.lang.String-}
أضف خيارًا إلى زر الراديو.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
أضف إلى خيار زر الراديو باستخدام مستطيل محدد.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> يحصل أو يضبط العلامة التي تسمح لزر الراديو بعدم وجود قيمة مختارة. إذا كان {@code }، يجب أن يكون زر راديو واحد محددًا في جميع الأوقات؛ اختيار الزر المحدد حاليًا لا يؤثر. إذا كان {@code }، فإن النقر على الزر المحدد يلغي تحديده، تاركًا لا زر محدد. </p> <hr> قد يتجاهل بعض قارئات PDF (بما في ذلك Adobe Acrobat) حالة العلامة.

**Returns:**
قيمة منطقية

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

يحصل على مجموعة الخيارات لزر الراديو.

**Returns:**
كائن OptionCollection

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

يحصل على فهرس الصفحة التي تحتوي على حقل RadioButton هذا.

**Returns:**
قيمة int

### getSelected {#getSelected--}
```
public int getSelected()
```

يحصل على فهرس العنصر المحدد. يبدأ ترقيم العناصر من 1.

**Returns:**
قيمة int

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

نمط صندوق الحقل.

**Returns:**
قيمة BoxStyle @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

يحصل على قيمة الحقل.

**Returns:**
قيمة سلسلة

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> يحصل أو يضبط العلامة التي تسمح لزر الراديو بعدم وجود قيمة مختارة. إذا كان {@code }، يجب أن يكون زر راديو واحد محددًا في جميع الأوقات؛ اختيار الزر المحدد حاليًا لا يؤثر. إذا كان {@code }، فإن النقر على الزر المحدد يلغي تحديده، تاركًا لا زر محدد. </p> <hr> قد يتجاهل بعض قارئات PDF (بما في ذلك Adobe Acrobat) حالة العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setPosition {#setPosition-com.aspose.pdf.Point-}
نقل جميع العناصر الفرعية لزر الراديو إلى المواقع المحددة على الصفحة.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

يضبط فهرس العنصر المحدد. يبدأ ترقيم العناصر من 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
نمط صندوق الحقل.

### setValue {#setValue-java.lang.String-}
يضبط قيمة الحقل.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

تحديث قيمة المظهر.
