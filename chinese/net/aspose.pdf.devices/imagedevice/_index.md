---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ImageDevice 类。图像设备的抽象类
type: docs
weight: 3610
url: /zh/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

图像设备的抽象类。

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | `ImageDevice` 子类的抽象初始化器，分辨率设置为 150x150。 |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | 使用提供的图像尺寸和默认分辨率（=150）初始化 [`JpegDevice`](../jpegdevice/) 类的新实例。 |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | `ImageDevice` 子类的抽象初始化器。结果图像文件的分辨率，请参见 [`Resolution`](./resolution/) 类。 |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | 使用提供的图像尺寸和默认分辨率（=150）初始化 [`JpegDevice`](../jpegdevice/) 类的新实例。 |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | 使用提供的图像尺寸和分辨率初始化 [`JpegDevice`](../jpegdevice/) 类的新实例。 |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | 使用提供的图像尺寸和分辨率初始化 [`JpegDevice`](../jpegdevice/) 类的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 获取图像输出高度。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 获取图像分辨率。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 获取图像输出宽度。 |

## Methods

| Name | Description |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | 对给定页面执行某些操作，例如将页面转换为图形图像。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)