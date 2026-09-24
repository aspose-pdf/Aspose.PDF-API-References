---
title: "PngDevice Class"
linktitle: "PngDevice"
articleTitle: "PngDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.PngDevice class. Represents image device that helps to save pdf document pages into png."
type: docs
weight: 150
url: "/net/aspose.pdf.devices/pngdevice/"
keywords: "PngDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PngDevice class

Represents image device that helps to save pdf document pages into png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [PngDevice](./pngdevice/#constructor) | Initializes a new instance of the [`PngDevice`](../../aspose.pdf.devices/pngdevice/) class with default resolution. |
| [PngDevice](./pngdevice/#constructor_1)(*[Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`PngDevice`](../../aspose.pdf.devices/pngdevice/) class. |
| [PngDevice](./pngdevice/#constructor_2)(*[PageSize](../../aspose.pdf/pagesize/)*) | Initializes a new instance of the [`PngDevice`](../../aspose.pdf.devices/pngdevice/) class with provided page size,. |
| [PngDevice](./pngdevice/#constructor_3)(*[PageSize](../../aspose.pdf/pagesize/), [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`PngDevice`](../../aspose.pdf.devices/pngdevice/) class with provided page size and. |
| [PngDevice](./pngdevice/#constructor_4)(*int, int*) | Initializes a new instance of the [`PngDevice`](../../aspose.pdf.devices/pngdevice/) class with provided image dimensions,. |
| [PngDevice](./pngdevice/#constructor_5)(*int, int, [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`PngDevice`](../../aspose.pdf.devices/pngdevice/) class with provided image dimensions and. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. *(Inherited from ImageDevice)* |
| [Document](../../aspose.pdf.devices/device/document/) { get; set; } | Document which is processed by this device instance. *(Inherited from Device)* |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. *(Inherited from ImageDevice)* |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Gets image output height. *(Inherited from ImageDevice)* |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Gets or sets rendering options. *(Inherited from ImageDevice)* |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Gets image resolution. *(Inherited from ImageDevice)* |
| [TransparentBackground](./transparentbackground/) { get; set; } | Gets or sets if image has transparent background. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Gets image output width. *(Inherited from ImageDevice)* |

## Methods

| Name | Description |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(*Page*) | Converts the page into `Bitmap`. *(Inherited from ImageDevice)* |
| [Process](./process/)(*Page, Stream*) | Converts the page into png and saves it in the output stream. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

