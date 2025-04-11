---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacement 类。表示放置到 Pdf 文档页面的图像的特征
type: docs
weight: 5900
url: /zh/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

表示放置到 Pdf 文档页面的图像的特征。

```csharp
public sealed class ImagePlacement
```

## Properties

| Name | Description |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | 获取放置到页面的图像的图形状态的合成参数。 |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | 获取相关的 XImage 资源对象。 |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | 此图像的当前变换矩阵。 |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | 用于显示图像的操作符。 |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | 获取包含图像的页面。 |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | 获取图像的矩形。 |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | 获取图像的分辨率。 |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | 获取图像的旋转角度。 |

## Methods

| Name | Description |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | 从页面中删除图像。 |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | 用另一个图像替换集合中的图像。 |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | 以相应的变换保存图像：缩放、旋转和分辨率。 |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | 以相应的变换保存图像：缩放、旋转和分辨率。 |

## Remarks

当图像放置到页面时，它可能具有与 [`Resources`](../resources/) 中定义的物理尺寸不同的尺寸。对象 `ImagePlacement` 旨在提供诸如尺寸、分辨率等信息。

## Examples

该示例演示如何在第一个 PDF 文档页面上查找图像并以可见尺寸获取图像作为位图。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)