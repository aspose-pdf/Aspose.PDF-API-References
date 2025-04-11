---
title: Class CdrLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.CdrLoadOptions. تصف الفئة خيارات تحميل CDR
type: docs
weight: 2960
url: /ar/net/aspose.pdf/cdrloadoptions/
---
## CdrLoadOptions class

تصف الفئة خيارات تحميل CDR.

```csharp
public class CdrLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [CdrLoadOptions](cdrloadoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يضبط علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون القيمة `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُرجع WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)