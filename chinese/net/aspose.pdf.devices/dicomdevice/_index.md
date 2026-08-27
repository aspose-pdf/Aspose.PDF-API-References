---
title: "类 DicomDevice"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Devices.DicomDevice 类。表示帮助将 PDF 文档页面保存为 Dicom 格式的图像设备。"
type: docs
weight: 3680
url: /zh/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class

表示帮助将 PDF 文档页面保存为 Dicom 格式的图像设备。

```csharp
public sealed class DicomDevice : ImageDevice
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | 使用默认分辨率初始化 `DicomDevice` 类的新实例。 |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | 使用提供的页面大小和默认分辨率 (=150) 初始化 `DicomDevice` 类的新实例。 |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | 初始化 `DicomDevice` 类的新实例。结果图像文件的分辨率，请参阅 [`Resolution`](../resolution/) 类。 |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | 使用提供的图像尺寸和默认分辨率 (=150) 初始化 `DicomDevice` 类的新实例。 |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | 使用提供的页面尺寸和分辨率初始化 `DicomDevice` 类的新实例。 |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | 使用提供的图像尺寸和分辨率初始化 `DicomDevice` 类的新实例。 |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | 将页面转换为 Dicom 并将其保存到输出流中。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

### 另请参见

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


