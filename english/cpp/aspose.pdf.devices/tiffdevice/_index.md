---
title: Aspose::Pdf::Devices::TiffDevice class
linktitle: TiffDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::TiffDevice class. This class helps to save pdf document page by page into the one tiff image in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class


This class helps to save pdf document page by page into the one tiff image.

```cpp
class TiffDevice : public Aspose::Pdf::Devices::DocumentDevice
```

## Methods

| Method | Description |
| --- | --- |
| [BinarizeBradley](./binarizebradley/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, double) | Do Bradley binarization for input stream. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Gets form presentation mode. |
| [get_Height](./get_height/)() const | Gets image output height. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Gets rendering options. |
| [get_Resolution](./get_resolution/)() const | Gets image resolution. |
| [get_Settings](./get_settings/)() const | Gets settings for mapping pdf into tiff image. |
| [get_Width](./get_width/)() const | Gets image output width. |
| [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) override | Converts certain document pages into tiff and save it in the output stream. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Perfoms some operation on the given page, e.g. converts page into graphic image. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Sets form presentation mode. |
| [set_RenderingOptions](./set_renderingoptions/)(System::SharedPtr\<Aspose::Pdf::RenderingOptions\>) | Sets rendering options. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, System::SharedPtr\<TiffSettings\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, System::SharedPtr\<TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<TiffSettings\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)() | Initializes a new instance of the [TiffDevice](./) class with default settings. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, System::SharedPtr\<TiffSettings\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, System::SharedPtr\<TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, System::SharedPtr\<TiffSettings\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, System::SharedPtr\<TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, System::SharedPtr\<TiffSettings\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, System::SharedPtr\<TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<TiffSettings\>) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t) | Initializes a new instance of the [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [TiffDevice](./) class. |
## See Also

* Class [DocumentDevice](../documentdevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
