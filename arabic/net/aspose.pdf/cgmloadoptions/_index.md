---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.CgmLoadOptions. تحتوي على خيارات لتحميل/استيراد ملف CGM إلى مستند PDF
type: docs
weight: 3010
url: /ar/net/aspose.pdf/cgmloadoptions/
---
## فئة CgmLoadOptions

تحتوي على خيارات لتحميل/استيراد ملف CGM إلى مستند PDF.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | ينشئ خيارات تحميل افتراضية لتحويل ملف CGM إلى مستند PDF. حجم صفحة PDF الافتراضي - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | ينشئ خيارات تحميل مع !:pageSize محددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | يحصل أو يحدد حجم الصفحة الناتجة للاستيراد. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

### انظر أيضًا

* فئة [LoadOptions](../loadoptions/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)