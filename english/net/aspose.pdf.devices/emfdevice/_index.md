---
title: "EmfDevice Class"
linktitle: "EmfDevice"
articleTitle: "EmfDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.EmfDevice class. Represents image device that helps to save pdf document pages into emf."
type: docs
weight: 80
url: "/net/aspose.pdf.devices/emfdevice/"
keywords: "EmfDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## EmfDevice class

Represents image device that helps to save pdf document pages into emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfDevice](./emfdevice/#constructor)() | Initializes a new instance of the [`EmfDevice`](../../aspose.pdf.devices/emfdevice/) class with default resolution of raster image written to emf. |
| [EmfDevice](./emfdevice/#constructor_1)(PageSize) | Initializes a new instance of the [`EmfDevice`](../../aspose.pdf.devices/emfdevice/) class with provided page size, and default resolution for the raster image written to emf (=150) |
| [EmfDevice](./emfdevice/#constructor_2)(Resolution) | Initializes a new instance of the [`EmfDevice`](../../aspose.pdf.devices/emfdevice/) class. |
| [EmfDevice](./emfdevice/#constructor_3)(int, int) | Initializes a new instance of the [`EmfDevice`](../../aspose.pdf.devices/emfdevice/) class with provided image dimensions, and default resolution for the raster image written to emf (=150) |
| [EmfDevice](./emfdevice/#constructor_4)(PageSize, Resolution) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided page size, and resolution for the raster image written to emf. |
| [EmfDevice](./emfdevice/#constructor_5)(int, int, Resolution) | Initializes a new instance of the [`JpegDevice`](../../aspose.pdf.devices/jpegdevice/) class with provided image dimensions, and resolution for the raster image written to emf. |

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
| override [Process](./process/)(Page, Stream) | Converts the page into emf and saves it in the output stream. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

