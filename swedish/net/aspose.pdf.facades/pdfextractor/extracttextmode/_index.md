---
title: "PdfExtractor.ExtractTextMode"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor-egenskap. Anger läget för resultatet av extraherade texter."
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

Ställer in läget för resultatet av textutdragning.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 är rent textläge och 1 är råt sorteringsläge. Standard är 0.

## Exempel

Exemplet demonstrerar användningen av `ExtractTextMode`-egenskapen i ett textutdragningsscenario.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


