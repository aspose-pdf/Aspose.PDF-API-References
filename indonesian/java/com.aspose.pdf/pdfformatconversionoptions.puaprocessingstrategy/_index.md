---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Beberapa dokumen PDF memiliki simbol unicode khusus, yang termasuk dalam Private Use Area (PUA), lihat deskripsi di https://en.wikipedia.org/wiki/Private_Use_Areas. Simbol-simbol ini."
type: docs
weight: 3750
url: /id/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Beberapa dokumen PDF memiliki simbol unicode khusus, yang termasuk dalam Private Use Area (PUA), lihat deskripsi di https://en.wikipedia.org/wiki/Private_Use_Areas. Simbol-simbol ini menyebabkan kesalahan kepatuhan PDF/A seperti "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk menangani simbol PUA.

## Fields

| Field | Deskripsi |
| --- | --- |
| [None](#None) | Nonaktifkan pemrosesan simbol PUA. Strategi ini digunakan secara default untuk dokumen PDF/A dengan kepatuhan Level B. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Strategi ini bekerja lebih lambat daripada 'SurroundPuaTextWithEmptyActualText' tetapi dapat menghapus kesalahan kepatuhan PUA untuk dokumen yang tidak dapat ditangani dengan baik oleh SurroundPuaTextWithEmptyActualText. Simbol PUA diganti dengan simbol 'space' atau unicode khusus (beberapa simbol PUA memiliki analog unicode). Substitusi diterapkan bukan pada teks dokumen tetapi pada data internal font ToUnicode sehingga tidak memengaruhi tampilan simbol tetapi memengaruhi presentasi simbol dalam operasi salin/tempel pada buffer sistem. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Menyisipkan blok konten yang ditandai dengan entri ActualText yang berisi teks kosong. Strategi ini memberikan hasil yang baik untuk dokumen tanpa blok konten yang ditandai. Digunakan secara default untuk dokumen PDF/A dengan kepatuhan Level A. |

### None {#None}
```
public static final int None
```

Nonaktifkan pemrosesan simbol PUA. Strategi ini digunakan secara default untuk dokumen PDF/A dengan kepatuhan Level B.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Strategi ini bekerja lebih lambat daripada 'SurroundPuaTextWithEmptyActualText' tetapi dapat menghapus kesalahan kepatuhan PUA untuk dokumen yang tidak dapat ditangani dengan baik oleh SurroundPuaTextWithEmptyActualText. Simbol PUA diganti dengan simbol 'space' atau unicode khusus (beberapa simbol PUA memiliki analog unicode). Substitusi diterapkan bukan pada teks dokumen tetapi pada data internal font ToUnicode sehingga tidak memengaruhi tampilan simbol tetapi memengaruhi presentasi simbol dalam operasi salin/tempel pada buffer sistem.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Menyisipkan blok konten yang ditandai dengan entri ActualText yang berisi teks kosong. Strategi ini memberikan hasil yang baik untuk dokumen tanpa blok konten yang ditandai. Digunakan secara default untuk dokumen PDF/A dengan kepatuhan Level A.
