---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.TextExtractor. Mewakili plugin TextExtractor
type: docs
weight: 9380
url: /id/net/aspose.pdf.plugins/textextractor/
---
## Kelas TextExtractor

Mewakili plugin TextExtractor.

```csharp
public class TextExtractor : PdfExtractor
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextExtractor](textextractor/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementasi dari IDisposable. Sebenarnya, tidak diperlukan untuk PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Memulai pemrosesan PdfExtractor dengan parameter yang ditentukan. |

## Catatan

Objek `TextExtractor` digunakan untuk mengekstrak teks dalam dokumen PDF.

## Contoh

Contoh ini menunjukkan cara mengekstrak konten teks dari dokumen PDF.

```csharp
// create TextExtractor object to extract text in PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Lihat Juga

* kelas [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)