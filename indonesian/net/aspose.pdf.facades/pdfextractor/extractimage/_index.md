---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfExtractor. Ekstrak gambar dari file PDF
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## Metode PdfExtractor.ExtractImage

Ekstrak gambar dari file PDF.

```csharp
public void ExtractImage()
```

## Contoh

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

### Lihat Juga

* kelas [PdfExtractor](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)