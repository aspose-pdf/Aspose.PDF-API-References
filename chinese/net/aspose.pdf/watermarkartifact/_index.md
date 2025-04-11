---
title: Class WatermarkArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.WatermarkArtifact 类。该类描述水印工件。可以用于
type: docs
weight: 11310
url: /zh/net/aspose.pdf/watermarkartifact/
---
## WatermarkArtifact class

该类描述水印工件。可以用于

```csharp
public class WatermarkArtifact : Artifact
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WatermarkArtifact](watermarkartifact/)() | 创建水印工件的实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | 工件的水平对齐方式。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | 工件的垂直对齐方式。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | 工件的底部边距。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | 获取工件内部操作符的集合。 |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | 获取工件子类型的名称。如果工件子类型不是标准子类型，则可以使用。 |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | 获取工件类型的名称。如果工件类型是非标准的，则可以使用。 |
| [Form](../../aspose.pdf/artifact/form/) { get; } | 获取工件的 XForm（如果使用 XForm）。 |
| [Image](../../aspose.pdf/artifact/image/) { get; } | 获取工件的图像（如果存在）。 |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | 如果为 true，工件将放置在页面内容后面。 |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | 工件的左边距。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | 多行文本工件的行。 |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | 获取或设置工件的不透明度。可能的值范围为 0..1。 |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | 获取或设置工件的位置。如果指定了此属性，则边距和对齐方式将被忽略。 |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | 获取工件的矩形。 |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | 工件的右边距。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | 获取或设置工件的旋转角度。 |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | 获取工件子类型。如果工件具有非标准子类型，则可以通过 CustomSubtype 读取子类型的名称。 |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | 获取工件的文本。 |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | 工件文本的文本状态。 |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | 工件的顶部边距。如果位置在 Position 属性中明确指定，则此值将被忽略。 |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | 获取工件类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | 开始延迟更新。如果需要对同一工件进行多次更改以提高性能，请使用此功能。通常，当工件属性发生更改时，工件操作符会随之更改。这会导致每次更改工件时页面内容都会更改。为了避免这种效果，请将所有工件更新放在 StartUpdates/SaveUpdates 调用之间。这允许仅更改一次页面内容。 |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | 处理工件。 |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | 获取工件的自定义值。 |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | 从工件中删除自定义值。 |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | 保存在 BeginUpdates() 调用后对工件所做的所有更新。 |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | 设置工件的图像。 |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | 设置工件的图像。 |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | 设置工件的文本和文本属性。允许指定多行。 |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | 设置将被页面编号替换的字符串。默认值为 #。 |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | 设置作为工件放置在文档页面上的 PDF 页面。 |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | 设置工件的文本。 |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | 设置工件的文本和文本属性。 |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | 设置工件的自定义值。 |

### 另请参阅

* class [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)