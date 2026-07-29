---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة التي تمثل حقل خانة الاختيار."
type: docs
weight: 580
url: /ar/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

الفئة التي تمثل حقل خانة الاختيار.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CheckboxField](#CheckboxField--) | إنشاء نسخة من CheckboxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | إنشاء نسخة من CheckboxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | إنشاء نسخة من CheckboxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | إنشاء نسخة من CheckboxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم CheckboxField(Document doc) |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة كحد أقصى في أي وقت. يتم إضافة خانة الاختيار الجديدة إلى أسفل المجموعة. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة كحد أقصى في أي وقت. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة كحد أقصى في أي وقت. |
| [deepClone](#deepClone--) | استنساخ خانة الاختيار. |
| [getActiveState](#getActiveState--) | يحصل على حالة مظهر التعليق التوضيحي الحالية. |
| [getAllowedStates](#getAllowedStates--) | يعيد قائمة بالحالات المسموح بها. |
| [getChecked](#getChecked--) | يحصل على حالة مربع الاختيار. |
| [getExportValue](#getExportValue--) | يحصل أو يضبط قيمة التصدير لحقل CheckBox. |
| [getNormalCaption](#getNormalCaption--) | يحصل على التسمية العادية للحقل. |
| [getOnState](#getOnState--) | يعيد اسم الحالة التي هي الحالة "Checked" لمربع الاختيار. تكون "Yes" إذا كانت موجودة أو أي قيمة أخرى غير "Off" و "No"; |
| [getStyle](#getStyle--) | يحصل على نمط مربع الاختيار. |
| [getValue](#getValue--) | يحصل على قيمة حقل مربع الاختيار. |
| [setActiveState](#setActiveState-java.lang.String-) | يضبط حالة مظهر التعليق الحالي. |
| [setChecked](#setChecked-boolean-) | يضبط حالة مربع الاختيار. |
| [setExportValue](#setExportValue-java.lang.String-) | يحصل أو يضبط قيمة التصدير لحقل CheckBox. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | يضبط نمط مربع الاختيار. |
| [setValue](#setValue-java.lang.String-) | يضبط قيمة حقل مربع الاختيار. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

إنشاء نسخة من CheckboxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
إنشاء نسخة من CheckboxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
إنشاء نسخة من CheckboxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
إنشاء نسخة من CheckboxField. @deprecated للحصول على وظائف الحقل الكاملة، يلزم ربط بالمستند - استخدم CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة كحد أقصى في أي وقت. يتم إضافة خانة الاختيار الجديدة إلى أسفل المجموعة.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة كحد أقصى في أي وقت.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة كحد أقصى في أي وقت.

### deepClone {#deepClone--}
```
public Object deepClone()
```

استنساخ خانة الاختيار.

**Returns:**
الكائن المستنسخ

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

يحصل على حالة مظهر التعليق التوضيحي الحالية.

**Returns:**
قيمة سلسلة

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

يعيد قائمة بالحالات المسموح بها.

**Returns:**
قائمة بقيم String

### getChecked {#getChecked--}
```
public boolean getChecked()
```

يحصل على حالة مربع الاختيار.

**Returns:**
قيمة منطقية

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

يحصل أو يضبط قيمة التصدير لحقل CheckBox.

**Returns:**
قيمة سلسلة

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

يحصل على التسمية العادية للحقل.

**Returns:**
قيمة سلسلة

### getOnState {#getOnState--}
```
public String getOnState()
```

يعيد اسم الحالة التي هي الحالة "Checked" لمربع الاختيار. تكون "Yes" إذا كانت موجودة أو أي قيمة أخرى غير "Off" و "No";

**Returns:**
قيمة سلسلة

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

يحصل على نمط مربع الاختيار.

**Returns:**
نمط مربع الاختيار. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

يحصل على قيمة حقل مربع الاختيار.

**Returns:**
قيمة سلسلة

### setActiveState {#setActiveState-java.lang.String-}
يضبط حالة مظهر التعليق الحالي.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

يضبط حالة مربع الاختيار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setExportValue {#setExportValue-java.lang.String-}
يحصل أو يضبط قيمة التصدير لحقل CheckBox.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
يضبط نمط مربع الاختيار.

### setValue {#setValue-java.lang.String-}
يضبط قيمة حقل مربع الاختيار.
