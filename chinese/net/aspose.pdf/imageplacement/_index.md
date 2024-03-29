---
title: ImagePlacement
second_title: Aspose.PDF for .NET API 参考
description: 表示放置到 Pdf 文档页面的图像的特征
type: docs
weight: 3760
url: /zh/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

表示放置到 Pdf 文档页面的图像的特征。

```csharp
public sealed class ImagePlacement
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters) { get; } | 获取放置到页面上的图像的活动图形状态的合成参数。 |
| [Image](../../aspose.pdf/imageplacement/image) { get; } | 获取相关的XImage资源对象。 |
| [Matrix](../../aspose.pdf/imageplacement/matrix) { get; } | 此图像的当前变换矩阵。 |
| [Operator](../../aspose.pdf/imageplacement/operator) { get; } | 用于显示图像的运算符。 |
| [Page](../../aspose.pdf/imageplacement/page) { get; } | 获取包含图像的页面。 |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle) { get; } | 获取图像的矩形。 |
| [Resolution](../../aspose.pdf/imageplacement/resolution) { get; } | 获取图像的分辨率。 |
| [Rotation](../../aspose.pdf/imageplacement/rotation) { get; } | 获取图像的旋转角度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide)() | 从页面中删除图像。 |
| [Replace](../../aspose.pdf/imageplacement/replace)(Stream) | 用另一个图像替换集合中的图像。 |
| [Save](../../aspose.pdf/imageplacement/save#save)(Stream) | 保存带有相应变换的图像：缩放、旋转和分辨率。 |
| [Save](../../aspose.pdf/imageplacement/save#save_1)(Stream, ImageFormat) | 保存带有相应变换的图像：缩放、旋转和分辨率。 |

### 评论

当图像被放置到页面时，它可能具有不同于定义的物理尺寸的尺寸[`Resources`](../resources). 对象[`ImagePlacement`](../imageplacement)旨在提供尺寸、分辨率等信息。

### 例子

该示例演示如何在第一个 PDF 文档页面上查找图像并将图像作为具有可见尺寸的位图获取。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 ImagePlacementAbsorber 对象以执行图像放置搜索
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// 接受第一页的吸收器
doc.Pages[1].Accept(abs);

// 检索具有可见尺寸的图像
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // 从资源中获取图片
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // 创建具有实际尺寸的新位图
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### 也可以看看

* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
