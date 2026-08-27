---
title: "Kelas TextExtractor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.TextExtractor. Mewakili plugin TextExtractor"
type: docs
weight: 9530
url: /id/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

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
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementasi IDisposable. Sebenarnya, ini tidak diperlukan untuk PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Memulai pemrosesan PdfExtractor dengan parameter yang ditentukan. |

## Catatan

Objek `TextExtractor` digunakan untuk mengekstrak teks dalam dokumen PDF.

## Contoh

Contoh ini menunjukkan cara mengekstrak konten teks dari dokumen PDF.

```csharp
// buat objek TextExtractor untuk mengekstrak teks dalam konten PDF
using (TextExtractor extractor = new TextExtractor())
{
    // buat TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // tambahkan jalur file input ke sumber data
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // lakukan proses ekstraksi
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // dapatkan teks yang diekstrak dari objek ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Lihat Juga

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


