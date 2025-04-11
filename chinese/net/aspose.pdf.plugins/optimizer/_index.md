---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Optimizer 类。表示优化器插件
type: docs
weight: 8970
url: /zh/net/aspose.pdf.plugins/optimizer/
---
## 优化器类

表示 `Optimizer` 插件。

```csharp
public sealed class Optimizer : IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Optimizer](optimizer/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | 使用指定参数开始 `Optimizer` 处理。 |

## 示例

该示例演示如何优化 PDF 文档。

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### 另请参见

* 接口 [IPlugin](../iplugin/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)