---
title: Aspose::Pdf::LowCode::TiffOptions class
linktitle: TiffOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::TiffOptions class. Represents Pdf to Tiff converter options for the Tiff plugin in C++.'
type: docs
weight: 8900
url: /cpp/aspose.pdf.lowcode/tiffoptions/
---
## TiffOptions class


Represents [Pdf](../../aspose.pdf/) to [Tiff](../tiff/) converter options for the [Tiff](../tiff/) plugin.

```cpp
class TiffOptions : public Aspose::Pdf::LowCode::PdfToImageOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_Brightness](./get_brightness/)() | Get or sets a value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1. |
| [get_Compression](./get_compression/)() | Gets the type of the compression. |
| [get_CoordinateType](./get_coordinatetype/)() | Get or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [get_Depth](./get_depth/)() | Gets the color depth. |
| [get_OperationName](./get_operationname/)() override | Returns name of the operation. |
| [get_SaveAsMultiPageTiff](./get_saveasmultipagetiff/)() const | Gets and sets flag that allows to save all pages in one multi-page tiff. |
| [get_Shape](./get_shape/)() | Gets the type of the shape. |
| [get_SkipBlankPages](./get_skipblankpages/)() | Gets a value indicating whether to skip blank pages. |
| [set_Brightness](./set_brightness/)(float) | Get or sets a value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1. |
| [set_Compression](./set_compression/)(Devices::CompressionType) | Sets the type of the compression. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Get or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [set_Depth](./set_depth/)(Devices::ColorDepth) | Sets the color depth. |
| [set_SaveAsMultiPageTiff](./set_saveasmultipagetiff/)(bool) | Gets and sets flag that allows to save all pages in one multi-page tiff. |
| [set_Shape](./set_shape/)(Devices::ShapeType) | Sets the type of the shape. |
| [set_SkipBlankPages](./set_skipblankpages/)(bool) | Sets a value indicating whether to skip blank pages. |
| [TiffOptions](./tiffoptions/)() | Initializes a new instance of the [TiffOptions](./) object. |
## See Also

* Class [PdfToImageOptions](../pdftoimageoptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
