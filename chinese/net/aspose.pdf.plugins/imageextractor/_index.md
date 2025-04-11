---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ImageExtractor 类。表示 ImageExtractor 插件
type: docs
weight: 8890
url: /zh/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor 类

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
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable 的实现。实际上，对于 PdfExtractor 来说并不是必需的。 |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 使用指定参数开始 PdfExtractor 处理。 |

## 备注

`ImageExtractor` 对象用于提取 PDF 文档中的文本。

## 示例

该示例演示如何从 PDF 文档中提取图像。

```csharp
// create ImageExtractor object to extract images
using (ImageExtractor extractor = new ImageExtractor())
{
    // create ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // add input file path to data sources
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // get the image from the ResultContainer object
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### 另请参阅

* 类 [PdfExtractor](../pdfextractor/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)