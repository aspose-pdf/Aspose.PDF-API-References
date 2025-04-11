---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractor 类。表示 TextExtractor 插件
type: docs
weight: 9380
url: /zh/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

表示 TextExtractor 插件。

```csharp
public class TextExtractor : PdfExtractor
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractor](textextractor/)() | 默认构造函数。 |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable 的实现。实际上，对于 PdfExtractor 来说，这是不必要的。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 使用指定参数开始 PdfExtractor 处理。 |

## Remarks

`TextExtractor` 对象用于提取 PDF 文档中的文本。

## Examples

该示例演示如何提取 PDF 文档的文本内容。

```csharp
// create TextExtractor object to extract text in PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### See Also

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)