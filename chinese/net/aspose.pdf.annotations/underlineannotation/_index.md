---
title: UnderlineAnnotation
second_title: Aspose.PDF for .NET API 参考
description: 表示在文档文本中显示为下划线的下划线注释
type: docs
weight: 1240
url: /zh/net/aspose.pdf.annotations/underlineannotation/
---
## UnderlineAnnotation class

表示在文档文本中显示为下划线的下划线注释。

```csharp
public sealed class UnderlineAnnotation : TextMarkupAnnotation
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [UnderlineAnnotation](underlineannotation)(Page, Rectangle) | 在指定页面上创建新的下划线注释。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | 获取注释操作列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/underlineannotation/annotationtype) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | 获取注解的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | 获取或设置注释边框特征。[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | 获取或设置注释颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | 获取或设置注释文本。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | 获取创建注释的日期和时间。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | 获取注解的完整限定名。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | 获取或设置注释的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | 获取或设置片段超链接（用于 pdf 生成器）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | 对此注解“回复”的注解的引用。 两个注释必须在文档的同一页上。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示该段落是否位于下一列。 默认为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置强制此段落在新页面生成的布尔值。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | 获取或设置最近修改注释的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | 获取或设置页面上的注解名称。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | 获取或设置用于绘制注释的常量不透明度值。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | 获取包含注释的页面的索引。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| [QuadPoints](../../aspose.pdf.annotations/textmarkupannotation/quadpoints) { get; set; } | 获取或设置指定 n 个四边形坐标的点数组。每个四边形包含注释下的文本中的一个单词或一组连续的单词。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | 获取或设置注释矩形。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | 一个字符串，指定此注释 与 InReplyTo 指定的关系（“回复类型”）。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | 获取或设置打开注释时在弹出窗口中显示的富文本字符串。 |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | 获取注解的外观字典。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | 获取表示对象描述的文本。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | 获取或设置应显示在注释标题栏中的文本。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | 获取或设置注释的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个表示图形 Z 顺序的 int 值。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中文本的后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/underlineannotation/accept)(AnnotationSelector) | 接受访问者对象来处理注释。 |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textmarkupannotation/changeafterresize)(Matrix) | 根据矩阵变换更新 QuadPoints。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | 克隆此实例。 虚方法。始终返回 null。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | 将注释内容直接放在页面上， 注释对象将被移除。 |
| [GetMarkedText](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtext)() | 获取标记注释下的文本作为字符串。 |
| [GetMarkedTextFragments](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtextfragments)() | 获取标记注释下的文本为[`TextFragmentCollection`](../../aspose.pdf.text/textfragmentcollection)。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | 考虑到页面旋转，返回注释矩形。 |

### 也可以看看

* class [TextMarkupAnnotation](../textmarkupannotation)
* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
