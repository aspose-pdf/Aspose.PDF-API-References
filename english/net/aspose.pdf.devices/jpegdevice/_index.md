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
| [JpegDevice](./jpegdevice/#constructor) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with default resolution and maximum quality. |
| [JpegDevice](./jpegdevice/#constructor_1)(*[Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class. |
| [JpegDevice](./jpegdevice/#constructor_2)(*int*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class. |
| [JpegDevice](./jpegdevice/#constructor_3)(*[PageSize](../../aspose.pdf/pagesize/)*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided page size,. |
| [JpegDevice](./jpegdevice/#constructor_4)(*[Resolution](../../aspose.pdf.devices/resolution/), int*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class. |
| [JpegDevice](./jpegdevice/#constructor_5)(*int, int*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions,. |
| [JpegDevice](./jpegdevice/#constructor_6)(*[PageSize](../../aspose.pdf/pagesize/), [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided page size,. |
| [JpegDevice](./jpegdevice/#constructor_7)(*int, int, [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions,. |
| [JpegDevice](./jpegdevice/#constructor_8)(*[PageSize](../../aspose.pdf/pagesize/), [Resolution](../../aspose.pdf.devices/resolution/), int*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided page size,. |
| [JpegDevice](./jpegdevice/#constructor_9)(*int, int, [Resolution](../../aspose.pdf.devices/resolution/), int*) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions,. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. *(Inherited from ImageDevice)* |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. *(Inherited from ImageDevice)* |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Gets image output height. *(Inherited from ImageDevice)* |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Gets or sets rendering options. *(Inherited from ImageDevice)* |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Gets image resolution. *(Inherited from ImageDevice)* |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Gets image output width. *(Inherited from ImageDevice)* |

## Methods

| Name | Description |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(*Page*) | Converts the page into `Bitmap`. *(Inherited from ImageDevice)* |
| [Process](./process/)(*Page, Stream*) | Converts the page into jpeg and saves it in the output stream. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

