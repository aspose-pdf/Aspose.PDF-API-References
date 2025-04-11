---
title: Class RichMediaAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.RichMediaAnnotation 类。该类描述了 RichMediaAnnotation，它允许将视频/音频数据嵌入 PDF 文档中
type: docs
weight: 2480
url: /zh/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

该类描述了 RichMediaAnnotation，它允许将视频/音频数据嵌入 PDF 文档中。

```csharp
public class RichMediaAnnotation : Annotation
```

## Constructors

| Name | Description |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation/)(Page, Rectangle) | 初始化 RichMediaAnnotation。 |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 获取注释操作的列表。 |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon/) { get; set; } | 激活应用程序的事件。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype/) { get; } | 获取注释的类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 获取注释的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 获取或设置注释边框特征。 [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 获取或设置注释颜色。 |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content/) { get; } | Rich Media 内容的数据。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 获取或设置注释文本。 |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables/) { get; set; } | 设置或获取传递给播放器的 Flash 变量。 |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer/) { get; set; } | 设置或获取自定义 Flash 播放器以播放视频/音频数据。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 获取注释的完全限定名称。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 获取或设置注释的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示该段落是否将在下一列中。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制该段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 获取或设置注释最近修改的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 获取或设置页面上注释的名称。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 获取包含注释的页面索引。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 获取或设置注释矩形。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 获取注释的外观字典。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type/) { get; set; } | 获取或设置内容的类型。可能的值：音频，视频。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 获取或设置注释的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上方。ZIndex 可以为负值。具有负 ZIndex 的图形将放置在页面文本后面。 |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept/)(AnnotationSelector) | 接受此注释的访问者。 |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata/)(string, Stream) | 添加自定义命名数据（例如 Flash 脚本所需）。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 根据矩阵变换更新参数和外观。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 克隆此实例。虚方法。始终返回 null。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 将注释内容直接放置在页面上，注释对象将被移除。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 返回考虑页面旋转的注释矩形。 |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent/)(string, Stream) | 设置内容流。 |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter/)(Stream) | 设置注释的海报。 |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update/)() | 使用指定参数更新数据。 |

## Other Members

| Name | Description |
| --- | --- |
| enum [ActivationEvent](../../aspose.pdf.annotations/richmediaannotation.activationevent) | 激活注释的事件。 |
| enum [ContentType](../../aspose.pdf.annotations/richmediaannotation.contenttype) | 多媒体的类型。 |

### See Also

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)