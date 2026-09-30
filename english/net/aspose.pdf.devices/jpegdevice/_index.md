---
title: "JpegDevice Class"
linktitle: "JpegDevice"
articleTitle: "JpegDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.JpegDevice class. Represents image device that helps to save pdf document pages into jpeg."
type: docs
weight: 120
url: "/net/aspose.pdf.devices/jpegdevice/"
keywords: "JpegDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## JpegDevice class

Represents image device that helps to save pdf document pages into jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegDevice](./jpegdevice/#constructor)() | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with default resolution and maximum quality. |
| [JpegDevice](./jpegdevice/#constructor_1)(int) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class. |
| [JpegDevice](./jpegdevice/#constructor_2)(PageSize) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided page size, default resolution (=150) and maximum quality. |
| [JpegDevice](./jpegdevice/#constructor_3)(Resolution) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class. |
| [JpegDevice](./jpegdevice/#constructor_4)(int, int) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions, default resolution (=150) and maximum quality. |
| [JpegDevice](./jpegdevice/#constructor_5)(PageSize, Resolution) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided page size, resolution and maximum quality. |
| [JpegDevice](./jpegdevice/#constructor_6)(Resolution, int) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class. |
| [JpegDevice](./jpegdevice/#constructor_7)(int, int, Resolution) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions, resolution and maximum quality. |
| [JpegDevice](./jpegdevice/#constructor_8)(PageSize, Resolution, int) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided page size, resolution and quality. |
| [JpegDevice](./jpegdevice/#constructor_9)(int, int, Resolution, int) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions, resolution and quality. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Gets image output height. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Gets image resolution. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Converts the page into `Bitmap`. |
| override [Process](./process/)(Page, Stream) | Converts the page into jpeg and saves it in the output stream. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

