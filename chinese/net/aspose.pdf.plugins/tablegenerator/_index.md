---
title: "类 TableGenerator"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.TableGenerator 类。表示 Aspose.PDF TableGenerator 插件。"
type: docs
weight: 9500
url: /zh/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

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
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | 实现 IDisposable。事实上，对 TableGenerator 并非必需。 |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | 使用指定参数启动 PdfGenerator 处理。 |

## 示例

示例演示如何向 PDF 文件添加表格。

```csharp
// 创建 TableGenerator
var generator = new TableGenerator();
// 创建 TableOptions 对象以设置指令
var opt = new TableOptions();
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


