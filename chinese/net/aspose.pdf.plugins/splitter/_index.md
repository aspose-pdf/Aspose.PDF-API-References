---
title: "类 Splitter"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.Splitter 类。表示 Splitter 插件"
type: docs
weight: 9430
url: /zh/net/aspose.pdf.plugins/splitter/
---
## Splitter class

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
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | 使用指定的参数启动 `Splitter` 处理。 |

## 示例

此示例演示如何拆分 PDF 文档。

```csharp
// 创建 Splitter
var splitter = new Splitter();
// 创建 SplitOptions 对象以设置指令
var opt = new SplitOptions();
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// 执行该过程
splitter.Process(opt);
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


