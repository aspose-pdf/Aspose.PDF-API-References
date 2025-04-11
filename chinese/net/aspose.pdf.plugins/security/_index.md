---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Security 类。表示安全插件
type: docs
weight: 9230
url: /zh/net/aspose.pdf.plugins/security/
---
## 安全类

表示 `Security` 插件。

```csharp
public sealed class Security : IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Security](security/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | 使用指定参数开始 `Security` 处理。 |

## 示例

该示例演示如何加密 PDF 文档。

```csharp
// create Security 
var plugin = new Security();
// create EncryptionOptions object to set instructions
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

该示例演示如何解密 PDF 文档。

```csharp
// create Security 
var plugin = new Security();
// create DecryptionOptions object to set instructions
var opt = new DecryptionOptions("123456"));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### 另请参阅

* 接口 [IPlugin](../iplugin/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)