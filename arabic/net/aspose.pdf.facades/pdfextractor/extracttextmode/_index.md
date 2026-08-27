---
title: "PdfExtractor.ExtractTextMode"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية PdfExtractor. تحدد الوضع لنتيجة استخراج النصوص"
type: docs
weight: 40
url: /ar/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

يضبط الوضع لنتيجة استخراج النص.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 هو وضع النص النقي و1 هو وضع الترتيب الخام. القيمة الافتراضية هي 0.

## أمثلة

يوضح المثال استخدام خاصية `ExtractTextMode` في سيناريو استخراج النص.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


