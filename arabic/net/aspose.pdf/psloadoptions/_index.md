---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.PsLoadOptions. تمثل الخيارات لتحميل/استيراد ملف .mht إلى مستند PDF
type: docs
weight: 9730
url: /ar/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

تمثل الخيارات لتحميل/استيراد ملف .mht إلى مستند PDF.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون القيمة `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تمنع الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | يحصل أو يحدد مسارات مجلدات الخطوط. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُرجع WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)