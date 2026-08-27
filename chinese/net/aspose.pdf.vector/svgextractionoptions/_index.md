---
title: "类 SvgExtractionOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Vector.SvgExtractionOptions 类。表示用于从 pdf 文档页面提取矢量图形的选项类。"
type: docs
weight: 11430
url: /zh/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

表示用于从 pdf 文档页面提取矢量图形的选项类。

```csharp
public class SvgExtractionOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | 获取或设置自动将 subpaths 分组为图像的选项。此选项排除 [`GroupStrength`](./groupstrength/) 选项。 |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | 获取或设置将 PDF 文档中的每个 subpath 提取为单独 SVG 图像的选项。 |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | 获取或设置定义 SVG 提取区域的边界矩形。 |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | 获取或设置 subpaths 分组为图像的强度选项。允许您配置 subpaths 分组的程度。值范围为 0 到 1。值为 0 时对应启用 [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) 选项。值为 1 时将在页面上为所有矢量路径创建单个图像。当 [`AutoGrouping`](./autogrouping/) 为 false 时此选项生效。默认值为 `0.8`。 |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | 获取或设置生成的 SVG 中使用的最小笔画宽度。如果 PDF 使用更细的笔画宽度，将被此宽度替代。默认值为 0.5。 |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | 获取或设置一个选项，以严格检查 subpaths 是否位于 [`ExtractionAreaBound`](./extractionareabound/) 指定的矩形内。如果设为 false，则未完全包含在 [`ExtractionAreaBound`](./extractionareabound/) 内的 subpaths 仍会被提取。默认值为 `True`。 |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | 获取或设置一个标志，以确定页面上找到的 XFrom 是否应解包。XFrom 元素可能会出现在不同的 SVG 文件中。仅解包由页面内容中的 Do 语句渲染的 XForms。嵌套的 XForms 不会被解包。 |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | 获取或设置仅解包对应指定谓词的 XForm 的选项。 |

### 另请参见

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


