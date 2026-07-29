---
title: "类 Optimizer"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.Optimizer 类。表示 Optimizer 插件。"
type: docs
weight: 9120
url: /zh/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

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
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | 使用指定的参数启动 `Optimizer` 处理。 |

## 示例

示例演示如何优化 PDF 文档。

```csharp
// 创建 Optimizer
var optimizer = new Optimizer();
// 创建 OptimizeOptions 对象以设置指令
var opt = new OptimizeOptions();
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath));
// 执行该过程
optimizer.Process(opt);
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


