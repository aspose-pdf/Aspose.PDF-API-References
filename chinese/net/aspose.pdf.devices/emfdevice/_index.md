---
title: EmfDevice
second_title: Aspose.PDF for .NET API 参考
description: 表示有助于将 pdf 文档页面保存到 emf 的图像设备
type: docs
weight: 1680
url: /zh/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

表示有助于将 pdf 文档页面保存到 emf 的图像设备。

```csharp
public sealed class EmfDevice : ImageDevice
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfDevice](emfdevice#constructor)() | 初始化[`EmfDevice`](../emfdevice)具有写入 emf. 的光栅图像默认分辨率的类 |
| [EmfDevice](emfdevice#constructor_2)(PageSize) | 初始化[`EmfDevice`](../emfdevice)具有提供的页面大小、 和写入 emf (=150) 的光栅图像的默认分辨率的类 |
| [EmfDevice](emfdevice#constructor_1)(Resolution) | 初始化[`EmfDevice`](../emfdevice)类.  写入 emf 的光栅图像的分辨率，请参见[`Resolution`](../resolution)类. |
| [EmfDevice](emfdevice#constructor_4)(int, int) | 初始化[`EmfDevice`](../emfdevice)具有提供的图像尺寸、 和写入 emf (=150) 的光栅图像的默认分辨率的类 |
| [EmfDevice](emfdevice#constructor_3)(PageSize, Resolution) | 初始化[`JpegDevice`](../jpegdevice)类具有提供的页面大小、 和写入 emf. 的光栅图像的分辨率 |
| [EmfDevice](emfdevice#constructor_5)(int, int, Resolution) | 初始化[`JpegDevice`](../jpegdevice)类具有提供的图像尺寸、 和写入 emf. 的光栅图像的分辨率 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | 获取或设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | 获取或设置表单展示模式。 |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | 获取图像输出高度。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | 获取图像分辨率。 |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | 获取图像输出宽度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/emfdevice/process#process)(Page, Stream) | 将页面转换为 emf 并保存在输出流中。 |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | 在给定页面上执行一些操作并将结果保存到文件中。 |

### 也可以看看

* class [ImageDevice](../imagedevice)
* 命名空间 [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->