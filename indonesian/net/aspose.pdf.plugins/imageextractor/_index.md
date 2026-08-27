---
title: "Kelas ImageExtractor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.ImageExtractor. Mewakili plugin ImageExtractor"
type: docs
weight: 9020
url: /id/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

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
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementasi IDisposable. Sebenarnya, ini tidak diperlukan untuk PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Memulai pemrosesan PdfExtractor dengan parameter yang ditentukan. |

## Catatan

Objek `ImageExtractor` digunakan untuk mengekstrak teks dalam PDF Document.

## Contoh

Contoh ini menunjukkan cara mengekstrak gambar dari PDF Document.

```csharp
// buat objek ImageExtractor untuk mengekstrak gambar
using (ImageExtractor extractor = new ImageExtractor())
{
    // buat ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // tambahkan jalur file input ke sumber data
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // lakukan proses ekstraksi
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // dapatkan gambar dari objek ResultContainer
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### Lihat Juga

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


