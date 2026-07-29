---
title: "类 ThumbnailDevice"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Devices.ThumbnailDevice 类。表示将 pdf 文档页面保存为 Thumbnail 图像的图像设备。"
type: docs
weight: 3810
url: /zh/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

表示将 PDF 文档页面保存为缩略图的图像设备。

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | 使用默认的缩略图大小（200x200 像素）初始化 `ThumbnailDevice` 类的新实例。 |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | 初始化 `ThumbnailDevice` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 获取图像输出高度。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 获取图像分辨率。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 获取图像输出宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | 将页面转换为位图。 |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | 将页面转换为缩略图 PNG 并将其保存到输出流中。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

### 另请参见

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


