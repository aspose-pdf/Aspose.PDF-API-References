---
title: RedactionAnnotation
second_title: Aspose.PDF for .NET API 参考
description: 表示密文注释
type: docs
weight: 960
url: /zh/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class

表示密文注释。

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RedactionAnnotation](redactionannotation#constructor)(Document) | RedactionAnnotation 的构造函数。用于生成器。 |
| [RedactionAnnotation](redactionannotation#constructor_1)(Page, Rectangle) | RedactAnnotation. 的构造函数 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | 获取注释操作列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | 获取注解的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | 获取或设置注释边框特征。[`Border`](../annotation/border) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor) { get; set; } | 获取或设置未激活编辑时绘制的边框颜色。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | 获取或设置注释颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | 获取或设置注释文本。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | 获取创建注释的日期和时间。 |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance) { get; set; } | 获取或设置用于格式化文本的默认外观字符串。 |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor) { get; set; } | 获取或设置颜色以填充注释。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | 获取注释的完整限定名。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | 获取或设置注解的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | 获取或设置片段超链接（用于pdf生成器）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | 对此注释“回复”的注释的引用。 两个注释必须在文档的同一页上。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。 默认为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置一个 bool 值，强制此段落在新页面生成。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | 获取或设置最近修改注释的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | 获取或设置页面注解名称。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | 获取或设置用于绘制注释的常量不透明度值。 |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext) { get; set; } | 在编辑注释上打印的文本。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | 获取包含注释的页面索引。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint) { get; set; } | 一个 8xN 数字的数组，指定要删除的内容区域的坐标。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | 获取或设置标注矩形。 |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat) { get; set; } | 如果为真，则将在注释上重复覆盖文本。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | 指定此批注 与 InReplyTo. 指定的关系（“回复类型”）的字符串 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | 获取或设置打开注解时在弹出窗口中显示的富文本字符串。 |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | 获取注解的外观字典。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | 获取表示对象描述的文本。 |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment) { get; set; } | 获取或设置。覆盖文本的对齐方式. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | 获取或设置应显示在注释标题栏中的文本。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | 获取或设置段落 的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | 获取或设置注解的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个 int 值，指示图形的 Z 顺序。 ZIndex 较大的图将放置在 ZIndex 较小的图上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中的文本后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept)(AnnotationSelector) | 接受访问者对象来处理注解。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | 根据矩阵变换更新参数和外观。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | 克隆此实例。 虚拟方法。总是返回 null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten)() | 展平注释，即删除注释并添加其 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | 考虑到页面旋转，返回注释矩形。 |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact)() | 展平注释并编辑页面内容（即删除编辑注释下的文本和图像） |

### 也可以看看

* class [MarkupAnnotation](../markupannotation)
* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
