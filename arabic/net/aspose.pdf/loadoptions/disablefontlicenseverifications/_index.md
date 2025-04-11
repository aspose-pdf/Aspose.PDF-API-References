---
title: LoadOptions.DisableFontLicenseVerifications
second_title: Aspose.PDF for .NET API Reference
description: خاصية LoadOptions. تحصل أو تعين علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون صحيحة، يسمح بتنفيذ العمليات مع الخط الذي تحظره رخصة هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تمنع الإدراج لهذا الخط. بشكل افتراضي، تكون خاطئة.
type: docs
weight: 10
url: /ar/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## خاصية LoadOptions.DisableFontLicenseVerifications

تحصل أو تعين علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ العمليات مع الخط الذي تحظره رخصة هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تمنع الإدراج لهذا الخط. بشكل افتراضي، تكون `false`.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## ملاحظات

كن حذرًا عند استخدام هذه العلامة. عندما يتم تعيينها، فهذا يعني أن الشخص الذي يعين هذه العلامة يتحمل كل مسؤولية انتهاكات الترخيص/القانون المحتملة على عاتقه. لذا فهو يتحمل ذلك على مسؤوليته الخاصة. يُوصى بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا أنك لا تنتهك قانون حقوق الطبع والنشر.

### انظر أيضًا

* class [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)