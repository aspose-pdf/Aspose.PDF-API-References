---
title: "PdfExtractor.ExtractImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor‑metod. Extrahera bilder från PDF‑filen"
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage method

Extrahera bilder från PDF-fil.

```csharp
public void ExtractImage()
```

## Exempel

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

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


