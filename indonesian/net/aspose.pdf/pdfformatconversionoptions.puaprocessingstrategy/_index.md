---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. Beberapa dokumen PDF memiliki simbol unicode khusus yang termasuk dalam Private Use Area, lihat deskripsi di https//en.wikipedia.org/wiki/Private_Use_Areas. Simbol-simbol ini menyebabkan kesalahan yang sesuai dengan PDF/A seperti "Teks dipetakan ke Private Use Area Unicode tetapi tidak ada entri ActualText yang hadir". Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk menangani simbol PUA.
type: docs
weight: 8390
url: /id/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## Enumerasi PdfFormatConversionOptions.PuaProcessingStrategy

Beberapa dokumen PDF memiliki simbol unicode khusus, yang termasuk dalam Private Use Area (PUA), lihat deskripsi di https://en.wikipedia.org/wiki/Private_Use_Areas. Simbol-simbol ini menyebabkan kesalahan yang sesuai dengan PDF/A seperti "Teks dipetakan ke Private Use Area Unicode tetapi tidak ada entri ActualText yang hadir". Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk menangani simbol PUA.

```csharp
public enum PuaProcessingStrategy
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Nonaktifkan pemrosesan simbol PUA. Strategi ini digunakan secara default untuk dokumen PDF/A dengan kepatuhan Level B. |
| SurroundPuaTextWithEmptyActualText | `1` | Menyisipkan blok konten yang ditandai dengan entri ActualText yang berisi teks kosong. Strategi ini memberikan hasil yang baik untuk dokumen tanpa blok konten yang ditandai. Digunakan secara default untuk dokumen PDF/A dengan kepatuhan Level A. |
| SubstitutePuaSymbols | `2` | Strategi ini bekerja lebih lambat daripada 'SurroundPuaTextWithEmptyActualText' tetapi dapat menghapus kesalahan yang sesuai dengan PUA untuk dokumen yang tidak dapat ditangani dengan baik oleh SurroundPuaTextWithEmptyActualText. Simbol PUA digantikan dengan simbol 'spasi' atau unicode khusus (beberapa simbol PUA memiliki analog unicode). Penggantian diterapkan tidak pada teks dokumen tetapi pada data internal font ToUnicode sehingga tidak mempengaruhi tampilan simbol tetapi mempengaruhi presentasi simbol dalam operasi salin/tempel di sistem buffer. |

### Lihat Juga

* kelas [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)