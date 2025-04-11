---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-egenskap. Ställer in läget för extraherade texters resultat
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode-egenskap

Ställer in läget för extraherad texts resultat.

```csharp
public int ExtractTextMode { get; set; }
```

### Egenskapsvärde

0 är rent textläge och 1 är rå ordningsläge. Standard är 0.

## Exempel

Exemplet visar användningen av `ExtractTextMode`-egenskapen i ett textutvinningsscenario.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)