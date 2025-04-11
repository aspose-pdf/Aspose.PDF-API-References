---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.TextExtractorOptions. Mewakili opsi ekstraksi teks untuk plugin TextExtractor
type: docs
weight: 9390
url: /id/net/aspose.pdf.plugins/textextractoroptions/
---
## Kelas TextExtractorOptions

Mewakili opsi ekstraksi teks untuk plugin TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Menginisialisasi instance baru dari objek `TextExtractorOptions` dengan mode pemformatan teks 'Raw' (default). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Menginisialisasi instance baru dari objek `TextExtractorOptions` untuk mode pemformatan teks yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Mendapatkan mode pemformatan. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Mengembalikan koleksi data plugin PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Mengembalikan nama operasi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin PdfExtractor. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Mendefinisikan berbagai mode yang dapat digunakan saat mengonversi dokumen PDF menjadi teks. Lihat kelas `TextExtractorOptions`. |

## Catatan

Objek `TextExtractorOptions` digunakan untuk mengatur [`TextFormattingMode`](../textextractoroptions.textformattingmode/) dan opsi lainnya untuk operasi ekstraksi teks. Selain itu, ia mewarisi fungsi untuk menambahkan data (file, aliran) yang mewakili dokumen PDF input.

## Contoh

Contoh ini menunjukkan cara mengekstrak konten teks dari dokumen PDF.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Lihat Juga

* kelas [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)