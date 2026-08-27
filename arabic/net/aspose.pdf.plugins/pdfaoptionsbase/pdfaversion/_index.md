---
title: "PdfAOptionsBase.PdfAVersion"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "PdfAOptionsBase property. يحصل أو يضبط نسخة معيار PDF/A المستخدمة للتحقق أو التحويل"
type: docs
weight: 110
url: /ar/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## PdfAOptionsBase.PdfAVersion property

يحصل أو يعيّن نسخة معيار PDF/A التي ستُستخدم للتحقق أو التحويل.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Property Value

نسخة معيار PDF/A. يمكن أن تكون واحدة من القيم في تعداد [`PdfAStandardVersion`](../../pdfastandardversion/).

## ملاحظات

يتم استخدام إصدار معيار PDF/A لتحديد مستوى الامتثال للتحقق من صحة PDF/A والتحويل. إذا تم تعيين الإصدار إلى Auto، سيقوم النظام تلقائيًا بتحديد الإصدار المناسب لمعيار PDF/A للتحقق بناءً على بيانات تعريف المستند. بالنسبة لعملية تحويل PDF/A، يكون Auto افتراضيًا إلى إصدار معيار PDF/A-1b.

### انظر أيضًا

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


