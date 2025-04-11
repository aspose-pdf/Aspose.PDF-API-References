---
title: Class DjvuLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.DjvuLoadOptions. تصف الفئة خيارات تحميل DJVU
type: docs
weight: 3740
url: /ar/net/aspose.pdf/djvuloadoptions/
---
## فئة DjvuLoadOptions

تصف الفئة خيارات تحميل DJVU.

```csharp
public class DjvuLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DjvuLoadOptions](djvuloadoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون القيمة `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يعيد WarningHandler عنصر تعداد ReturnAction الذي يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

### انظر أيضًا

* فئة [LoadOptions](../loadoptions/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)