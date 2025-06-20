---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ImageDevice class. An abstract class for image devices
type: docs
weight: 3730
url: /net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

An abstract class for image devices.

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Abstract initializer for `ImageDevice` descendants, set resolution to 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Initializes a new instance of the [`JpegDevice`](../jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Abstract initializer for `ImageDevice` descendants.  Resolution for the result image file, see [`Resolution`](./resolution/) class. |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Initializes a new instance of the [`JpegDevice`](../jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Initializes a new instance of the [`JpegDevice`](../jpegdevice/) class with provided image dimensions and resolution. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Initializes a new instance of the [`JpegDevice`](../jpegdevice/) class with provided image dimensions and resolution. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Perfoms some operation on the given page, e.g. converts page into graphic image. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


