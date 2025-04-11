---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacementAbsorber 类。表示图像放置对象的吸收器对象。执行图像使用情况的搜索，并通过 ImagePlacements 集合提供对搜索结果的访问
type: docs
weight: 5910
url: /zh/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber 类

表示图像放置对象的吸收器对象。执行图像使用情况的搜索，并通过 [`ImagePlacements`](./imageplacements/) 集合提供对搜索结果的访问。

```csharp
public sealed class ImagePlacementAbsorber
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | 获取以 [`ImagePlacement`](../imageplacement/) 对象表示的图像放置发生的集合。 |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | 获取/设置用于解析操作集合的只读模式。它可能有助于防止内存溢出异常。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | 在指定文档上执行搜索。 |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | 在指定页面上执行搜索。 |

## 备注

`ImagePlacementAbsorber` 对象基本上用于图像搜索场景。当搜索完成时，发生的情况由 [`ImagePlacement`](../imageplacement/) 对象表示，[`ImagePlacements`](./imageplacements/) 集合包含这些对象。[`ImagePlacement`](../imageplacement/) 对象提供对图像放置属性的访问：尺寸、分辨率等。图像的正向旋转是逆时针的，对于页面，则是顺时针的。在这里，我们需要表示图像旋转角度，因此我们从图像角度中减去页面角度。

## 示例

该示例演示如何在第一个 PDF 文档页面上查找图像并获取图像放置属性。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)