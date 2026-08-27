---
title: "类 Merger"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.Merger 类。表示 Merger 插件"
type: docs
weight: 9070
url: /zh/net/aspose.pdf.plugins/merger/
---
## Merger class

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
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | 使用指定的参数启动 `Merger` 处理。 |

## 示例

此示例演示如何合并两个 PDF 文档。

```csharp
// 创建 Merger
var merger = new Merger();
// 创建 MergeOptions 对象以设置指令
var opt = new MergeOptions();
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath));
// 执行该过程
merger.Process(opt);
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


