---
title: "Enum TextExtractionOptions.TextFormattingMode"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode. Mendefinisikan berbagai mode yang dapat digunakan saat mengonversi dokumen pdf menjadi teks. Lihat kelas TextDevice"
type: docs
weight: 11080
url: /id/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

Mendefinisikan berbagai mode yang dapat digunakan saat mengonversi dokumen pdf menjadi teks. Lihat kelas !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Pure | `0` | Mewakili konten pdf dengan sedikit rutinitas pemformatan. |
| Raw | `1` | Mewakili konten pdf apa adanya, yaitu tanpa pemformatan. |
| Flatten | `2` | Mewakili konten pdf dengan menempatkan fragmen teks berdasarkan koordinatnya. Pada dasarnya mirip dengan mode "Raw". Namun sementara "Raw" fokus pada mempertahankan struktur fragmen teks (operator) dalam dokumen, "Flatten" fokus pada menjaga teks dalam urutan yang dibaca. |
| MemorySaving | `3` | Ekstraksi dengan penghematan memori. Hampir sama dengan mode 'Raw' tetapi bekerja sedikit lebih cepat dan menggunakan lebih sedikit memori. |

### Lihat Juga

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


