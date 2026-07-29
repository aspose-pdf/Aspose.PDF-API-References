---
title: "类 Html"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.Html 类。表示 Html 插件"
type: docs
weight: 8950
url: /zh/net/aspose.pdf.plugins/html/
---
## Html class

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
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | 实现 IDisposable。 |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | 使用指定的参数启动 `Html` 处理。 |

## 示例

示例演示如何将 PDF 转换为 HTML 文档。

```csharp
// 创建 Html
var converter = new Html();
// 创建 PdfToHtmlOptions 对象，以将输出数据类型设置为带嵌入资源的文件
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

示例演示如何将 HTML 转换为 PDF 文档。

```csharp
// 创建 Html
var converter = new Html();
// 创建 HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


