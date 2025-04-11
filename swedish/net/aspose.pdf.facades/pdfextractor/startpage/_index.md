---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-egenskap. Hämtar eller ställer in startsidans intervall där extraktionsoperationen kommer att utföras
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage-egenskap

Hämtar eller ställer in startsidans intervall där extraktionsoperationen kommer att utföras.

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

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)