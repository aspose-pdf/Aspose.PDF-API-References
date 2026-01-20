---
title: Aspose::Pdf::Devices::ImageDevice class
linktitle: ImageDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::ImageDevice class. An abstract class for image devices in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.devices/imagedevice/
---
## ImageDevice class


An abstract class for image devices.

```cpp
class ImageDevice : public Aspose::Pdf::Devices::PageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [get_CoordinateType](./get_coordinatetype/)() const | Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Gets form presentation mode. |
| [get_Height](./get_height/)() const | Gets image output height. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Gets rendering options. |
| [get_Resolution](./get_resolution/)() const | Gets image resolution. |
| [get_Width](./get_width/)() const | Gets image output width. |
| [GetBitmap](./getbitmap/)(System::SharedPtr\<Page\>) | Converts the page into [Bitmap](../). |
| [ImageDevice](./imagedevice/)() | Abstract initializer for [ImageDevice](./) descendants, set resolution to 150x150. |
| [ImageDevice](./imagedevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Abstract initializer for [ImageDevice](./) descendants. |
| [ImageDevice](./imagedevice/)(int32_t, int32_t) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](./imagedevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](./imagedevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions and resolution. |
| [ImageDevice](./imagedevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions and resolution. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Sets form presentation mode. |
| [set_RenderingOptions](./set_renderingoptions/)(System::SharedPtr\<Aspose::Pdf::RenderingOptions\>) | Sets rendering options. |
## See Also

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
