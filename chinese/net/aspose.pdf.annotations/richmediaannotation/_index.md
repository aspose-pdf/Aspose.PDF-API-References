---
title: RichMediaAnnotation
second_title: Aspose.PDF for .NET API 参考
description: 类描述允许将视频/音频数据嵌入 PDF 文档的 RichMediaAnnotation
type: docs
weight: 1030
url: /zh/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

类描述允许将视频/音频数据嵌入 PDF 文档的 RichMediaAnnotation。

```csharp
public class RichMediaAnnotation : Annotation
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation)(Page, Rectangle) | 初始化 RichMediaAnnotation. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | 获取注释操作列表。 |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon) { get; set; } | 激活应用程序的事件。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | 获取注解的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | 获取或设置注释边框特征。[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | 获取或设置注释颜色。 |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content) { get; } | 富媒体内容的数据。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | 获取或设置注释文本。 |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables) { get; set; } | 设置或获取传递给播放器的闪存变量。 |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer) { get; set; } | 设置或获取自定义 Flash 播放器以播放视频/音频数据。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | 获取注释的完整限定名。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | 获取或设置注解的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | 获取或设置片段超链接（用于pdf生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。 默认为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置一个 bool 值，强制此段落在新页面生成。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | 获取或设置最近修改注释的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | 获取或设置页面注解名称。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | 获取包含注释的页面索引。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | 获取或设置标注矩形。 |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | 获取注解的外观字典。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type) { get; set; } | 获取或设置内容类型。可能的值：音频、视频。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | 获取或设置段落 的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | 获取或设置注解的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个 int 值，指示图形的 Z 顺序。 ZIndex 较大的图将放置在 ZIndex 较小的图上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中的文本后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept)(AnnotationSelector) | 接受此注释的访问者。 |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata)(string, Stream) | 添加自定义命名数据（例如 Flash 脚本所需）。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | 根据矩阵变换更新参数和外观。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | 克隆此实例。 虚拟方法。总是返回 null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | 将注释内容直接放在页面上， 注释对象将被移除。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | 考虑到页面旋转，返回注释矩形。 |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent)(string, Stream) | 设置内容流。 |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter)(Stream) | 设置注释的海报。 |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update)() | 使用指定参数更新数据。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| enum [ActivationEvent](richmediaannotation.activationevent) | 激活注释的事件。 |
| enum [ContentType](richmediaannotation.contenttype) | 多媒体类型。 |

### 也可以看看

* class [Annotation](../annotation)
* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
