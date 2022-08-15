---
title: InkAnnotation
second_title: Aspose.PDF for .NET API 参考
description: 表示由一个或多个不相交的路径组成的手绘涂鸦
type: docs
weight: 540
url: /zh/net/aspose.pdf.annotations/inkannotation/
---
## InkAnnotation class

表示由一个或多个不相交的路径组成的手绘“涂鸦”。

```csharp
public sealed class InkAnnotation : MarkupAnnotation
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [InkAnnotation](inkannotation#constructor)(Document, IList&lt;Point[]&gt;) | Generator. Ink 注释的构造函数 |
| [InkAnnotation](inkannotation#constructor_1)(Page, Rectangle, IList&lt;Point[]&gt;) | 在指定页面上创建新的 Ink 注释。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | 获取注释操作列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/inkannotation/annotationtype) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | 获取注解的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | 获取或设置注释边框特征。[`Border`](../annotation/border) |
| [CapStyle](../../aspose.pdf.annotations/inkannotation/capstyle) { get; set; } | 墨水注释行结尾的样式。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | 获取或设置注释颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | 获取或设置注释文本。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | 获取创建注释的日期和时间。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | 获取注释的完整限定名。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | 获取或设置注解的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | 获取或设置片段超链接（用于pdf生成器）。 |
| [InkList](../../aspose.pdf.annotations/inkannotation/inklist) { get; set; } | 获取或设置由 Point[] 数组表示的独立线条的手势列表。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | 对此注释“回复”的注释的引用。 两个注释必须在文档的同一页上。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。 默认为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置一个 bool 值，强制此段落在新页面生成。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | 获取或设置最近修改注释的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | 获取或设置页面注解名称。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | 获取或设置用于绘制注释的常量不透明度值。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | 获取包含注释的页面索引。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | 获取或设置标注矩形。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | 指定此批注 与 InReplyTo. 指定的关系（“回复类型”）的字符串 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | 获取或设置打开注解时在弹出窗口中显示的富文本字符串。 |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | 获取注解的外观字典。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | 获取表示对象描述的文本。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | 获取或设置应显示在注释标题栏中的文本。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | 获取或设置段落 的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | 获取或设置注解的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个 int 值，指示图形的 Z 顺序。 ZIndex 较大的图将放置在 ZIndex 较小的图上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中的文本后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/inkannotation/accept)(AnnotationSelector) | 接受访问者对象来处理注解。 |
| override [ChangeAfterResize](../../aspose.pdf.annotations/inkannotation/changeafterresize)(Matrix) | 根据矩阵变换更新 InkList 中的点。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | 克隆此实例。 虚拟方法。总是返回 null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | 将注释内容直接放在页面上， 注释对象将被移除。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | 考虑到页面旋转，返回注释矩形。 |

### 也可以看看

* class [MarkupAnnotation](../markupannotation)
* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
