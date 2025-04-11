---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConverter 类。表示一个处理 PDF 文档转换为 PDF/A 格式以及验证 PDF/A 合规性的插件
type: docs
weight: 9000
url: /zh/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

表示一个处理 PDF 文档转换为 PDF/A 格式以及验证 PDF/A 合规性的插件。

```csharp
public sealed class PdfAConverter : IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | 默认构造函数。 |

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | 使用给定选项开始 PDF/A 转换或验证过程。 |

## Examples

该示例演示如何验证 PDF 文档是否符合 PDF/A 格式（在本例中为 PDF/A-1a）：

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

该示例演示如何将 PDF 文档转换为 PDF/A 格式（在本例中为 PDF/A-3b）：

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