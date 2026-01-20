---
title: Aspose::Pdf::Devices::TiffSettings class
linktitle: TiffSettings
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::TiffSettings class. This class represents settings for importing pdf to Tiff in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf.devices/tiffsettings/
---
## TiffSettings class


This class represents settings for importing pdf to Tiff.

```cpp
class TiffSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Brightness](./get_brightness/)() const | Get or sets a value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or [ColorDepth.Format1bpp](../colordepth/) == 1. |
| [get_Compression](./get_compression/)() const | Gets the type of the compression. |
| [get_CoordinateType](./get_coordinatetype/)() const | Get or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [get_Depth](./get_depth/)() const | Gets the color depth. |
| [get_Margins](./get_margins/)() const | Gets the margins. |
| [get_Shape](./get_shape/)() const | Gets the type of the shape. |
| [get_SkipBlankPages](./get_skipblankpages/)() const | Gets a value indicating whether to skip blank pages. |
| [set_Brightness](./set_brightness/)(float) | Get or sets a value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or [ColorDepth.Format1bpp](../colordepth/) == 1. |
| [set_Compression](./set_compression/)(CompressionType) | Sets the type of the compression. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Get or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [set_Depth](./set_depth/)(ColorDepth) | Sets the color depth. |
| [set_Shape](./set_shape/)(ShapeType) | Sets the type of the shape. |
| [set_SkipBlankPages](./set_skipblankpages/)(bool) | Sets a value indicating whether to skip blank pages. |
| [TiffSettings](./tiffsettings/)() | Initializes a new instance of the [TiffSettings](./) class. |
| [TiffSettings](./tiffsettings/)(ShapeType) | Initializes a new instance of the [TiffSettings](./) class. |
| [TiffSettings](./tiffsettings/)(CompressionType) | Initializes a new instance of the [TiffSettings](./) class. |
| [TiffSettings](./tiffsettings/)(ColorDepth) | Initializes a new instance of the [TiffSettings](./) class. |
| [TiffSettings](./tiffsettings/)(System::SharedPtr\<Aspose::Pdf::Devices::Margins\>) | Initializes a new instance of the [TiffSettings](./) class. |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, System::SharedPtr\<Aspose::Pdf::Devices::Margins\>) | Initializes a new instance of the [TiffSettings](./) class. |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, System::SharedPtr\<Aspose::Pdf::Devices::Margins\>, bool) | Initializes a new instance of the [TiffSettings](./) class. |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, System::SharedPtr\<Aspose::Pdf::Devices::Margins\>, bool, ShapeType) | Initializes a new instance of the [TiffSettings](./) class. |
| [TiffSettings](./tiffsettings/)(bool) | Initializes a new instance of the [TiffSettings](./) class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
