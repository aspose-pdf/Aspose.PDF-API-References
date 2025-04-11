---
title: Aspose.Pdf.Vector
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector 是图形操作的根命名空间
type: docs
weight: 270
url: /zh/net/aspose.pdf.vector/
---
**Aspose.Pdf.Vector** 是图形操作的根命名空间。

## 类

| 类 | 描述 |
| --- | --- |
| [GraphicElement](./graphicelement/) | 表示页面上图形对象的基类。 |
| [GraphicElementCollection](./graphicelementcollection/) | 表示 [`GraphicElement`](../aspose.pdf.vector/graphicelement/) 集合。 |
| [GraphicsAbsorber](./graphicsabsorber/) | 表示图形元素的吸收器对象。执行图形搜索并通过 [`Elements`](../aspose.pdf.vector/graphicsabsorber/elements/) 集合提供对搜索结果的访问。 |
| [GraphicState](./graphicstate/) | 表示当前 [`GraphicElement`](../aspose.pdf.vector/graphicelement/) 的图形状态。 |
| [SubPath](./subpath/) | 表示页面上的矢量图形对象。基本上，矢量图形对象由两组 SubPaths 表示。其中一组由一组线条和曲线表示。其他则呈现为矩形，有时可能会混淆。通常这是一个具有颜色的矩形区域，但这个矩形通常位于页面的开头，并定义了整个页面的白色空间。因此，您获得了 SubPath，但在视觉上您只看到页面上的文本。 |
| [SubPathGroup](./subpathgroup/) | 表示一组图形元素容器的类。类对象具有一个边界框以考虑组的大小。 |
| [SvgExtractionOptions](./svgextractionoptions/) | 表示从 pdf 文档页面提取矢量图形的选项类。 |
| [SvgExtractor](./svgextractor/) | 表示从页面提取 SVG 图像的类。 |
| [XFormPlacement](./xformplacement/) | 表示 XForm 的放置。如果 XForm 在页面上显示超过 1 次，则与此 XForm 关联的所有 XformPlacements 将具有共同的图形元素，但具有不同的图形状态。 |