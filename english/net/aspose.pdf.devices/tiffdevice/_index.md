---
title: "TiffDevice Class"
linktitle: "TiffDevice"
articleTitle: "TiffDevice"
second_title: "Aspose.PDF for .NET"
description: "This class helps to save pdf document page by page into the one tiff image."
type: docs
weight: 200
url: "/net/aspose.pdf.devices/tiffdevice/"
keywords: "TiffDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TiffDevice class

This class helps to save pdf document page by page into the one tiff image.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffDevice](./tiffdevice/#constructor) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class with default settings. |
| [TiffDevice](./tiffdevice/#constructor_1)(*[Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_2)(*[TiffSettings](../../aspose.pdf.devices/tiffsettings/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_3)(*[PageSize](../../aspose.pdf/pagesize/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_4)(*[Resolution](../../aspose.pdf.devices/resolution/), [TiffSettings](../../aspose.pdf.devices/tiffsettings/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_5)(*[TiffSettings](../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../aspose.pdf/iindexbitmapconverter/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_6)(*[PageSize](../../aspose.pdf/pagesize/), [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_7)(*[PageSize](../../aspose.pdf/pagesize/), [TiffSettings](../../aspose.pdf.devices/tiffsettings/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_8)(*int, int*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_9)(*[Resolution](../../aspose.pdf.devices/resolution/), [TiffSettings](../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../aspose.pdf/iindexbitmapconverter/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_10)(*[PageSize](../../aspose.pdf/pagesize/), [Resolution](../../aspose.pdf.devices/resolution/), [TiffSettings](../../aspose.pdf.devices/tiffsettings/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_11)(*int, int, [Resolution](../../aspose.pdf.devices/resolution/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_12)(*int, int, [TiffSettings](../../aspose.pdf.devices/tiffsettings/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_13)(*[PageSize](../../aspose.pdf/pagesize/), [TiffSettings](../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../aspose.pdf/iindexbitmapconverter/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_14)(*int, int, [Resolution](../../aspose.pdf.devices/resolution/), [TiffSettings](../../aspose.pdf.devices/tiffsettings/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_15)(*[PageSize](../../aspose.pdf/pagesize/), [Resolution](../../aspose.pdf.devices/resolution/), [TiffSettings](../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../aspose.pdf/iindexbitmapconverter/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_16)(*int, int, [TiffSettings](../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../aspose.pdf/iindexbitmapconverter/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |
| [TiffDevice](./tiffdevice/#constructor_17)(*int, int, [Resolution](../../aspose.pdf.devices/resolution/), [TiffSettings](../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../aspose.pdf/iindexbitmapconverter/)*) | Initializes a new instance of the [`TiffDevice`](../../aspose.pdf.devices/tiffdevice/) class. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.devices/device/document/) { get; set; } | Document which is processed by this device instance. *(Inherited from Device)* |
| [FormPresentationMode](./formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](./height/) { get; } | Gets image output height. |
| [RenderingOptions](./renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](./resolution/) { get; } | Gets image resolution. |
| [Settings](./settings/) { get; } | Gets settings for mapping pdf into tiff image. |
| [Width](./width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| [BinarizeBradley](./binarizebradley/)(*Stream, Stream, double*) | Do Bradley binarization for input stream. |
| [Process](./process/)(*Page, Stream*) |  |
| [Process](./process/)(*Document, int, int, Stream*) | Converts certain document pages into tiff and save it in the output stream. |

### See Also

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

