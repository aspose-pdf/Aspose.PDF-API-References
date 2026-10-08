---
title: "TiffDevice Class"
linktitle: "TiffDevice"
articleTitle: "TiffDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.TiffDevice class. This class helps to save pdf document page by page into the one tiff image."
type: docs
weight: 200
url: "/net/aspose.pdf.devices/tiffdevice/"
keywords: "TiffDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## TiffDevice class

This class helps to save pdf document page by page into the one tiff image.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)(Resolution) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_3)(TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_5)() | Initializes a new instance of the `TiffDevice` class with default settings. |
| [TiffDevice](tiffdevice/#constructor_6)(int, int, Resolution, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_7)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_10)(int, int, Resolution) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, Resolution) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_14)(PageSize, TiffSettings, IIndexBitmapConverter) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_15)(PageSize, TiffSettings) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int) | Initializes a new instance of the `TiffDevice` class. |
| [TiffDevice](tiffdevice/#constructor_17)(PageSize) | Initializes a new instance of the `TiffDevice` class. |

## Properties

| Name | Description |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Gets image output height. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Gets image resolution. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Gets settings for mapping pdf into tiff image. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Gets image output width. |

## Methods

| Name | Description |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Do Bradley binarization for input stream. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Converts certain document pages into tiff and save it in the output stream. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_1)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Processes the whole document and saves results into stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Processes the whole document and saves results into file. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Processes certain pages of the document and saves results into file. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

### See Also

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

