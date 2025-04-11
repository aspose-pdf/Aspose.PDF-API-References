---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractor 类。表示提取 PDF 文档页面上可能出现的文本、图像和其他类型内容的基本功能
type: docs
weight: 9060
url: /zh/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

表示提取 PDF 文档页面上可能出现的文本、图像和其他类型内容的基本功能。

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable 的实现。实际上，对于 PdfExtractor 来说并不是必需的。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 使用指定参数开始 PdfExtractor 处理。 |

## Remarks

[`TextExtractor`](../textextractor/) 对象用于提取文本，或 [`ImageExtractor`](../imageextractor/) 用于提取图像。

## Examples

该示例演示如何提取 PDF 文档的文本内容。

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)