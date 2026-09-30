---
title: "BmpDevice Class"
linktitle: "BmpDevice"
articleTitle: "BmpDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.BmpDevice class. Represents image device that helps to save pdf document pages into bmp."
type: docs
weight: 20
url: "/net/aspose.pdf.devices/bmpdevice/"
keywords: "BmpDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## BmpDevice class

Represents image device that helps to save pdf document pages into bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [BmpDevice](./bmpdevice/#constructor)() | Initializes a new instance of the [`BmpDevice`](../../aspose.pdf.devices/bmpdevice/) class with default resolution. |
| [BmpDevice](./bmpdevice/#constructor_1)(PageSize) | Initializes a new instance of the [`BmpDevice`](../../aspose.pdf.devices/bmpdevice/) class with provided page size, default resolution (=150). |
| [BmpDevice](./bmpdevice/#constructor_2)(Resolution) | Initializes a new instance of the [`BmpDevice`](../../aspose.pdf.devices/bmpdevice/) class. |
| [BmpDevice](./bmpdevice/#constructor_3)(int, int) | Initializes a new instance of the [`BmpDevice`](../../aspose.pdf.devices/bmpdevice/) class with provided image dimensions, default resolution (=150). |
| [BmpDevice](./bmpdevice/#constructor_4)(PageSize, Resolution) | Initializes a new instance of the [`BmpDevice`](../../aspose.pdf.devices/bmpdevice/) class with provided page size and resolution. |
| [BmpDevice](./bmpdevice/#constructor_5)(int, int, Resolution) | Initializes a new instance of the [`BmpDevice`](../../aspose.pdf.devices/bmpdevice/) class with provided image dimensions and resolution. |

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
| override [Process](./process/)(Page, Stream) | Converts the page into bmp and saves it in the output stream. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

