---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CgmLoadOptions class. 包含将 CGM 文件加载/导入到 PDF 文档中的选项
type: docs
weight: 3010
url: /zh/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions class

包含将 CGM 文件加载/导入到 PDF 文档中的选项。

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | 创建用于将 CGM 文件转换为 PDF 文档的默认加载选项。默认 PDF 页面大小 - A4 300dpi 2480 X 3508。 |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | 创建具有定义的 !:pageSize 的加载选项。 |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以在加载文件时禁用所有字体的许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入 PDF 文档，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | 获取或设置导入的输出页面大小。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作将继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)