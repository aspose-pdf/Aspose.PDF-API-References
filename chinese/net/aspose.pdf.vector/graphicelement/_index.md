---
title: "类 GraphicElement"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Vector.GraphicElement 类。表示页面上图形对象的基类"
type: docs
weight: 11370
url: /zh/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement class

表示页面上图形对象的基类。

```csharp
public abstract class GraphicElement : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 获取图形元素矩阵。矩阵在创建元素时设置，调用 SetPosition() 时会更改。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 获取表示该元素的运算符集合。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 获取元素所在的当前 [`XFormPlacement`](../xformplacement/)。 |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | 获取或设置当前坐标空间中的位置。如果 [`Parent`](./parent/) 不为 !:null，则该元素具有 xForm 坐标空间。 |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | 获取 `GraphicElement` 的边界矩形。 |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 获取提取图形元素的页面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | 在页面上添加当前元素。如果要添加的元素很多，最好使用 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | 释放 `GraphicElement` 类使用的所有资源。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 从页面中移除当前元素。如果要移除的元素很多，最好使用 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | 将元素转换为单个 SVG 图像。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | 将元素转换为单个 SVG 图像文件。 |

### 另请参见

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


