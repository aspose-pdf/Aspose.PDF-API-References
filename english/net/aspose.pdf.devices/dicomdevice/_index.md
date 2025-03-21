---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DicomDevice class. Represents image device that helps to save pdf document pages into Dicom format
type: docs
weight: 3560
url: /net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class

Represents image device that helps to save pdf document pages into Dicom format.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Initializes a new instance of the `DicomDevice` class with default resolution. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Initializes a new instance of the `DicomDevice` class with provided page size, with default resolution (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Initializes a new instance of the `DicomDevice` class.  Resolution for the result image file, see [`Resolution`](../resolution/) class. |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Initializes a new instance of the `DicomDevice` class with provided image dimensions, with default resolution (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Initializes a new instance of the `DicomDevice` class with provided page size and resolution. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Initializes a new instance of the `DicomDevice` class with provided image dimensions and resolution. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Converts the page into Dicom and saves it in the output stream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


