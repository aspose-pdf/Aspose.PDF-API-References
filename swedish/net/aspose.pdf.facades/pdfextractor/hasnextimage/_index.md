---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-metod. Kontrollerar om fler bilder är tillgängliga i PDF-dokumentet. Observera att ExtractImage måste anropas innan denna metod används
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage metod

Kontrollerar om fler bilder är tillgängliga i PDF-dokumentet. Observera: ExtractImage måste anropas innan denna metod används.

```csharp
public bool HasNextImage()
```

### Returvärde

Sant om fler bilder är tillgängliga

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

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)