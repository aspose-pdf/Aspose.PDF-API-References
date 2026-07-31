---
title: "Kelas PdfExtractor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.PdfExtractor. Mewakili fungsionalitas dasar untuk mengekstrak teks, gambar, dan jenis konten lain yang mungkin muncul pada halaman PDF documents"
type: docs
weight: 9210
url: /id/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

Mewakili fungsionalitas dasar untuk mengekstrak teks, gambar, dan jenis konten lain yang mungkin terdapat pada halaman dokumen PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementasi IDisposable. Sebenarnya, ini tidak diperlukan untuk PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Memulai pemrosesan PdfExtractor dengan parameter yang ditentukan. |

## Catatan

Objek [`TextExtractor`](../textextractor/) digunakan untuk mengekstrak teks, atau [`ImageExtractor`](../imageextractor/) untuk mengekstrak gambar.

## Contoh

Contoh ini menunjukkan cara mengekstrak konten teks dari dokumen PDF.

```csharp
// buat objek TextExtractor untuk mengekstrak konten PDF
using (TextExtractor extractor = new TextExtractor())
{
    // buat objek TextExtractorOptions untuk mengatur instruksi
    textExtractorOptions = new TextExtractorOptions();
    
    // tambahkan jalur file input ke sumber data
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // lakukan proses ekstraksi
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // dapatkan teks yang diekstrak dari objek ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Lihat Juga

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


