---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfAOptionsBase. تحصل أو تعين قيمة تشير إلى ما إذا كانت وسائل إضافية ضرورية للحفاظ على محاذاة النص أثناء عملية تحويل PDF/A
type: docs
weight: 10
url: /ar/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## خاصية PdfAOptionsBase.AlignText

تحصل أو تعين قيمة تشير إلى ما إذا كانت وسائل إضافية ضرورية للحفاظ على محاذاة النص أثناء عملية تحويل PDF/A.

```csharp
public bool AlignText { get; set; }
```

### قيمة الخاصية

`true` إذا تم تغيير محاذاة النص وكانت هناك حاجة إلى إجراءات إضافية لاستعادتها؛ خلاف ذلك، `false`.

## ملاحظات

عند تعيينها إلى `true`، ستسعى عملية التحويل إلى استعادة حدود مقاطع النص الأصلية. بالنسبة لمعظم الوثائق، لا حاجة لتغيير هذه الخاصية من القيمة الافتراضية `false`، حيث أن محاذاة النص لا تتغير أثناء عملية التحويل الافتراضية.

### انظر أيضًا

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)