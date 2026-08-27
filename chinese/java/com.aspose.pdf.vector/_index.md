---
title: "com.aspose.pdf.vector"
linktitle: "com.aspose.pdf.vector"
second_title: "Aspose.PDF for Java API 参考"
description: "Aspose.Pdf.Vector 是用于图形操作的根命名空间。"
type: docs
weight: 390
url: /zh/java/com.aspose.pdf.vector/
---
Aspose.Pdf.Vector 是用于图形操作的根命名空间。

## 类

| 类 | 描述 |
| --- | --- |
| [GraphicElement](./graphicelement/) | 表示页面上图形对象的基类。 |
| [GraphicElementCollection](./graphicelementcollection/) | 表示 {@link GraphicElement} 集合。 |
| [GraphicsAbsorber](./graphicsabsorber/) | 表示图形元素的吸收器对象。执行图形搜索并通过 {@code GraphicsAbsorber.Elements}（{@link GraphicsAbsorber#getElements}）集合提供对搜索结果的访问。 |
| [GraphicState](./graphicstate/) | 表示当前 {@link GraphicElement} 的图形状态。 |
| [InternalHelper](./internalhelper/) |  |
| [SubPath](./subpath/) | 表示页面上的矢量图形对象。基本上，矢量图形对象由两组 SubPath 组成。其中一组由一系列直线和曲线表示。另一组表现为矩形，有时会被混淆。通常它是一个带颜色的矩形区域，但经常该矩形位于页面的起始位置，以白色定义整个页面的空间。因此你会得到 SubPath，但在视觉上只看到页面上的文本。 |
| [XFormPlacement](./xformplacement/) | 表示 XForm 的放置。如果 XForm 在页面上显示超过一次，则与该 XForm 关联的所有 XformPlacements 将拥有相同的图形元素，但图形状态不同。 |
