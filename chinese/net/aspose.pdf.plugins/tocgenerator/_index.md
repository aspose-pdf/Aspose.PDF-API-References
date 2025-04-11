---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TocGenerator 类。表示 Aspose.PDF TocGenerator 插件
type: docs
weight: 9430
url: /zh/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator 类

表示 Aspose.PDF TocGenerator 插件。

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TocGenerator](tocgenerator/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | IDisposable 的实现。实际上，对于 TocGenerator 来说并不是必需的。 |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | 使用指定参数启动 PdfGenerator 处理。 |

## 示例

该示例演示如何将 TOC 添加到 PDF 文件中。

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### 另请参阅

* 接口 [IPlugin](../iplugin/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)