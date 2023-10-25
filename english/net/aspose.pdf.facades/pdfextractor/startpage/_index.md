---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor property. Gets or sets start page in the page range where extracting operation will be performed
type: docs
weight: 80
url: /net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

Gets or sets start page in the page range where extracting operation will be performed.

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

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


