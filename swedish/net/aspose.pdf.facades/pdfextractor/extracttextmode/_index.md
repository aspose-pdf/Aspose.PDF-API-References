---
title: ExtractTextMode
second_title: Aspose.PDF för .NET API Referens
description: Ställer in läget för extrahering av textresultat.
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

Ställer in läget för extrahering av textresultat.

```csharp
public int ExtractTextMode { get; set; }
```

### Fastighetsvärde

0 är rent textläge och 1 är råbeställningsläge. Standard är 0.

### Exempel

Exemplet visar`ExtractTextMode` egenskapsanvändning i textextraktionsscenario.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Se även

* class [PdfExtractor](../../pdfextractor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfextractor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->