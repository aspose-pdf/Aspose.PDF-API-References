---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Splitter 类。表示分割器插件
type: docs
weight: 9280
url: /zh/net/aspose.pdf.plugins/splitter/
---
## 分割器类

表示 `Splitter` 插件。

```csharp
public class Splitter : IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Splitter](splitter/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | 使用指定参数开始 `Splitter` 处理。 |

## 示例

该示例演示如何拆分 PDF 文档。

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### 另请参阅

* 接口 [IPlugin](../iplugin/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)