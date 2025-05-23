---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FreeTextAnnotation 类。表示一个自由文本注释，直接在页面上显示文本。与普通文本注释不同，自由文本注释没有打开或关闭状态；文本始终可见，而不是在弹出窗口中显示。
type: docs
weight: 1810
url: /zh/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

表示一个自由文本注释，直接在页面上显示文本。与普通文本注释不同，自由文本注释没有打开或关闭状态；文本始终可见，而不是在弹出窗口中显示。

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | 用于生成器的构造函数。 |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | 在指定页面上创建新的自由文本注释。 |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 获取注释操作的列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 获取注释的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 获取或设置注释边框特征。 [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | 指定呼叫线的点数组。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 获取或设置注释颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 获取或设置注释文本。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | 获取注释创建的日期和时间。 |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | 获取或设置用于格式化文本的默认外观字符串。 |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | 表示自由文本注释的默认外观的对象。 |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | 获取或设置默认样式字符串。 |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | 获取或设置线条结束点的线条结束样式。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 获取注释的完全限定名称。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 获取或设置注释的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | 对此注释的“回复”注释的引用。两个注释必须在文档的同一页面上。 |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | 获取或设置自由文本注释的意图。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列中。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面上生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面上。默认值为 false。（用于 PDF 生成） |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | 获取或设置一个代码，指定用于显示注释文本的对齐方式（对齐）。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 获取或设置注释最近修改的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 获取或设置页面上注释的名称。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | 获取或设置用于绘制注释的常量不透明度值。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 获取包含注释的页面索引。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | 用于输入或编辑与此注释相关的文本的弹出注释。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 获取或设置注释矩形。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | 一个字符串，指定此注释与 InReplyTo 指定的注释之间的关系（“回复类型”）。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | 获取或设置在打开注释时在弹出窗口中显示的富文本字符串。 |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | 注释旋转的角度。 |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | 获取或设置线条结束点的线条结束样式。此属性已过时，请使用 EndingStyle。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 获取注释的外观字典。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | 获取表示对象描述的文本。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | 描述两个矩形之间数值差异的矩形：注释的 Rect 条目和包含在该矩形内的矩形。内部矩形是注释文本应显示的地方。 |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | 获取或设置外观中文本的样式。当文本样式更改时，文本外观会更新。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 获取或设置将在注释标题栏中显示的文本。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 获取或设置注释的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | 接受访问者对象以处理注释。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 根据矩阵变换更新参数和外观。 |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | 清除注释的状态和状态模型。例如，清除注释的审阅状态。注意，状态存储在其他具有状态和状态模型键的文本注释中。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 克隆此实例。虚拟方法。始终返回 null。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 将注释内容直接放置在页面上，注释对象将被移除。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 返回考虑页面旋转的注释矩形。 |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | 获取注释的状态。注意，状态存储在其他具有状态和状态模型键的文本注释中。 |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | 获取注释的状态模型。注意，状态存储在其他具有状态和状态模型键的文本注释中。 |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | 设置注释的标记和未标记状态。注意，状态存储在其他具有状态和状态模型键的文本注释中。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | 设置注释的审阅状态。标记和未标记状态被忽略，因为它们不属于审阅状态模型。状态由创建目标注释的用户设置。值取自目标注释的 Title 属性。注意，状态存储在其他具有状态和状态模型键的文本注释中。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | 设置注释的审阅状态。标记和未标记状态被忽略，因为它们不属于审阅状态模型。注意，状态存储在其他具有状态和状态模型键的文本注释中。 |

### See Also

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)