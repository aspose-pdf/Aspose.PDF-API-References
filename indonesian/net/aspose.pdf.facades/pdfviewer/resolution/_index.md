---
title: "PdfViewer.Resolution"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti PdfViewer. Mendapatkan atau mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatan. Nilai default adalah 150"
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

Mendapatkan atau mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatan. Nilai default adalah 150.

```csharp
public int Resolution { get; set; }
```

## Catatan

Properti ini mengubah resolusi gambar dalam alur konversi halaman-ke-gambar: ketika [`PrintAsImage`](../printasimage/) diatur ke `true`, atau ketika metode [`DecodePage`](../decodepage/) atau [`DecodeAllPages`](../decodeallpages/) dipanggil. Untuk mengatur resolusi printer untuk pencetakan langsung ke printer, gunakan properti [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) dalam kelas [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Lihat Juga

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


