---
title: "类 ImageExtractor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.ImageExtractor 类。表示 ImageExtractor 插件"
type: docs
weight: 9020
url: /zh/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

表示 ImageExtractor 插件。

```csharp
public class ImageExtractor : PdfExtractor
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageExtractor](imageextractor/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | 实现 IDisposable。实际上，对 PdfExtractor 并非必要。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 使用指定参数启动 PdfExtractor 处理。 |

## 备注

`ImageExtractor` 对象用于提取 PDF 文档中的文本。

## 示例

此示例演示如何从 PDF 文档中提取图像。

```csharp
// 创建 ImageExtractor 对象以提取图像
using (ImageExtractor extractor = new ImageExtractor())
{
    // 创建 ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // 将输入文件路径添加到数据源
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // 执行提取过程
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // 从 ResultContainer 对象获取图像
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### 另请参见

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


