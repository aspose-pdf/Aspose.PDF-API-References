---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor metodu. PDF dosyasından görüntüleri çıkar
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.GörüntüÇıkar metodu

PDF dosyasından görüntüleri çıkar.

```csharp
public void ExtractImage()
```

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)