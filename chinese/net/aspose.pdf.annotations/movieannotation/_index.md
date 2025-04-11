---
title: Class MovieAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.MovieAnnotation 类。表示一个包含动画图形和声音的电影注释，以在计算机屏幕和扬声器上呈现。当注释被激活时，电影将播放。
type: docs
weight: 2110
url: /zh/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation 类

表示一个包含动画图形和声音的电影注释，以在计算机屏幕和扬声器上呈现。当注释被激活时，电影将播放。

```csharp
public sealed class MovieAnnotation : Annotation
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | 用于生成器的构造函数。 |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | 在指定页面上创建新的声音注释。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 获取注释动作的列表。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 获取或设置当前注释外观状态。 |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | 获取注释的类型。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 获取注释的外观字典。 |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | 获取或设置电影边界框的宽度和高度（以像素为单位）。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 获取或设置注释边框特征。 [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 获取注释特征。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 获取或设置注释颜色。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 获取或设置注释文本。 |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | 获取或设置一个文件规范，标识一个自描述的电影文件。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注释的标志。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 获取注释的完全限定名称。 |
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
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | 获取或设置一个标志或流，指定是否以及如何显示表示电影的海报图像。如果为 true，则海报图像将从电影文件中检索；如果为 false，则不显示海报。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 获取或设置注释矩形。 |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | 获取或设置电影相对于页面顺时针旋转的度数。该值应为 90 的倍数。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 获取注释的外观字典。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 获取或设置注释的文本对齐方式。 |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | 获取或设置电影注释的标题。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 获取或设置注释的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上方。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | 接受访问者对象以处理注释。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 根据矩阵变换更新参数和外观。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 克隆此实例。虚方法。始终返回 null。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 将注释内容直接放置在页面上，注释对象将被移除。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 返回考虑页面旋转的注释矩形。 |

### 另请参阅

* 类 [Annotation](../annotation/)
* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 程序集 [Aspose.PDF](../../)