---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PdfAConverter. Представляет плагин для обработки конвертации PDF-документов в формат PDF/A и для проверки соответствия PDF/A
type: docs
weight: 9000
url: /ru/net/aspose.pdf.plugins/pdfaconverter/
---
## Класс PdfAConverter

Представляет плагин для обработки конвертации PDF-документов в формат PDF/A и для проверки соответствия PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Начинает процесс конвертации или проверки PDF/A с заданными параметрами. |

## Примеры

Пример демонстрирует, как проверить соответствие PDF-документа формату PDF/A (в данном случае PDF/A-1a):

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

Пример демонстрирует, как конвертировать PDF-документ в формат PDF/A (в данном случае PDF/A-3b):

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

### См. также

* интерфейс [IPlugin](../iplugin/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)