---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfExtractor. تحدد الوضع لنتيجة استخراج النصوص
type: docs
weight: 40
url: /ar/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## خاصية PdfExtractor.ExtractTextMode

تحدد الوضع لنتيجة استخراج النص.

```csharp
public int ExtractTextMode { get; set; }
```

### قيمة الخاصية

0 هو وضع النص النقي و 1 هو وضع الترتيب الخام. القيمة الافتراضية هي 0.

## أمثلة

توضح المثال استخدام خاصية `ExtractTextMode` في سيناريو استخراج النص.

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