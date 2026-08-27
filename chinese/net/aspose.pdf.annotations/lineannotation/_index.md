---
title: "类 LineAnnotation"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.LineAnnotation 类。表示线注释的类。"
type: docs
weight: 2070
url: /zh/net/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class

表示线注释的类。

```csharp
public sealed class LineAnnotation : MarkupAnnotation
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LineAnnotation](lineannotation/#constructor)(Document, Point, Point) | 用于 Generator 的构造函数。 |
| [LineAnnotation](lineannotation/#constructor_1)(Page, Rectangle, Point, Point) | 在指定页面上创建新的 Line 注释。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 获取注释操作的列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 获取或设置当前 Annotation 外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/lineannotation/annotationtype/) { get; } | 获取 Annotation 的类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 获取 Annotation 的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 获取或设置注释边框特性。[`Border`](../annotation/border/) |
| [CaptionOffset](../../aspose.pdf.annotations/lineannotation/captionoffset/) { get; set; } | 获取或设置标题文本相对于其正常位置的偏移。 |
| [CaptionPosition](../../aspose.pdf.annotations/lineannotation/captionposition/) { get; set; } | 获取或设置注释标题的位置。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 获取 Annotation 特性。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 获取或设置 Annotation 颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 获取或设置 Annotation 文本。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | 获取注释创建的日期和时间。 |
| [Ending](../../aspose.pdf.annotations/lineannotation/ending/) { get; set; } | 获取或设置线的结束点。 |
| [EndingStyle](../../aspose.pdf.annotations/lineannotation/endingstyle/) { get; set; } | 获取或设置线结束点的结束样式。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Annotation 的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 获取 Annotation 的完全限定名称。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 获取或设置 Annotation 的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | 对该注释所 "回复" 的注释的引用。两个注释必须位于文档的同一页。 |
| [Intent](../../aspose.pdf.annotations/lineannotation/intent/) { get; set; } | 获取或设置线注释的意图。 |
| [InteriorColor](../../aspose.pdf.annotations/lineannotation/interiorcolor/) { get; set; } | 获取或设置注释的内部颜色。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成） |
| [LeaderLine](../../aspose.pdf.annotations/lineannotation/leaderline/) { get; set; } | 获取或设置引导线的长度。 |
| [LeaderLineExtension](../../aspose.pdf.annotations/lineannotation/leaderlineextension/) { get; set; } | 获取或设置引导线延伸的长度。 |
| [LeaderLineOffset](../../aspose.pdf.annotations/lineannotation/leaderlineoffset/) { get; set; } | 获取或设置引导线的偏移。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 pdf 生成） |
| [Measure](../../aspose.pdf.annotations/lineannotation/measure/) { get; set; } | 为此注释指定的测量单位。 |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 获取或设置 Annotation 最近修改的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 获取或设置 Page 上 Annotation 的名称。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | 获取或设置用于绘制注释的固定不透明度值。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 获取包含注释的页面索引。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 获取或设置注释矩形。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | 一个字符串，指定此注释与 InReplyTo 指定的注释之间的关系（即"reply type"）。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | 获取或设置一个富文本字符串，在打开注释时显示在弹出窗口中。 |
| [ShowCaption](../../aspose.pdf.annotations/lineannotation/showcaption/) { get; set; } | 获取或设置布尔标志，以确定内容是否必须显示为标题。 |
| [Starting](../../aspose.pdf.annotations/lineannotation/starting/) { get; set; } | 获取或设置线的起始点。 |
| [StartingStyle](../../aspose.pdf.annotations/lineannotation/startingstyle/) { get; set; } | 获取或设置线起始点的结束样式。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 获取 Annotation 的外观字典。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | 获取表示对象描述的文本。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 获取或设置 Annotation 的文本对齐方式。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 获取或设置一个文本标签，在注释的弹出窗口标题栏打开且激活时显示。此条目用于标识添加该注释的用户。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 获取或设置批注的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将位于 ZIndex 较小的图形之上。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本的后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/lineannotation/accept/)(AnnotationSelector) | 接受访问者以进行注释处理。 |
| override [ChangeAfterResize](../../aspose.pdf.annotations/lineannotation/changeafterresize/)(Matrix) | 根据矩阵变换更新起始点和结束点。 |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | 清除注释的状态和状态模型。例如，清除注释的审阅状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 克隆此实例。虚拟方法。始终返回 null。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 将注释内容直接放置在页面上，注释对象将被移除。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 返回考虑页面旋转后的批注矩形。 |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | 获取注释的状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | 获取注释的状态模型。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | 为注释设置已标记和未标记状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | 为注释设置审阅状态。已标记和未标记状态将被忽略，因为它们不属于 Review StateModel。该状态由创建目标注释的用户设置，值取自目标注释的 Title 属性。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | 为注释设置审阅状态。已标记和未标记状态将被忽略，因为它们不属于 Review StateModel。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |

### 另请参见

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


