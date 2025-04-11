---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TableGenerator 类。表示 Aspose.PDF TableGenerator 插件
type: docs
weight: 9350
url: /zh/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator 类

表示 Aspose.PDF TableGenerator 插件。

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TableGenerator](tablegenerator/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | IDisposable 的实现。实际上，对于 TableGenerator 来说并不是必需的。 |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | 使用指定参数开始 PdfGenerator 处理。 |

## 示例

该示例演示如何将表添加到 PDF 文件中。

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
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