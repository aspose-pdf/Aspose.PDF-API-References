---
title: "GifDevice Class"
linktitle: "GifDevice"
articleTitle: "GifDevice"
second_title: "Aspose.PDF for .NET"
description: "Represents image device that helps to save pdf document pages into gif."
type: docs
weight: 100
url: "/net/aspose.pdf.devices/gifdevice/"
keywords: "GifDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## GifDevice class

Represents image device that helps to save pdf document pages into gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [GifDevice](./gifdevice/#constructor) | Initializes a new instance of the [`GifDevice`](../../aspose.pdf.devices/gifdevice/) class with default resolution. |
| [GifDevice](./gifdevice/#constructor_1)(*[Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`GifDevice`](../../aspose.pdf.devices/gifdevice/) class. |
| [GifDevice](./gifdevice/#constructor_2)(*[PageSize](../../aspose.pdf/pagesize/)*) | Initializes a new instance of the [`GifDevice`](../../aspose.pdf.devices/gifdevice/) class with provided page size,. |
| [GifDevice](./gifdevice/#constructor_3)(*[PageSize](../../aspose.pdf/pagesize/), [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`GifDevice`](../../aspose.pdf.devices/gifdevice/) class with provided page size and. |
| [GifDevice](./gifdevice/#constructor_4)(*int, int*) | Initializes a new instance of the [`GifDevice`](../../aspose.pdf.devices/gifdevice/) class with provided image dimensions,. |
| [GifDevice](./gifdevice/#constructor_5)(*int, int, [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`GifDevice`](../../aspose.pdf.devices/gifdevice/) class with provided image dimensions and. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. *(Inherited from ImageDevice)* |
| [Document](../../aspose.pdf.devices/device/document/) { get; set; } | Document which is processed by this device instance. *(Inherited from Device)* |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. *(Inherited from ImageDevice)* |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Gets image output height. *(Inherited from ImageDevice)* |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Gets or sets rendering options. *(Inherited from ImageDevice)* |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Gets image resolution. *(Inherited from ImageDevice)* |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Gets image output width. *(Inherited from ImageDevice)* |

## Methods

| Name | Description |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(*Page*) | Converts the page into `Bitmap`. *(Inherited from ImageDevice)* |
| [Process](./process/)(*Page, Stream*) | Converts the page into gif and saves it in the output stream. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

