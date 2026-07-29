---
title: "الفئة CgmLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.CgmLoadOptions. تحتوي على خيارات لتحميل/استيراد ملف CGM إلى مستند pdf"
type: docs
weight: 3120
url: /ar/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions class

يحتوي على خيارات لتحميل/استيراد ملف CGM إلى مستند pdf.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | ينشئ خيارات التحميل الافتراضية لتحويل ملف CGM إلى مستند pdf. حجم صفحة pdf الافتراضي - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | ينشئ خيارات التحميل مع حجم الصفحة المحدد !:pageSize. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | يحصل أو يعيّن حجم صفحة الإخراج للاستيراد. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


