---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الفئة الأساسية لحقول الاختيار."
type: docs
weight: 590
url: /ar/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

يمثل الفئة الأساسية لحقول الاختيار.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | ينشئ حقل اختيار (لـ Generator) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | منشئ لـ ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | منشئ لـ ChoiceField. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | يضيف خيارًا جديدًا بالاسم المحدد. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | يضيف خيارًا جديدًا بقيمة التصدير والاسم المحدد. |
| [deleteOption](#deleteOption-java.lang.String-) | يحذف الخيار حسب اسمه. |
| [getCommitImmediately](#getCommitImmediately--) | يحصل على علم الالتزام عند تغيير الاختيار. |
| [getMultiSelect](#getMultiSelect--) | يحصل على علم التحديد المتعدد. |
| [getOptions](#getOptions--) | يحصل على مجموعة خيارات الاختيار. |
| [getSelected](#getSelected--) | يحصل على فهرس الخيار المحدد. هذه الخاصية تسمح بتغيير الاختيار. |
| [getSelectedItems](#getSelectedItems--) | يضبط مصفوفة العناصر المحددة. بالنسبة لقائمة التحديد المتعدد، تحتوي المصفوفة على أكثر من عنصر واحد. بالنسبة لقائمة التحديد الفردي، تحتوي على عنصر واحد. |
| [getValue](#getValue--) | يحصل على قيمة الحقل. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | يضبط علم الالتزام عند تغيير الاختيار. |
| [setMultiSelect](#setMultiSelect-boolean-) | يضبط علم التحديد المتعدد. |
| [setOptions](#setOptions-java.util.List-) | يستبدل الخيارات المتاحة بتلك التي تُعطى أسماؤها في معامل الخيارات. |
| [setSelected](#setSelected-int-) | يضبط فهرس الخيار المحدد. هذه الخاصية تسمح بتغيير الاختيار. |
| [setSelectedItems](#setSelectedItems-int:A-) | يضبط مصفوفة العناصر المحددة. بالنسبة لقائمة التحديد المتعدد، تحتوي المصفوفة على أكثر من عنصر واحد. بالنسبة لقائمة التحديد الفردي، تحتوي على عنصر واحد. |
| [setValue](#setValue-java.lang.String-) | يضبط قيمة الحقل. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
ينشئ حقل اختيار (لـ Generator)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
منشئ لـ ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
منشئ لـ ChoiceField.

### addOption {#addOption-java.lang.String-}
يضيف خيارًا جديدًا بالاسم المحدد.

### addOption {#addOption-java.lang.String-java.lang.String-}
يضيف خيارًا جديدًا بقيمة التصدير والاسم المحدد.

### deleteOption {#deleteOption-java.lang.String-}
يحذف الخيار حسب اسمه.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

يحصل على علم الالتزام عند تغيير الاختيار.

**Returns:**
قيمة منطقية

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

يحصل على علم التحديد المتعدد.

**Returns:**
قيمة منطقية

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

يحصل على مجموعة خيارات الاختيار.

**Returns:**
كائن OptionCollection

### getSelected {#getSelected--}
```
public int getSelected()
```

يحصل على فهرس الخيار المحدد. هذه الخاصية تسمح بتغيير الاختيار.

**Returns:**
قيمة int

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

يضبط مصفوفة العناصر المحددة. بالنسبة لقائمة التحديد المتعدد، تحتوي المصفوفة على أكثر من عنصر واحد. بالنسبة لقائمة التحديد الفردي، تحتوي على عنصر واحد.

**Returns:**
مصفوفة من قيم int

### getValue {#getValue--}
```
public String getValue()
```

يحصل على قيمة الحقل.

**Returns:**
قيمة سلسلة

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

يضبط علم الالتزام عند تغيير الاختيار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

يضبط علم التحديد المتعدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOptions {#setOptions-java.util.List-}
يستبدل الخيارات المتاحة بتلك التي تُعطى أسماؤها في معامل الخيارات.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

يضبط فهرس الخيار المحدد. هذه الخاصية تسمح بتغيير الاختيار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

يضبط مصفوفة العناصر المحددة. بالنسبة لقائمة التحديد المتعدد، تحتوي المصفوفة على أكثر من عنصر واحد. بالنسبة لقائمة التحديد الفردي، تحتوي على عنصر واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة من قيم int |

### setValue {#setValue-java.lang.String-}
يضبط قيمة الحقل.
