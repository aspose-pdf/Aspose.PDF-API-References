---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor property. Gets or sets end page in the page range where extracting operation will be performed
type: docs
weight: 20
url: /net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

Gets or sets end page in the page range where extracting operation will be performed.

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

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


