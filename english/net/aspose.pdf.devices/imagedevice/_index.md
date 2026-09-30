---
title: "ImageDevice Class"
linktitle: "ImageDevice"
articleTitle: "ImageDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.ImageDevice class. An abstract class for image devices."
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
| [ImageDevice](./imagedevice/#constructor)() | Abstract initializer for [`ImageDevice`](../../aspose.pdf.devices/imagedevice/) descendants, set resolution to 150x150. |
| [ImageDevice](./imagedevice/#constructor_1)(PageSize) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](./imagedevice/#constructor_2)(Resolution) | Abstract initializer for [`ImageDevice`](../../aspose.pdf.devices/imagedevice/) descendants. |
| [ImageDevice](./imagedevice/#constructor_3)(int, int) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](./imagedevice/#constructor_4)(PageSize, Resolution) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions and resolution. |
| [ImageDevice](./imagedevice/#constructor_5)(int, int, Resolution) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions and resolution. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](./coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [FormPresentationMode](./formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](./height/) { get; } | Gets image output height. |
| [RenderingOptions](./renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](./resolution/) { get; } | Gets image resolution. |
| [Width](./width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| [GetBitmap](./getbitmap/)(Page) | Converts the page into `Bitmap`. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Perfoms some operation on the given page, e.g. converts page into graphic image. |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

