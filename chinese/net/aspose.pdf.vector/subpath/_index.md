---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SubPath 类。表示页面上的矢量图形对象。基本上，矢量图形对象由两组 SubPaths 表示。其中一组由一组线条和曲线表示。另一组则呈现为矩形，有时可能会混淆。通常这是一个有颜色的矩形区域，但这个矩形通常位于页面的开头，并定义了整个页面的白色空间。因此，您获得了 SubPath，但在视觉上您只看到页面上的文本。
type: docs
weight: 11220
url: /zh/net/aspose.pdf.vector/subpath/
---
## SubPath class

表示页面上的矢量图形对象。基本上，矢量图形对象由两组 SubPaths 表示。其中一组由一组线条和曲线表示。另一组则呈现为矩形，有时可能会混淆。通常这是一个有颜色的矩形区域，但这个矩形通常位于页面的开头，并定义了整个页面的白色空间。因此，您获得了 SubPath，但在视觉上您只看到页面上的文本。

```csharp
public sealed class SubPath : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 获取图形元素矩阵。矩阵在元素创建时设置。当调用 SetPosition() 时，它会改变。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 获取表示元素的操作符集合。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 获取当前 [`XFormPlacement`](../xformplacement/) 中元素的位置。 |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | 获取或设置当前坐标空间中的位置。如果 [`Parent`](../graphicelement/parent/) 不是 !:null，则元素具有 xForm 坐标空间。 |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 获取提取图形元素的页面。 |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | 将当前元素添加到页面。如果要添加多个元素，最好使用 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | 释放 [`GraphicElement`](../graphicelement/) 类使用的所有资源。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 从页面中移除当前元素。如果要移除多个元素，最好使用 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 将元素转换为单个 SVG 图像。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 将元素转换为单个 SVG 图像文件。 |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)