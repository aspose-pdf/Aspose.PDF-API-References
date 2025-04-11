---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Artifact 类。类表示 PDF Artifact 对象
type: docs
weight: 2770
url: /zh/net/aspose.pdf/artifact/
---
## Artifact 类

类表示 PDF Artifact 对象。

```csharp
public class Artifact : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | 带有指定类型和子类型的 artifact 的构造函数 |
| [Artifact](artifact/#constructor_1)(string, string) | 带有指定类型和子类型的 artifact 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | artifact 的水平对齐方式。如果位置在 Position 属性中被明确指定，则此值将被忽略。 |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | artifact 的垂直对齐方式。如果位置在 Position 属性中被明确指定，则此值将被忽略。 |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | artifact 的底部边距。如果位置在 Position 属性中被明确指定，则此值将被忽略。 |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | 获取 artifact 内部操作符的集合。 |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | 获取 artifact 子类型的名称。如果 artifact 子类型不是标准子类型，则可以使用。 |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | 获取 artifact 类型的名称。如果 artifact 类型是非标准的，则可以使用。 |
| [Form](../../aspose.pdf/artifact/form/) { get; } | 获取 artifact 的 XForm（如果使用 XForm）。 |
| [Image](../../aspose.pdf/artifact/image/) { get; } | 获取 artifact 的图像（如果存在）。 |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | 如果为 true，Artifact 将放置在页面内容后面。 |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | artifact 的左边距。如果位置在 Position 属性中被明确指定，则此值将被忽略。 |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | 多行文本 artifact 的行。 |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | 获取或设置 artifact 的不透明度。可能的值范围为 0..1。 |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | 获取或设置 artifact 位置。如果指定了此属性，则边距和对齐方式将被忽略。 |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | 获取 artifact 的矩形。 |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | artifact 的右边距。如果位置在 Position 属性中被明确指定，则此值将被忽略。 |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | 获取或设置 artifact 旋转角度。 |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | 获取 artifact 子类型。如果 artifact 具有非标准子类型，则可以通过 CustomSubtype 读取子类型的名称。 |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | 获取 artifact 的文本。 |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | artifact 文本的文本状态。 |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | artifact 的顶部边距。如果位置在 Position 属性中被明确指定，则此值将被忽略。 |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | 获取 artifact 类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | 开始延迟更新。如果需要对同一 artifact 进行多次更改以提高性能，请使用此功能。通常，当 artifact 属性发生更改时，artifact 操作符会随之更改。这会导致每次更改 artifact 时页面内容也发生变化。为了避免这种效果，请将所有 artifact 更新放在 StartUpdates/SaveUpdates 调用之间。这允许仅更改一次页面内容。 |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | 处理 artifact。 |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | 获取 artifact 的自定义值。 |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | 从 artifact 中移除自定义值。 |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | 保存在 BeginUpdates() 调用后对 artifact 所做的所有更新。 |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | 设置 artifact 的图像。 |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | 设置 artifact 的图像。 |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | 设置 artifact 的文本和文本属性。允许指定多行。 |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | 设置将被页面编号替换的字符串。默认值为 #。 |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | 设置作为 artifact 放置在文档页面上的 PDF 页面。 |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | 设置 artifact 的文本。 |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | 设置 artifact 的文本和文本属性。 |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | 设置 artifact 的自定义值。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | 可能的 artifact 子类型的枚举。 |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | 可能的 artifact 类型的枚举。 |

### 另请参阅

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)