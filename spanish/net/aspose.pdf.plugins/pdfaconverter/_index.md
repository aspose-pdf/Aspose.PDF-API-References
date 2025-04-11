---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.PdfAConverter. Representa un complemento para manejar la conversión de documentos PDF en un formato PDF/A y para la validación de la conformidad con PDF/A
type: docs
weight: 9000
url: /es/net/aspose.pdf.plugins/pdfaconverter/
---
## Clase PdfAConverter

Representa un complemento para manejar la conversión de documentos PDF en un formato PDF/A y para la validación de la conformidad con PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Comienza un proceso de conversión o validación de PDF/A con las opciones dadas. |

## Ejemplos

El ejemplo demuestra cómo validar la conformidad del documento PDF con el formato PDF/A (PDF/A-1a en este caso):

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

El ejemplo demuestra cómo convertir el documento PDF en un formato PDF/A (PDF/A-3b en este caso):

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

### Véase También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)