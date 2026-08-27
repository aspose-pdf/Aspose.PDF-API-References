---
title: "类 ImagePlacement"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.ImagePlacement 类。表示放置在 Pdf document page 上的图像的特性"
type: docs
weight: 6030
url: /zh/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

表示放置在 PDF 文档页面上的图像特性。

```csharp
public sealed class ImagePlacement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | 获取放置在 page 上的图像所使用的图形状态的合成参数。 |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | 获取相关的 XImage 资源对象。 |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | 此图像的当前变换矩阵。 |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | 用于显示图像的操作符。 |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | 获取包含该图像的 page。 |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | 获取 rectangle of the 图像。 |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | 获取图像的分辨率。 |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | 获取图像的旋转角度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | 从页面中删除图像。 |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | 用另一张图像替换集合中的图像。 |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | 保存图像及其相应的转换：缩放、旋转和分辨率。 |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | 保存图像及其相应的转换：缩放、旋转和分辨率。 |

## 备注

当图像放置到页面时，其尺寸可能与[`Resources`](../resources/)中定义的物理尺寸不同。对象 `ImagePlacement` 用于提供诸如尺寸、分辨率等信息。

## 示例

此示例演示如何在第一个 PDF 文档页面上查找图像并获取具有可见尺寸的位图图像。

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
        // 从资源中检索图像
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // 创建具有实际尺寸的新位图
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


