---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: Properti PdfViewer. Mendapatkan atau mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatannya. Nilai default adalah 150
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfviewer/resolution/
---
## Properti PdfViewer.Resolution

Mendapatkan atau mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatannya. Nilai default adalah 150.

```csharp
public int Resolution { get; set; }
```

## Keterangan

Properti ini mengubah resolusi gambar dalam alur konversi halaman ke gambar: ketika [`PrintAsImage`](../printasimage/) diatur ke `true`, atau ketika metode [`DecodePage`](../decodepage/) atau [`DecodeAllPages`](../decodeallpages/) dipanggil. Untuk mengatur resolusi printer untuk pencetakan langsung ke printer, gunakan properti [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) dalam kelas [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Lihat Juga

* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)