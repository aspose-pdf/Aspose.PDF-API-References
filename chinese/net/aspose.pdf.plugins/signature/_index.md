---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Signature 类。表示签名插件
type: docs
weight: 9260
url: /zh/net/aspose.pdf.plugins/signature/
---
## 签名类

表示 `Signature` 插件。

```csharp
public sealed class Signature : IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Signature](signature/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | 使用指定参数开始 `Signature` 处理。 |

## 示例

该示例演示如何签署 PDF 文档。

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### 另请参见

* 接口 [IPlugin](../iplugin/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)