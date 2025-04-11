---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SvgExtractionOptions 类。表示用于从 PDF 文档页面提取矢量图形的选项类
type: docs
weight: 11240
url: /zh/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

表示用于从 PDF 文档页面提取矢量图形的选项类。

```csharp
public class SvgExtractionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | 获取和设置自动将子路径分组为图像的选项。此选项排除了 [`GroupStrength`](./groupstrength/) 选项。 |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | 获取和设置从 PDF 文档提取每个子路径到单独 SVG 图像的选项。 |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | 获取和设置定义 SVG 提取区域的边界矩形。 |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | 获取和设置将子路径分组为图像的强度选项。允许您配置子路径的分组程度。值范围从 0 到 1。值为 0 对应于启用 [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) 选项。值为 1 将为页面上的所有矢量路径创建单个图像。该选项在 [`AutoGrouping`](./autogrouping/) 为 false 时生效。默认值为 `0.8`。 |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | 获取或设置结果 SVG 中使用的最小笔划宽度。如果 PDF 使用更细的笔划宽度，将用此宽度替换。默认值为 0.5。 |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | 获取和设置一个选项，以严格检查子路径是否在 [`ExtractionAreaBound`](./extractionareabound/) 指定的矩形内。如果设置为 false，则不完全包含在 [`ExtractionAreaBound`](./extractionareabound/) 中的子路径将被提取。默认值为 `True`。 |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | 获取和设置一个标志，确定页面上找到的 XForm 是否应被解包。XForm 元素可能会出现在不同的 SVG 文件中。仅由页面内容的 Do 语句呈现的 XForms 会被解包。嵌套的 XForms 不会被解包。 |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | 获取和设置仅解包与指定谓词对应的 XForm 的选项。 |

### See Also

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)