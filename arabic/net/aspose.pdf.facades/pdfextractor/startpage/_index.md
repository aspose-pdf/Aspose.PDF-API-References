---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfExtractor. تحصل أو تعين الصفحة الأولى في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/pdfextractor/startpage/
---
## خاصية PdfExtractor.StartPage

تحصل أو تعين الصفحة الأولى في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)