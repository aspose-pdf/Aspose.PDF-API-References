---
title: "ImageDevice Class"
linktitle: "ImageDevice"
articleTitle: "ImageDevice"
second_title: "Aspose.PDF for .NET"
description: "An abstract class for image devices."
type: docs
weight: 110
url: "/net/aspose.pdf.devices/imagedevice/"
keywords: "ImageDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ImageDevice class

An abstract class for image devices.

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageDevice](./imagedevice/#constructor) | Abstract initializer for [`ImageDevice`](../../aspose.pdf.devices/imagedevice/) descendants, set resolution to 150x150. |
| [ImageDevice](./imagedevice/#constructor_1)(*[Resolution](../../aspose.pdf.devices/resolution/)*) | Abstract initializer for [`ImageDevice`](../../aspose.pdf.devices/imagedevice/) descendants. |
| [ImageDevice](./imagedevice/#constructor_2)(*[PageSize](../../aspose.pdf/pagesize/)*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](./imagedevice/#constructor_3)(*int, int*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](./imagedevice/#constructor_4)(*[PageSize](../../aspose.pdf/pagesize/), [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions and resolution. |
| [ImageDevice](./imagedevice/#constructor_5)(*int, int, [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions and resolution. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](./coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [Document](../../aspose.pdf.devices/device/document/) { get; set; } | Document which is processed by this device instance. *(Inherited from Device)* |
| [FormPresentationMode](./formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](./height/) { get; } | Gets image output height. |
| [RenderingOptions](./renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](./resolution/) { get; } | Gets image resolution. |
| [Width](./width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| [GetBitmap](./getbitmap/)(*Page*) | Converts the page into `Bitmap`. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(*Page, Stream*) | Perfoms some operation on the given page, e.g. converts page into graphic image. *(Inherited from PageDevice)* |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

