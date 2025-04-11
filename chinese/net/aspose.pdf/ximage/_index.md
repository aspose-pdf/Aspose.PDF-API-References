---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImage 类。表示图像 XObject 的类
type: docs
weight: 11350
url: /zh/net/aspose.pdf/ximage/
---
## XImage class

表示图像 X-Object 的类。

```csharp
public sealed class XImage
```

## Properties

| Name | Description |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | 如果图像包含透明度，则返回 true；否则返回 false。 |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | 获取图像过滤器类型。 |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | 获取图像的灰度版本。 |
| [Height](../../aspose.pdf/ximage/height/) { get; } | 获取图像的高度。 |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | 获取一个标志，指示图像是否应被视为图像蒙版（请参见 8.9.6，“蒙版图像”）。如果此标志为 true，则 BitsPerComponent 的值应为 1，且 Mask 和 ColorSpace 不应被指定；未蒙版区域应使用当前非描边颜色进行绘制。默认值：false。 |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | 图像的元数据。 |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | 获取或设置图像名称。请注意，如果您更改了在页面内容中有引用的图像名称，文档可能会变得不正确。在这种情况下，请使用 XImage.Rename 方法。 |
| [Width](../../aspose.pdf/ximage/width/) { get; } | 获取图像的宽度。 |

## Methods

| Name | Description |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | 向 XImage 添加一个模板蒙版。 |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | 返回图像的颜色类型。 |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | 返回图像在其集合中的名称。 |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | 从源图像检索原始图像数据。 |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | 如果两个图像引用同一对象，则返回 true。 |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | 重命名图像并用新名称替换对图像的所有引用 |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | 将图像数据保存到流中作为 JPEG 图像。 |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | 以请求的格式将图像保存到流中。 |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | 以指定的分辨率将图像数据保存到流中作为 JPEG 图像。 |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | 以请求的格式和指定的分辨率将图像保存到流中。 |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | 返回原始图像流。 |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)