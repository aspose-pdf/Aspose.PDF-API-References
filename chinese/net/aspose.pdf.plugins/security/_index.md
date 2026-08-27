---
title: "类 Security"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.Security 类。表示 Security 插件"
type: docs
weight: 9380
url: /zh/net/aspose.pdf.plugins/security/
---
## Security class

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
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | 使用指定的参数启动 `Security` 处理。 |

## 示例

示例演示如何加密 PDF document。

```csharp
// 创建 Security 
var plugin = new Security();
// 创建 EncryptionOptions 对象以设置指令
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath));
// 执行该过程
plugin.Process(opt);
```

示例演示如何解密 PDF document。

```csharp
// 创建 Security 
var plugin = new Security();
// 创建 DecryptionOptions 对象以设置指令
var opt = new DecryptionOptions("123456"));
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


