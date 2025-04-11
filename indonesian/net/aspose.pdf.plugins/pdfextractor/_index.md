---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.PdfExtractor. Mewakili fungsionalitas dasar untuk mengekstrak teks, gambar, dan jenis konten lain yang mungkin terjadi di halaman dokumen PDF
type: docs
weight: 9060
url: /id/net/aspose.pdf.plugins/pdfextractor/
---
## Kelas PdfExtractor

Mewakili fungsionalitas dasar untuk mengekstrak teks, gambar, dan jenis konten lain yang mungkin terjadi di halaman dokumen PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementasi dari IDisposable. Sebenarnya, tidak diperlukan untuk PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Memulai pemrosesan PdfExtractor dengan parameter yang ditentukan. |

## Catatan

Objek [`TextExtractor`](../textextractor/) digunakan untuk mengekstrak teks, atau [`ImageExtractor`](../imageextractor/) untuk mengekstrak gambar.

## Contoh

Contoh ini menunjukkan cara mengekstrak konten teks dari dokumen PDF.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Lihat Juga

* antarmuka [IPlugin](../iplugin/)
* ruang nama [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)