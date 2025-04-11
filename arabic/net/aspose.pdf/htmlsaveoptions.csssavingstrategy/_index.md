---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: يمكنك تعيين استراتيجية مخصصة لهذه الخاصية تقوم بتنفيذ معالجة أو/و حفظ جزء من CSS تم إنشاؤه أثناء تحويل PDF إلى HTML. في هذه الحالة، يجب أن تتم المعالجة مثل الحفظ إلى دفق أو قرص في هذا الكود المخصص
type: docs
weight: 5590
url: /ar/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

يمكنك تعيين استراتيجية مخصصة لهذه الخاصية تقوم بتنفيذ معالجة أو/و حفظ جزء من CSS تم إنشاؤه أثناء تحويل PDF إلى HTML. في هذه الحالة، يجب أن تتم المعالجة (مثل الحفظ إلى دفق أو قرص) في هذا الكود المخصص

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parameter | Type | Description |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | يمثل مجموعة من البيانات التي يمكن استخدامها لحفظ جزء CSS المقدم |

### See Also

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)