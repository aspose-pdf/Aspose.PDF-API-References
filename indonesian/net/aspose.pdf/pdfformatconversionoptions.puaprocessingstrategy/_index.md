---
title: "Enum PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. Beberapa dokumen PDF memiliki simbol unicode khusus yang termasuk dalam Private Use Area (PUA); lihat deskripsi di https//en.wikipedia.org/wiki/Private_Use_Areas. Simbol-simbol ini menyebabkan kesalahan kepatuhan PDF/A seperti \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Enum ini mendeklarasikan strategi yang dapat digunakan untuk menangani simbol PUA."
type: docs
weight: 8530
url: /id/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

Beberapa dokumen PDF memiliki simbol unicode khusus yang termasuk dalam Private Use Area (PUA), lihat deskripsi di https://en.wikipedia.org/wiki/Private_Use_Areas. Simbol-simbol ini menyebabkan kesalahan kepatuhan PDF/A seperti "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Enum ini mendeklarasikan strategi yang dapat digunakan untuk menangani simbol PUA.

```csharp
public enum PuaProcessingStrategy
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Nonaktifkan pemrosesan simbol PUA. Strategi ini digunakan secara default untuk dokumen PDF/A dengan konformitas Level B. |
| SurroundPuaTextWithEmptyActualText | `1` | Menyisipkan blok konten yang ditandai dengan entri ActualText yang berisi teks kosong. Strategi ini memberikan hasil yang baik untuk dokumen tanpa blok konten yang ditandai. Digunakan secara default untuk dokumen PDF/A dengan konformitas Level A. |
| SubstitutePuaSymbols | `2` | Strategi ini bekerja lebih lambat daripada 'SurroundPuaTextWithEmptyActualText' tetapi dapat menghapus kesalahan kepatuhan PUA untuk dokumen yang tidak dapat ditangani dengan baik oleh SurroundPuaTextWithEmptyActualText. Simbol PUA digantikan dengan simbol 'space' atau unicode khusus (beberapa simbol PUA memiliki analog unicode). Substitusi diterapkan bukan pada teks dokumen tetapi pada data internal font ToUnicode sehingga tidak memengaruhi tampilan simbol tetapi memengaruhi presentasi simbol dalam operasi salin/tempel pada buffer sistem. |

### Lihat Juga

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


