---
title: "Kelas TextExtractorOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Plugins.TextExtractorOptions kelas. Mewakili opsi ekstraksi teks untuk plugin TextExtractor."
type: docs
weight: 9540
url: /id/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

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

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Mendefinisikan berbagai mode yang dapat digunakan saat mengonversi dokumen PDF menjadi teks. Lihat kelas `TextExtractorOptions`. |

## Catatan

Objek `TextExtractorOptions` digunakan untuk mengatur [`TextFormattingMode`](../textextractoroptions.textformattingmode/) dan opsi lain untuk operasi ekstraksi teks. Juga, objek ini mewarisi fungsi untuk menambahkan data (file, stream) yang mewakili dokumen PDF input.

## Contoh

Contoh ini menunjukkan cara mengekstrak konten teks dari dokumen PDF.

```csharp
// buat objek TextExtractor untuk mengekstrak konten PDF
using (TextExtractor extractor = new TextExtractor())
{
    // buat objek TextExtractorOptions untuk mengatur TextFormattingMode (Pure, atau Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // tambahkan jalur file input ke sumber data
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // lakukan proses ekstraksi
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // dapatkan teks yang diekstrak dari objek ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Lihat Juga

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


