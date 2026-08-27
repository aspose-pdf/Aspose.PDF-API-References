---
title: "PdfExtractor.ExtractImage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfExtractor. Mengekstrak gambar dari file PDF"
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage method

Mengekstrak gambar dari file PDF.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


