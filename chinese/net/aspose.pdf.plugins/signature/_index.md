---
title: "类 Signature"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.Signature 类。表示 Signature 插件"
type: docs
weight: 9410
url: /zh/net/aspose.pdf.plugins/signature/
---
## Signature class

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
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | 使用指定参数启动 `Signature` 处理。 |

## 示例

此示例演示如何对 PDF 文档进行签名。

```csharp
// 创建 Signature
var plugin = new Signature();
// 创建 SignOptions 对象以设置指令
var opt = new SignOptions(inputPfx, inputPfxPassword);
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath));
// 执行该过程
plugin.Process(opt);
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


