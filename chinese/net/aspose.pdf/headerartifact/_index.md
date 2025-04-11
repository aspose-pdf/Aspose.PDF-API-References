---
title: Class HeaderArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HeaderArtifact 类。该类描述了 Header 伪影。此伪影可用于设置页面的标题
type: docs
weight: 5420
url: /zh/net/aspose.pdf/headerartifact/
---
## HeaderArtifact 类

该类描述了 Header 伪影。此伪影可用于设置页面的标题。

```csharp
public class HeaderArtifact : Artifact
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HeaderArtifact](headerartifact/)() | 创建 Header Artifact 实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | 伪影的水平对齐方式。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | 伪影的垂直对齐方式。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | 伪影的底部边距。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | 获取伪影内部操作符的集合。 |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | 获取伪影子类型的名称。如果伪影子类型不是标准子类型，则可以使用。 |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | 获取伪影类型的名称。如果伪影类型是非标准的，则可以使用。 |
| [Form](../../aspose.pdf/artifact/form/) { get; } | 获取伪影的 XForm（如果使用 XForm）。 |
| [Image](../../aspose.pdf/artifact/image/) { get; } | 获取伪影的图像（如果存在）。 |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | 如果为 true，伪影将放置在页面内容后面。 |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | 伪影的左边距。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | 多行文本伪影的行。 |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | 获取或设置伪影的不透明度。可能的值范围为 0..1。 |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | 获取或设置伪影的位置。如果指定了此属性，则边距和对齐方式将被忽略。 |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | 获取伪影的矩形。 |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | 伪影的右边距。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | 获取或设置伪影的旋转角度。 |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | 获取伪影子类型。如果伪影具有非标准子类型，则可以通过 CustomSubtype 读取子类型的名称。 |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | 获取伪影的文本。 |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | 伪影文本的文本状态。 |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | 伪影的顶部边距。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | 获取伪影类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | 开始延迟更新。如果需要对同一伪影进行多次更改以提高性能，请使用此功能。通常，当伪影属性发生更改时，伪影操作符会随之更改。这会导致每次更改伪影时页面内容都会发生变化。为避免此效果，请将所有伪影更新放在 StartUpdates/SaveUpdates 调用之间。这允许仅更改一次页面内容。 |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | 处理伪影。 |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | 获取伪影的自定义值。 |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | 从伪影中移除自定义值。 |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | 保存在 BeginUpdates() 调用后对伪影所做的所有更新。 |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | 设置伪影的图像。 |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | 设置伪影的图像。 |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | 设置伪影的文本和文本属性。允许指定多行。 |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | 设置将被页面编号替换的字符串。默认值为 #。 |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | 设置作为伪影放置在文档页面上的 PDF 页面。 |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | 设置伪影的文本。 |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | 设置伪影的文本和文本属性。 |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | 设置伪影的自定义值。 |

### 另请参阅

* 类 [Artifact](../artifact/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)