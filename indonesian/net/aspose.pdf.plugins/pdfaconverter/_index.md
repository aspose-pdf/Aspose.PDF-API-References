---
title: "Kelas PdfAConverter"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Plugins.PdfAConverter kelas. Mewakili plugin untuk menangani konversi dokumen PDF ke format PDF/A dan untuk validasi kepatuhan PDF/A"
type: docs
weight: 9150
url: /id/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

Mewakili plugin untuk menangani konversi dokumen PDF ke format PDF/A dan untuk validasi kepatuhan PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Memulai proses konversi atau validasi PDF/A dengan opsi yang diberikan. |

## Contoh

Contoh ini menunjukkan cara memvalidasi kepatuhan dokumen PDF terhadap format PDF/A (PDF/A-1a dalam kasus ini):

```csharp
// Buat kelas opsi untuk menyiapkan proses validasi
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// Tambahkan satu atau lebih file untuk divalidasi
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// tambahkan lebih banyak file sesuai kebutuhan

// Buat instance plugin
var plugin = new PdfAConverter();

// Jalankan validasi dan dapatkan hasilnya
var resultContainer = plugin.Process(options);

// Periksa properti resultContainer.ResultCollection untuk hasil validasi setiap file:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

Contoh ini menunjukkan cara mengonversi dokumen PDF ke format PDF/A (PDF/A-3b dalam kasus ini):

```csharp
// Buat kelas opsi untuk menyiapkan proses konversi
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// Tambahkan file sumber
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// Tambahkan jalur untuk menyimpan file yang dikonversi
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// Buat instance plugin
var plugin = new PdfAConverter();

// Jalankan konversi
plugin.Process(options);
```

### Lihat Juga

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


