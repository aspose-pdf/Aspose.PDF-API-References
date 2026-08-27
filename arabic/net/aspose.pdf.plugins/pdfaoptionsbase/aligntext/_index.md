---
title: "PdfAOptionsBase.AlignText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية PdfAOptionsBase. تحصل أو تعيين قيمة تشير إلى ما إذا كانت هناك حاجة إلى وسائل إضافية للحفاظ على محاذاة النص أثناء عملية تحويل PDF/A."
type: docs
weight: 10
url: /ar/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText property

يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هناك حاجة إلى وسائل إضافية للحفاظ على محاذاة النص أثناء عملية تحويل PDF/A.

```csharp
public bool AlignText { get; set; }
```

### Property Value

`true` إذا تم تغيير محاذاة النص وكانت هناك حاجة إلى إجراءات إضافية لاستعادتها؛ وإلا `false`.

## ملاحظات

عند تعيينه إلى `true`، ستحاول عملية التحويل استعادة حدود مقاطع النص الأصلية. بالنسبة لمعظم المستندات لا يلزم تغيير هذه الخاصية من القيمة الافتراضية `false`، لأن محاذاة النص لا تتغير أثناء عملية التحويل الافتراضية.

### انظر أيضًا

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


