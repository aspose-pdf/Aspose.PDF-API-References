---
title: "PdfExtractor.ExtractTextMode"
linktitle: "ExtractTextMode"
articleTitle: "ExtractTextMode"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor property. Sets the mode for extract text's result."
type: docs
weight: 270
url: "/net/aspose.pdf.facades/pdfextractor/extracttextmode/"
product_version: "26.9.0"
---
## PdfExtractor.ExtractTextMode property

Sets the mode for extract text's result.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 is pure text mode and 1 is raw ordering mode. Default is 0.

## Examples

The example demonstrates the `ExtractTextMode` property usage in text extraction scenario.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

