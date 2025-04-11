---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfExtractor. تحصل أو تعين الصفحة النهائية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج
type: docs
weight: 20
url: /ar/net/aspose.pdf.facades/pdfextractor/endpage/
---
## خاصية PdfExtractor.EndPage

تحصل أو تعين الصفحة النهائية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)