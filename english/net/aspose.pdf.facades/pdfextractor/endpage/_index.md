---
title: "PdfExtractor.EndPage"
linktitle: "EndPage"
articleTitle: "EndPage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor property. Gets or sets end page in the page range where extracting operation will be performed. PdfExtractor ext = new PdfExtractor(); ext.BindB..."
type: docs
weight: 260
url: "/net/aspose.pdf.facades/pdfextractor/endpage/"
product_version: "26.9.0"
---
## PdfExtractor.EndPage property

Gets or sets end page in the page range where extracting operation will be performed.
 
 PdfExtractor ext = new PdfExtractor();
 ext.BindBdf("sample.pdf");
 ext.StartPage = 2;
 ext.EndPage = 3;
 ext.ExtractText();

```csharp
public int EndPage { get; set; }
```

### Property Value

int

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

