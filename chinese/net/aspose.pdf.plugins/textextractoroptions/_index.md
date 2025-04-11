---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractorOptions 类。表示 TextExtractor 插件的文本提取选项
type: docs
weight: 9390
url: /zh/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

表示 TextExtractor 插件的文本提取选项。

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | 使用“原始”（默认）文本格式化模式初始化 `TextExtractorOptions` 对象的新实例。 |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | 为指定的文本格式化模式初始化 `TextExtractorOptions` 对象的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | 获取格式化模式。 |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | 返回 PdfExtractor 插件数据集合。 |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | 返回操作的名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | 向 PdfExtractor 插件数据集合添加新的数据源。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | 定义在将 PDF 文档转换为文本时可以使用的不同模式。请参见 `TextExtractorOptions` 类。 |

## 备注

`TextExtractorOptions` 对象用于设置 [`TextFormattingMode`](../textextractoroptions.textformattingmode/) 和文本提取操作的其他选项。此外，它继承了添加表示输入 PDF 文档的数据（文件、流）的功能。

## 示例

该示例演示如何提取 PDF 文档的文本内容。

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 另请参阅

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)