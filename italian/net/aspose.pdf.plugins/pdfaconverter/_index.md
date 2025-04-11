---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfAConverter. Rappresenta un plugin per gestire la conversione di documenti PDF in formato PDF/A e per la validazione della conformità al PDF/A
type: docs
weight: 9000
url: /it/net/aspose.pdf.plugins/pdfaconverter/
---
## Classe PdfAConverter

Rappresenta un plugin per gestire la conversione di documenti PDF in formato PDF/A e per la validazione della conformità al PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Inizia un processo di conversione o validazione PDF/A con le opzioni date. |

## Esempi

L'esempio dimostra come validare la conformità del documento PDF al formato PDF/A (PDF/A-1a in questo caso):

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

L'esempio dimostra come convertire il documento PDF in un formato PDF/A (PDF/A-3b in questo caso):

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

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)