---
title: "类 PdfExtractor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.PdfExtractor 类。表示用于提取文本、图像及 PDF 文档页面上可能出现的其他类型内容的基础功能"
type: docs
weight: 9210
url: /zh/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

表示用于提取 PDF 文档页面上可能出现的文本、图像和其他类型内容的基础功能。

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | 实现 IDisposable。实际上，对 PdfExtractor 并非必要。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 使用指定参数启动 PdfExtractor 处理。 |

## 备注

使用 [`TextExtractor`](../textextractor/) 对象来提取文本，或使用 [`ImageExtractor`](../imageextractor/) 来提取图像。

## 示例

此示例演示如何提取 PDF 文档的文本内容。

```csharp
// 创建 TextExtractor 对象以提取 PDF 内容
using (TextExtractor extractor = new TextExtractor())
{
    // 创建 TextExtractorOptions 对象以设置指令。
    textExtractorOptions = new TextExtractorOptions();
    
    // 将输入文件路径添加到数据源
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // 执行提取过程
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // 从 ResultContainer 对象获取提取的文本
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


