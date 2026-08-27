---
title: "类 LoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.LoadOptions 类。LoadOptions 类型保存对各个加载选项的抽象层级"
type: docs
weight: 6260
url: /zh/net/aspose.pdf/loadoptions/
---
## LoadOptions class

LoadOptions 类型在各个加载选项上保持抽象层次。

```csharp
public abstract class LoadOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 `LoadOptions` 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


