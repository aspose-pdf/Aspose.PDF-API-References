---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.ImageExtractor. Mewakili plugin ImageExtractor
type: docs
weight: 8890
url: /id/net/aspose.pdf.plugins/imageextractor/
---
## Kelas ImageExtractor

Mewakili plugin ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementasi dari IDisposable. Sebenarnya, ini tidak diperlukan untuk PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Memulai pemrosesan PdfExtractor dengan parameter yang ditentukan. |

## Catatan

Objek `ImageExtractor` digunakan untuk mengekstrak teks dalam dokumen PDF.

## Contoh

Contoh ini menunjukkan cara mengekstrak gambar dari dokumen PDF.

```csharp
// create ImageExtractor object to extract images
using (ImageExtractor extractor = new ImageExtractor())
{
    // create ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // add input file path to data sources
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // get the image from the ResultContainer object
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### Lihat Juga

* kelas [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)