---
title: "类 SubPath"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Vector.SubPath 类。表示页面上的矢量图形对象。基本上，矢量图形对象由两组 SubPaths 表示。其中一组由一系列直线和曲线组成，另一组以矩形形式呈现，有时会产生混淆。通常它是一个带颜色的矩形区域，但此矩形常常位于页面的开头，以白色定义整个页面的空间。因此你会得到 SubPath，但在视觉上只能看到页面上的文本。"
type: docs
weight: 11410
url: /zh/net/aspose.pdf.vector/subpath/
---
## SubPath class

表示页面上的矢量图形对象。基本上，矢量图形对象由两组 SubPath 组成。其中一组由一系列直线和曲线表示。另一组以矩形形式呈现，有时会产生混淆。通常它是具有颜色的矩形区域，但该矩形常常位于页面的起始位置，以白色定义页面的整个空间。因此你会得到 SubPath，但在视觉上只能看到页面上的文本。

```csharp
public sealed class SubPath : GraphicElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 获取图形元素矩阵。矩阵在创建元素时设置，调用 SetPosition() 时会更改。 |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 获取表示该元素的运算符集合。 |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 获取元素所在的当前 [`XFormPlacement`](../xformplacement/)。 |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | 获取或设置当前坐标空间中的位置。如果 [`Parent`](../graphicelement/parent/) 不为 null，则该元素具有 xForm 坐标空间。 |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 获取提取图形元素的页面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | 在页面上添加当前元素。如果要添加的元素很多，最好使用 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)。 |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | 释放 [`GraphicElement`](../graphicelement/) 类使用的所有资源。 |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 从页面中移除当前元素。如果要移除的元素很多，最好使用 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 将元素转换为单个 SVG 图像。 |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 将元素转换为单个 SVG 图像文件。 |

### 另请参见

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


