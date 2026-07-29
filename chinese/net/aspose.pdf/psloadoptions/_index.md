---
title: "类 PsLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PsLoadOptions 类。表示加载/导入 .mhtfile 到 pdf 文档的选项。"
type: docs
weight: 9880
url: /zh/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

表示将 .mht 文件加载/导入到 pdf 文档的选项。

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | 指定是否将非 TrueType 字体保存为 TTF。它显著降低 PS 转 PDF 转换后文档的体积，并提高在非 TrueType 字体文本量大的 PS 文件转换为任何输出格式的速度。然而，在将 PostSctipt 文件转换为图像时会出现轻微的垂直文字位移。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | 获取或设置字体文件夹路径。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


