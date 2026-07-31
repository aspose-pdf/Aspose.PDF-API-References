---
title: "PdfExtractor.HasNextImage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfExtractor. Memeriksa apakah ada gambar lain yang dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini"
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

Memeriksa apakah lebih banyak gambar dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini.

```csharp
public bool HasNextImage()
```

### Nilai Kembalian

Benar jika ada gambar lain yang dapat diakses

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


