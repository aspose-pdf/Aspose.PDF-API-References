---
title: "类 ImagePlacementAbsorber"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.ImagePlacementAbsorber 类。表示图像放置对象的吸收器。执行图像使用情况的搜索，并通过 ImagePlacements 集合提供对搜索结果的访问"
type: docs
weight: 6040
url: /zh/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

表示图像放置对象的吸收器。执行图像使用情况的搜索，并通过 [`ImagePlacements`](./imageplacements/) 集合提供对搜索结果的访问。

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
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | 获取以 [`ImagePlacement`](../imageplacement/) 对象呈现的图像放置出现的集合。 |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | 获取/设置解析操作集合的只读模式。这可能有助于防止内存不足异常。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | 在指定的 Document 上执行搜索。 |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | 在指定的 Page 上执行搜索。 |

## 备注

`ImagePlacementAbsorber` 对象主要用于图像搜索场景。搜索完成后，出现的项以 [`ImagePlacement`](../imageplacement/) 对象表示，这些对象包含在 [`ImagePlacements`](./imageplacements/) 集合中。[`ImagePlacement`](../imageplacement/) 对象提供对图像放置属性的访问：尺寸、分辨率等。图像的正向旋转是逆时针，而页面的正向旋转是顺时针。在这里，我们需要表示图像的旋转角度，因此需要从图像角度中减去页面角度。

## 示例

此示例演示如何在第一个 PDF 文档页面上查找图像并获取图像放置属性。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 ImagePlacementAbsorber 对象以执行图像放置搜索
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// 接受第一页的吸收器
doc.Pages[1].Accept(abs);

// 显示所有放置的图像放置属性
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

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


