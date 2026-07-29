---
title: "类 TextExtractor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.TextExtractor 类。表示 TextExtractor 插件"
type: docs
weight: 9530
url: /zh/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

表示 TextExtractor 插件。

```csharp
public class TextExtractor : PdfExtractor
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextExtractor](textextractor/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | 实现 IDisposable。实际上，对 PdfExtractor 并非必要。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 使用指定参数启动 PdfExtractor 处理。 |

## 备注

`TextExtractor` 对象用于提取 PDF 文档中的文本。

## 示例

此示例演示如何提取 PDF 文档的文本内容。

```csharp
// 创建 TextExtractor 对象以提取 PDF 内容中的文本。
using (TextExtractor extractor = new TextExtractor())
{
    // 创建 TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // 将输入文件路径添加到数据源
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // 执行提取过程
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // 从 ResultContainer 对象获取提取的文本
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 另请参见

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


