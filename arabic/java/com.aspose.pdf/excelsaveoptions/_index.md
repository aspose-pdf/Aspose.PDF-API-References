---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات الحفظ للتصدير إلى تنسيق Excel"
type: docs
weight: 1260
url: /ar/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

خيارات الحفظ للتصدير إلى تنسيق Excel

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat](#getFormat--) | / * / * يحصل أو يضبط العامل الذي سيُطبق على حجم الخط (الافتراضي) أثناء التحويل إلى جدول Excel في / * محرك legacy. ضبط قيمة أقل يسهل البحث عن الأعمدة ويمنع دمجها لبعض / * المستندات. القيمة الافتراضية هي 0.9؛ ضبط القيمة إلى صفر يسمح للخوارزمية باختيار التحجيم تلقائيًا. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | عيّن true إذا كنت بحاجة إلى تقليل عدد أوراق العمل في المصنف الناتج. القيمة الافتراضية هي false؛ يعني حفظ كل صفحة PDF كورقة عمل منفصلة. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | عيّن false إذا كنت بحاجة إلى منع إدراج عمود فارغ كأول عمود في ورقة العمل. القيمة الافتراضية هي true؛ وهذا يعني أنه سيتم إدراج العمود الفارغ. |
| [isUniformWorksheets](#isUniformWorksheets--) | عيّن true لاستخدام تقسيم الأعمدة المتساوية عبر المستند. القيمة الافتراضية هي false؛ وهذا يعني أن تقسيم الأعمدة سيكون مستقلاً لكل صفحة. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | تنسيق الإخراج |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | عيّن false إذا كنت بحاجة إلى منع إدراج عمود فارغ كأول عمود في ورقة العمل. القيمة الافتراضية هي true؛ وهذا يعني أنه سيتم إدراج العمود الفارغ. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | عيّن true إذا كنت بحاجة إلى تقليل عدد أوراق العمل في المصنف الناتج. القيمة الافتراضية هي false؛ يعني حفظ كل صفحة PDF كورقة عمل منفصلة. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | يحدد محرك التحويل الذي سيُستخدم في التحويل |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

منشئ

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * يحصل أو يضبط العامل الذي سيُطبق على حجم الخط (الافتراضي) أثناء التحويل إلى جدول Excel في / * محرك legacy. ضبط قيمة أقل يسهل البحث عن الأعمدة ويمنع دمجها لبعض / * المستندات. القيمة الافتراضية هي 0.9؛ ضبط القيمة إلى صفر يسمح للخوارزمية باختيار التحجيم تلقائيًا. / * / * / *

**Returns:**
قيمة مزدوجة /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

عيّن true إذا كنت بحاجة إلى تقليل عدد أوراق العمل في المصنف الناتج. القيمة الافتراضية هي false؛ يعني حفظ كل صفحة PDF كورقة عمل منفصلة.

**Returns:**
قيمة منطقية

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

عيّن false إذا كنت بحاجة إلى منع إدراج عمود فارغ كأول عمود في ورقة العمل. القيمة الافتراضية هي true؛ وهذا يعني أنه سيتم إدراج العمود الفارغ.

**Returns:**
قيمة منطقية

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

عيّن true لاستخدام تقسيم الأعمدة المتساوية عبر المستند. القيمة الافتراضية هي false؛ وهذا يعني أن تقسيم الأعمدة سيكون مستقلاً لكل صفحة.

**Returns:**
قيمة منطقية

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
تنسيق الإخراج

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

عيّن false إذا كنت بحاجة إلى منع إدراج عمود فارغ كأول عمود في ورقة العمل. القيمة الافتراضية هي true؛ وهذا يعني أنه سيتم إدراج العمود الفارغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

عيّن true إذا كنت بحاجة إلى تقليل عدد أوراق العمل في المصنف الناتج. القيمة الافتراضية هي false؛ يعني حفظ كل صفحة PDF كورقة عمل منفصلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

يحدد محرك التحويل الذي سيُستخدم في التحويل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |
