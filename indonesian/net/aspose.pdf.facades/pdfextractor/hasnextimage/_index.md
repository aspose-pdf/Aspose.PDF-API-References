---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfExtractor. Memeriksa apakah lebih banyak gambar dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## Metode PdfExtractor.HasNextImage

Memeriksa apakah lebih banyak gambar dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini.

```csharp
public bool HasNextImage()
```

### Nilai Kembali

Benar jika lebih banyak gambar dapat diakses

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