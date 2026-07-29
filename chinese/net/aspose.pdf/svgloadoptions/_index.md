---
title: "类 SvgLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.SvgLoadOptions 类。表示将 SVG 文件加载/导入到 PDF Document 的选项"
type: docs
weight: 10390
url: /zh/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

表示将 SVG 文件加载/导入到 pdf 文档的选项。

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | 调整 PDF Page 大小以匹配 SVG 大小 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | 获取或设置在加载 Document 期间应应用的 Page 信息。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | 允许选择在转换期间使用的转换引擎。目前新引擎处于 B 测试阶段，因此此值默认设置为 ConversionEngines.LegacyEngine。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


