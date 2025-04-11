---
title: Class ColorBarAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.ColorBarAnnotation 类。表示 ColorBarAnnotation 注释的类。属性 Color 被忽略，改为使用 ColorsOfCMYK 颜色。在创建时，宽度和高度的比例决定了注释的方向 - 水平或垂直。接下来，它检查注释矩形是否在 TrimBox 之外，如果不是，则根据注释的方向将其移动到 TrimBox 之外的最近位置。可以减少宽度（高度），以便注释适合 TrimBox 之外。如果布局没有空间，宽度/高度可以设置为零（在这种情况下，注释存在于页面上，但不显示）。
type: docs
weight: 1600
url: /zh/net/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class

表示 ColorBarAnnotation 注释的类。属性 Color 被忽略，改为使用 ColorsOfCMYK 颜色。在创建时，宽度和高度的比例决定了注释的方向 - 水平或垂直。接下来，它检查注释矩形是否在 TrimBox 之外，如果不是，则根据注释的方向将其移动到 TrimBox 之外的最近位置。可以减少宽度（高度），以便注释适合 TrimBox 之外。如果布局没有空间，宽度/高度可以设置为零（在这种情况下，注释存在于页面上，但不显示）。

```csharp
public sealed class ColorBarAnnotation : PrinterMarkAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [ColorBarAnnotation](colorbarannotation/)(Page, Rectangle, ColorsOfCMYK) | 在指定页面上创建新的 ColorBar 注释。 |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 获取注释操作的列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/colorbarannotation/annotationtype/) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 获取注释的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 获取或设置注释边框特征。 [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 获取或设置注释颜色。 |
| [ColorOfCMYK](../../aspose.pdf.annotations/colorbarannotation/colorofcmyk/) { get; set; } | 获取或设置注释绘制的颜色（青色、品红色、黄色、黑色之一）。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 获取或设置注释文本。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 获取注释的全名。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 获取或设置注释的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示该段落是否将在下一列。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制该段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 获取或设置注释最近修改的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 获取或设置页面上的注释名称。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 获取包含注释的页面索引。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 获取或设置注释矩形。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 获取注释的外观字典。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 获取或设置注释的文本对齐方式。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 获取或设置注释的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上方。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/colorbarannotation/accept/)(AnnotationSelector) | 接受访问者对象以处理注释。 |
| override [ChangeAfterResize](../../aspose.pdf.annotations/colorbarannotation/changeafterresize/)(Matrix) | 根据矩阵变换更新参数和外观，并在必要时移动到 TrimBox 之外。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 克隆此实例。虚拟方法。始终返回 null。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 将注释内容直接放置在页面上，注释对象将被移除。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 返回考虑页面旋转的注释矩形。 |

### See Also

* class [PrinterMarkAnnotation](../printermarkannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)