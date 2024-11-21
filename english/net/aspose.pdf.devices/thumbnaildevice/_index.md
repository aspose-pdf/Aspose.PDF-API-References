---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ThumbnailDevice class. Represents image device that save pdf document pages into Thumbnail image
type: docs
weight: 2360
url: /net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

Represents image device that save pdf document pages into Thumbnail image.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Initializes a new instance of the `ThumbnailDevice` class with default size of thumbnail image (200x200 pixels). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Initializes a new instance of the `ThumbnailDevice` class. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Gets image output height. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Gets image resolution. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Converts the page into thumbnail image png and saves it in the output stream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


