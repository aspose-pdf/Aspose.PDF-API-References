---
title: "PdfExtractor.HasNextImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor‑metod. Kontrollerar om fler bilder är tillgängliga i PDF-dokumentet. Observera att ExtractImage måste anropas innan denna metod används"
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

Kontrollerar om fler bilder är tillgängliga i PDF-dokumentet. Obs: ExtractImage måste anropas innan den här metoden används.

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

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


