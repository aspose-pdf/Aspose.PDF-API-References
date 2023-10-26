---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor method. Checks if more images are accessible in PDF document. Note ExtractImage must be called before using of this method
type: docs
weight: 200
url: /net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

Checks if more images are accessible in PDF document. Note: ExtractImage must be called before using of this method.

```csharp
public bool HasNextImage()
```

### Return Value

Trues if more images are accessible

## Examples

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


