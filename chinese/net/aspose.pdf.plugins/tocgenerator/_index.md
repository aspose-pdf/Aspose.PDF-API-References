---
title: "类 TocGenerator"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.TocGenerator 类。表示 Aspose.PDF TocGenerator 插件"
type: docs
weight: 9580
url: /zh/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

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
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | 实现 IDisposable。事实上，对 TocGenerator 来说并非必需。 |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | 使用指定参数启动 PdfGenerator 处理。 |

## 示例

此示例演示如何向 PDF 文件添加目录（TOC）。

```csharp
// 创建 TocGenerator
var generator = new TocGenerator();
// 创建 TocOptions 对象以设置指令
var opt = new TocOptions();
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath));
// 执行提取过程
generator.Process(opt);
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


