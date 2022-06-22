---
title: FreeTextAnnotation
second_title: Aspose.PDF for .NET API 参考
description: 表示直接在页面上显示文本的自由文本注释与普通文本注释不同自由文本注释没有打开或关闭状态文本始终可见而不是显示在弹出窗口中
type: docs
weight: 430
url: /zh/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

表示直接在页面上显示文本的自由文本注释。与普通文本注释不同，自由文本注释没有打开或关闭状态；文本始终可见，而不是显示在弹出窗口中。

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [FreeTextAnnotation](freetextannotation#constructor)(Document, DefaultAppearance) | 与生成器一起使用的构造函数。 |
| [FreeTextAnnotation](freetextannotation#constructor_1)(Page, Rectangle, DefaultAppearance) | 在指定页面上创建新的 FreeText 注释。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | 获取注释操作列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | 获取注解的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | 获取或设置注释边框特征。[`Border`](../annotation/border) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout) { get; set; } | 指定标注线的点数组。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | 获取或设置注释颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | 获取或设置注释文本。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | 获取创建注释的日期和时间。 |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance) { get; set; } | 获取或设置用于格式化文本的默认外观字符串。 |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject) { get; } | 对象，表示 FreeText 注释的默认外观。 |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle) { get; set; } | 获取或设置默认样式字符串。 |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle) { get; set; } | 获取或设置行结束点的行结束样式。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | 获取注解的完整限定名。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | 获取或设置注释的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | 获取或设置片段超链接（用于 pdf 生成器）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | 对此注解“回复”的注解的引用。 两个注释必须在文档的同一页上。 |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent) { get; set; } | 获取或设置自由文本注释的意图。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示该段落是否位于下一列。 默认为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置强制此段落在新页面生成的布尔值。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification) { get; set; } | 获取或设置一个代码，指定用于显示注释文本的四边形（对齐）形式。 |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | 获取或设置最近修改注释的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | 获取或设置页面上的注解名称。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | 获取或设置用于绘制注释的常量不透明度值。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | 获取包含注释的页面的索引。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | 获取或设置注释矩形。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | 一个字符串，指定此注释 与 InReplyTo 指定的关系（“回复类型”）。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | 获取或设置打开注释时在弹出窗口中显示的富文本字符串。 |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate) { get; set; } | 注释旋转角度。 |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle) { get; set; } | 获取或设置行结束点的行结束样式。 O此属性已过时，请使用 EndingStyle。 |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | 获取注解的外观字典。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | 获取表示对象描述的文本。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle) { get; set; } | 描述两个矩形之间数值差异的矩形:注释 的 Rect 条目和包含在该矩形中的矩形。内部矩形是应显示注释文本的位置。 |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle) { get; set; } | 获取或设置外观文本的样式。更改文本样式时，会更新文本外观。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | 获取或设置应显示在注释标题栏中的文本。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | 获取或设置注释的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个表示图形 Z 顺序的 int 值。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中文本的后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept)(AnnotationSelector) | 接受访问者对象来处理注释。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | 根据矩阵变换更新参数和外观。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | 克隆此实例。 虚方法。始终返回 null。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | 将注释内容直接放在页面上， 注释对象将被移除。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | 考虑到页面旋转，返回注释矩形。 |

### 也可以看看

* class [MarkupAnnotation](../markupannotation)
* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
