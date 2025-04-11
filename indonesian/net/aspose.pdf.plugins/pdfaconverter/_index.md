---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.PdfAConverter. Mewakili plugin untuk menangani konversi dokumen PDF dalam format PDF/A dan untuk validasi kesesuaian PDF/A
type: docs
weight: 9000
url: /id/net/aspose.pdf.plugins/pdfaconverter/
---
## Kelas PdfAConverter

Mewakili plugin untuk menangani konversi dokumen PDF dalam format PDF/A dan untuk validasi kesesuaian PDF/A.

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

Contoh ini menunjukkan cara memvalidasi kesesuaian dokumen PDF dengan format PDF/A (PDF/A-1a dalam kasus ini):

```csharp
// Create the options class to set up the validation process
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// Add one or more files to be validated
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// add more files as needed

// Create the plugin instance
var plugin = new PdfAConverter();

// Run the validation and get results
var resultContainer = plugin.Process(options);

// Check the resultContainer.ResultCollection property for validation results for each file:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

Contoh ini menunjukkan cara mengonversi dokumen PDF dalam format PDF/A (PDF/A-3b dalam kasus ini):

```csharp
// Create the options class to set up the conversion process
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// Add the source file
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// Add the path to save the converted file
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// Create the plugin instance
var plugin = new PdfAConverter();

// Run the conversion
plugin.Process(options);
```

### Lihat Juga

* antarmuka [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)