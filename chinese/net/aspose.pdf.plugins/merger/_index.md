---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Merger 类。表示合并插件
type: docs
weight: 8940
url: /zh/net/aspose.pdf.plugins/merger/
---
## 合并类

表示 `Merger` 插件。

```csharp
public sealed class Merger : IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Merger](merger/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | 使用指定参数开始 `Merger` 处理。 |

## 示例

该示例演示如何合并两个 PDF 文档。

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### 另请参阅

* 接口 [IPlugin](../iplugin/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)