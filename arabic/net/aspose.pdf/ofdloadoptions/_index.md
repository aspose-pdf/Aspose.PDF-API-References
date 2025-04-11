---
title: Class OfdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.OfdLoadOptions. خيارات التحميل لتنسيق OFD
type: docs
weight: 7060
url: /ar/net/aspose.pdf/ofdloadoptions/
---
## OfdLoadOptions class

خيارات التحميل لتنسيق OFD.

```csharp
public class OfdLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [OfdLoadOptions](ofdloadoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون القيمة `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد الاتصال لمعالجة أي تحذيرات تم إنشاؤها. يُرجع WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)