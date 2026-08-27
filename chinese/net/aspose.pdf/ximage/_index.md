---
title: "类 XImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.XImage 类。表示图像 XObject 的类。"
type: docs
weight: 11540
url: /zh/net/aspose.pdf/ximage/
---
## XImage class

表示图像 X-Object 的类。

```csharp
public sealed class XImage
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | 如果图像包含透明度则返回 true；否则返回 false。 |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | 获取图像过滤器类型。 |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | 获取图像的灰度版本。 |
| [Height](../../aspose.pdf/ximage/height/) { get; } | 获取图像的高度。 |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | 获取一个标志，指示图像是否应被视为图像遮罩（参见 8.9.6，“Masked Images”）。如果此标志为 true，则 BitsPerComponent 的值应为 1，且不应指定 Mask 和 ColorSpace；未遮罩的区域应使用当前非描边颜色进行绘制。默认值：false。 |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | 图像的元数据。 |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | 获取或设置图像名称。请注意，如果更改在页面内容中有引用的图像名称，文档可能会变得不正确。在这种情况下请使用 XImage.Rename 方法。 |
| [Width](../../aspose.pdf/ximage/width/) { get; } | 获取图像的宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | 向 XImage 添加模板遮罩。 |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | 返回一个包含 XImage 替代文本的字符串列表。 |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | 返回图像的颜色类型。 |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | 返回图像在其集合中的名称。 |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | 检索源图像的原始图像数据。 |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | 如果两个图像引用同一对象则返回 true。 |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | 重命名图像并将所有对该图像的引用替换为新名称。 |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | 将图像数据以 JPEG 图像形式保存到流中。 |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | 按请求的格式将图像保存到流中。 |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | 将图像数据以指定分辨率的 JPEG 图像形式保存到流中。 |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | 按请求的格式并使用指定分辨率将图像保存到流中。 |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | 返回原始图像流。 |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | 在页面上为 XImage 设置替代文本。 |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


