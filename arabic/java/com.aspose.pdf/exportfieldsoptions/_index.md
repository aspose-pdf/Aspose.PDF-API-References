---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الفئة الأساسية للخيارات الخاصة بتصدير حقول النموذج."
type: docs
weight: 1310
url: /ar/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

يمثل الفئة الأساسية للخيارات الخاصة بتصدير حقول النموذج.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تصدير قيمة كلمة المرور. القيمة: {@code true} إذا كان يجب تصدير قيمة كلمة المرور؛ وإلا {@code false}. |
| [getFieldSelector](#getFieldSelector--) | يحصل على مندوب يحدد ما إذا كان يجب تصدير حقل معين. إذا كان المندوب {@code null}، يتم تصدير جميع الحقول (السلوك الافتراضي). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تصدير قيمة كلمة المرور. القيمة: {@code true} إذا كان يجب تصدير قيمة كلمة المرور؛ وإلا {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | يضبط مندوبًا يحدد ما إذا كان يجب تصدير حقل معين. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تصدير قيمة كلمة المرور. القيمة: {@code true} إذا كان يجب تصدير قيمة كلمة المرور؛ وإلا {@code false}.

**Returns:**
قيمة منطقية

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

يحصل على مندوب يحدد ما إذا كان يجب تصدير حقل معين. إذا كان المندوب {@code null}، يتم تصدير جميع الحقول (السلوك الافتراضي).

**Returns:**
مندوب يحدد ما إذا كان يجب تصدير حقل معين.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تصدير قيمة كلمة المرور. القيمة: {@code true} إذا كان يجب تصدير قيمة كلمة المرور؛ وإلا {@code false}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
يضبط مندوبًا يحدد ما إذا كان يجب تصدير حقل معين.
