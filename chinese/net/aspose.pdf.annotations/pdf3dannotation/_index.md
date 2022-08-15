---
title: PDF3DAnnotation
second_title: Aspose.PDF for .NET API 参考
description: 类 PDF3DAnnotation这个类不能被继承
type: docs
weight: 770
url: /zh/net/aspose.pdf.annotations/pdf3dannotation/
---
## PDF3DAnnotation class

类 PDF3DAnnotation。这个类不能被继承。

```csharp
public sealed class PDF3DAnnotation : Annotation
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PDF3DAnnotation](pdf3dannotation#constructor)(Page, Rectangle, PDF3DArtwork) | 初始化[`PDF3DAnnotation`](../pdf3dannotation)类. |
| [PDF3DAnnotation](pdf3dannotation#constructor_1)(Page, Rectangle, PDF3DArtwork, PDF3DActivation) | 初始化[`PDF3DAnnotation`](../pdf3dannotation)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | 获取注释操作列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/pdf3dannotation/annotationtype) { get; } | 获取注释类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | 获取注解的外观字典。 |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | 获取或设置注释边框特征。[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | 获取或设置注释颜色。 |
| [Content](../../aspose.pdf.annotations/pdf3dannotation/content) { get; set; } | 获取或设置内容。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | 获取或设置注释文本。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | 获取注释的完整限定名。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | 获取或设置注解的高度。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | 获取或设置片段超链接（用于pdf生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。 默认为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置一个 bool 值，强制此段落在新页面生成。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [LightingScheme](../../aspose.pdf.annotations/pdf3dannotation/lightingscheme) { get; } | 获取光照方案。 |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | 获取或设置最近修改注释的日期和时间。 |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | 获取或设置页面注解名称。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | 获取包含注释的页面索引。 |
| [Pdf3DArtwork](../../aspose.pdf.annotations/pdf3dannotation/pdf3dartwork) { get; } | 获取 3D 图稿。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | 获取或设置标注矩形。 |
| [RenderMode](../../aspose.pdf.annotations/pdf3dannotation/rendermode) { get; } | 获取渲染模式。 |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | 获取注解的外观字典。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | 获取或设置注释的文本对齐方式。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | 获取或设置段落 的垂直对齐方式 |
| [ViewArray](../../aspose.pdf.annotations/pdf3dannotation/viewarray) { get; } | 获取视图数组。 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | 获取或设置注解的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个 int 值，指示图形的 Z 顺序。 ZIndex 较大的图将放置在 ZIndex 较小的图上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中的文本后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/pdf3dannotation/accept)(AnnotationSelector) | 接受访问者进行注释处理。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | 根据矩阵变换更新参数和外观。 |
| [ClearImagePreview](../../aspose.pdf.annotations/pdf3dannotation/clearimagepreview)() | 清除图像预览。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | 克隆此实例。 虚拟方法。总是返回 null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | 将注释内容直接放在页面上， 注释对象将被移除。 |
| [GetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/getimagepreview)() | 获取图像预览。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | 考虑到页面旋转，返回注释矩形。 |
| [SetDefaultViewIndex](../../aspose.pdf.annotations/pdf3dannotation/setdefaultviewindex)(int) | 设置默认视图的索引。 |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview)(Stream) | 设置图像预览。 |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview_1)(string) | 设置图像预览。 |

### 也可以看看

* class [Annotation](../annotation)
* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
