---
title: "类 XFormPlacement"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Vector.XFormPlacement 类。表示 XForm 的放置。如果 XForm 在页面上显示超过一次，所有与该 XForm 关联的 XformPlacement 将具有相同的图形元素，但图形状态不同。"
type: docs
weight: 11450
url: /zh/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

表示 XForm 的放置。如果 XForm 在页面上显示超过一次，则与该 XForm 关联的所有 XformPlacements 将拥有相同的图形元素，但图形状态不同。

```csharp
public sealed class XFormPlacement : GraphicElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | 获取此 XForm 内的图形元素。 |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 获取图形元素矩阵。矩阵在创建元素时设置，调用 SetPosition() 时会更改。 |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | 获取 XForm 的名称。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 获取表示该元素的运算符集合。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 获取元素所在的当前 `XFormPlacement`。 |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 获取提取图形元素的页面。 |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | 获取与此 XFormPlacement 关联的 XForm。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | 在页面上添加当前元素。如果要添加的元素很多，最好使用 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | 释放 [`GraphicElement`](../graphicelement/) 类使用的所有资源。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 从页面中移除当前元素。如果要移除的元素很多，最好使用 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 将元素转换为单个 SVG 图像。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 将元素转换为单个 SVG 图像文件。 |

### 另请参见

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


