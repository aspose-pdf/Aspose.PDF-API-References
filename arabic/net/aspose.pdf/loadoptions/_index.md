---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.LoadOptions. نوع LoadOptions يحمل مستوى من التجريد حول خيارات التحميل الفردية
type: docs
weight: 6120
url: /ar/net/aspose.pdf/loadoptions/
---
## فئة LoadOptions

نوع LoadOptions يحمل مستوى من التجريد حول خيارات التحميل الفردية

```csharp
public abstract class LoadOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون القيمة `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه `LoadOptions`. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يقوم WarningHandler بإرجاع عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)