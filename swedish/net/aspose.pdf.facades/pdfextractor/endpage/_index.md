---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-egenskap. Hämtar eller ställer in slutbladet i sidintervallet där extraheringsoperationen kommer att utföras
type: docs
weight: 20
url: /sv/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage-egenskap

Hämtar eller ställer in slutbladet i sidintervallet där extraheringsoperationen kommer att utföras.

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

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)