---
title: "ThumbnailDevice Class"
linktitle: "ThumbnailDevice"
articleTitle: "ThumbnailDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.ThumbnailDevice class. Represents image device that save pdf document pages into Thumbnail image."
type: docs
weight: 190
url: "/net/aspose.pdf.devices/thumbnaildevice/"
keywords: "ThumbnailDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ThumbnailDevice class

Represents image device that save pdf document pages into Thumbnail image.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [ThumbnailDevice](./thumbnaildevice/#constructor) | Initializes a new instance of the [`ThumbnailDevice`](../../aspose.pdf.devices/thumbnaildevice/) class. |
| [ThumbnailDevice](./thumbnaildevice/#constructor_1)(*int, int*) | Initializes a new instance of the [`ThumbnailDevice`](../../aspose.pdf.devices/thumbnaildevice/) class. |

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
| [Process](./process/)(*Page, Stream*) | Converts the page into thumbnail image png and saves it in the output stream. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

