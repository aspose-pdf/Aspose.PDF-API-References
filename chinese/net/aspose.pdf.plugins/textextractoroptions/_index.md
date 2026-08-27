---
title: "类 TextExtractorOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.TextExtractorOptions 类。表示 TextExtractor 插件的文本提取选项。"
type: docs
weight: 9540
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
| [TextExtractorOptions](textextractoroptions/#constructor)() | 使用 'Raw'（默认）文本格式模式初始化 `TextExtractorOptions` 对象的新实例。 |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | 为指定的文本格式模式初始化 `TextExtractorOptions` 对象的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | 获取格式模式。 |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | 返回 PdfExtractor 插件的数据集合。 |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | 返回操作的名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | 向 PdfExtractor 插件的数据集合添加新的数据源。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | 定义在将 PDF 文档转换为文本时可使用的不同模式。参见 `TextExtractorOptions` 类。 |

## 备注

`TextExtractorOptions` 对象用于设置 [`TextFormattingMode`](../textextractoroptions.textformattingmode/) 以及文本提取操作的其他选项。同时，它继承了添加表示输入 PDF 文档的数据（文件、流）的功能。

## 示例

此示例演示如何提取 PDF 文档的文本内容。

```csharp
// 创建 TextExtractor 对象以提取 PDF 内容
using (TextExtractor extractor = new TextExtractor())
{
    // 创建 TextExtractorOptions 对象以设置 TextFormattingMode（Pure，或 Raw - 默认）
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // 将输入文件路径添加到数据源
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // 执行提取过程
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // 从 ResultContainer 对象获取提取的文本
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 另请参见

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


