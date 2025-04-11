---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfAConverter. Representa um plugin para lidar com a conversão de documentos PDF em formato PDF/A e para validação da conformidade PDF/A
type: docs
weight: 9000
url: /pt/net/aspose.pdf.plugins/pdfaconverter/
---
## Classe PdfAConverter

Representa um plugin para lidar com a conversão de documentos PDF em formato PDF/A e para validação da conformidade PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Inicia um processo de conversão ou validação PDF/A com as opções dadas. |

## Exemplos

O exemplo demonstra como validar a conformidade do documento PDF com o formato PDF/A (PDF/A-1a neste caso):

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

O exemplo demonstra como converter o documento PDF em um formato PDF/A (PDF/A-3b neste caso):

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

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)