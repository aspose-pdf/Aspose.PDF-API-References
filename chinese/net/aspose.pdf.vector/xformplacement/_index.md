---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.XFormPlacement class. Represents XForm placement. If the XForm is displayed on the page more than 1 time all XformPlacements associated with this XForm will have common graphical elements but different graphical states
type: docs
weight: 11260
url: /zh/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

表示 XForm 的放置。如果 XForm 在页面上显示超过 1 次，则与此 XForm 关联的所有 XformPlacements 将具有共同的图形元素，但具有不同的图形状态。

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | 获取此 XForm 内的图形元素。 |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 获取图形元素矩阵。矩阵在元素创建时设置。当调用 SetPosition() 时会更改。 |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | 获取 XForm 的名称。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 获取表示元素的操作符集合。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 获取当前 `XFormPlacement`，其中包含该元素。 |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 获取提取图形元素的页面。 |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | 获取与此 XFormPlacement 关联的 XForm。 |

## Methods

| Name | Description |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | 将当前元素添加到页面。如果要添加多个元素，最好使用 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | 释放 [`GraphicElement`](../graphicelement/) 类使用的所有资源。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 从页面中移除当前元素。如果要移除多个元素，最好使用 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 将元素转换为单个 SVG 图像。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 将元素转换为单个 SVG 图像文件。 |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)