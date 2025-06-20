---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConverter class. Represents a plugin for handling the conversion of PDF documents in a PDF/A format and for validation of the PDF/A conformance
type: docs
weight: 9130
url: /net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

Represents a plugin for handling the conversion of PDF documents in a PDF/A format and for validation of the PDF/A conformance.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Begins a PDF/A conversion or validation process with given options. |

## Examples

The example demonstrates how to validate the PDF document conformance to PDF/A format (PDF/A-1a in this case):

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

The example demonstrates how to convert the PDF document in a PDF/A format (PDF/A-3b in this case):

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

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


