---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgLoadOptions 类。表示将 SVG 文件加载/导入到 PDF 文档中的选项
type: docs
weight: 10210
url: /zh/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

表示将 SVG 文件加载/导入到 PDF 文档中的选项。

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | 调整 PDF 页面大小以适应 SVG 大小 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以在加载文件时禁用所有字体的许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入 PDF 文档，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | 获取或设置在加载文档时应应用的页面信息。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作将继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

## Fields

| Name | Description |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | 允许选择在转换过程中使用的转换引擎。目前新引擎处于 B 测试阶段，因此此值默认设置为 ConversionEngines.LegacyEngine |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)