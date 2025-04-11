---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Html 类。表示 Html 插件
type: docs
weight: 8820
url: /zh/net/aspose.pdf.plugins/html/
---
## Html 类

表示 `Html` 插件。

```csharp
public sealed class Html : IDisposable, IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Html](html/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | IDisposable 的实现。 |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | 使用指定参数开始 `Html` 处理。 |

## 示例

该示例演示如何将 PDF 转换为 HTML 文档。

```csharp
// create Html
var converter = new Html();
// create PdfToHtmlOptions object to set output data type as file with embedded resources
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

该示例演示如何将 HTML 转换为 PDF 文档。

```csharp
// create Html
var converter = new Html();
// create HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 另请参阅

* 接口 [IPlugin](../iplugin/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)