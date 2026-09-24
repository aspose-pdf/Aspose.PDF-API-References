---
title: "PdfExtractor.StartPage"
linktitle: "StartPage"
articleTitle: "StartPage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor property. Gets or sets start page in the page range where extracting operation will be performed. PdfExtractor ext = new PdfExtractor(); ext.Bin..."
type: docs
weight: 250
url: "/net/aspose.pdf.facades/pdfextractor/startpage/"
product_version: "26.9.0"
---
## PdfExtractor.StartPage property

Gets or sets start page in the page range where extracting operation will be performed.
 
 PdfExtractor ext = new PdfExtractor();
 ext.BindBdf("sample.pdf");
 ext.StartPage = 2;
 ext.EndPage = 5;
 ext.ExtractText();

```csharp
public int StartPage { get; set; }
```

### Property Value

int

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

