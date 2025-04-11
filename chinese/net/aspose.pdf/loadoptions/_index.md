---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptions 类。LoadOptions 类型持有单个加载选项的抽象级别
type: docs
weight: 6120
url: /zh/net/aspose.pdf/loadoptions/
---
## LoadOptions 类

LoadOptions 类型持有单个加载选项的抽象级别

```csharp
public abstract class LoadOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志以禁用加载文件时对所有字体的任何许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入到 PDF 文档中，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 `LoadOptions` 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作将继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)