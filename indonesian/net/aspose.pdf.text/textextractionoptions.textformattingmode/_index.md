---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode enum. Menentukan berbagai mode yang dapat digunakan saat mengonversi dokumen pdf menjadi teks. Lihat kelas TextDevice
type: docs
weight: 10900
url: /id/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## Enumerasi TextExtractionOptions.TextFormattingMode

Menentukan berbagai mode yang dapat digunakan saat mengonversi dokumen pdf menjadi teks. Lihat kelas !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Pure | `0` | Mewakili konten pdf dengan sedikit rutinitas pemformatan. |
| Raw | `1` | Mewakili konten pdf apa adanya, yaitu tanpa pemformatan. |
| Flatten | `2` | Mewakili konten pdf dengan memposisikan fragmen teks berdasarkan koordinatnya. Ini pada dasarnya mirip dengan mode "Raw". Tetapi sementara "Raw" fokus pada mempertahankan struktur fragmen teks (operator) dalam dokumen, "Flatten" fokus pada menjaga teks dalam urutan saat dibaca. |
| MemorySaving | `3` | Ekstraksi dengan penghematan memori. Ini hampir sama dengan mode 'Raw' tetapi bekerja sedikit lebih cepat dan menggunakan lebih sedikit memori. |

### Lihat Juga

* kelas [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)