---
title: "PdfExtractor.HasNextPageText"
linktitle: "HasNextPageText"
articleTitle: "HasNextPageText"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Indicates that whether can get more texts or not."
type: docs
weight: 190
url: "/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/"
product_version: "26.9"
---
## PdfExtractor.HasNextPageText method

Indicates that whether can get more texts or not.

```csharp
public bool HasNextPageText()
```

### Return Value

Can get more texts or not, true is can, or false.

## Examples

The example demonstrates the `HasNextPageText` property usage in text extraction scenario.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

