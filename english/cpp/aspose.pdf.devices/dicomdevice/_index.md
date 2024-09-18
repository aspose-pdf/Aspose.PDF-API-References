---
title: Aspose::Pdf::Devices::DicomDevice class
linktitle: DicomDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::DicomDevice class. Represents image device that helps to save pdf document pages into Dicom format in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class


Represents image device that helps to save pdf document pages into Dicom format.

```cpp
class DicomDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [DicomDevice](./dicomdevice/)() | Initializes a new instance of the [DicomDevice](./) class with default resolution. |
| [DicomDevice](./dicomdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [DicomDevice](./) class. |
| [DicomDevice](./dicomdevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [DicomDevice](./) class with provided page size, with default resolution (=150). |
| [DicomDevice](./dicomdevice/)(int32_t, int32_t) | Initializes a new instance of the [DicomDevice](./) class with provided image dimensions, with default resolution (=150). |
| [DicomDevice](./dicomdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [DicomDevice](./) class with provided page size and resolution. |
| [DicomDevice](./dicomdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [DicomDevice](./) class with provided image dimensions and resolution. |
| [get_CoordinateType](../imagedevice/get_coordinatetype/)() const | Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [get_FormPresentationMode](../imagedevice/get_formpresentationmode/)() const | Gets form presentation mode. |
| [get_Height](../imagedevice/get_height/)() const | Gets image output height. |
| [get_RenderingOptions](../imagedevice/get_renderingoptions/)() const | Gets rendering options. |
| [get_Resolution](../imagedevice/get_resolution/)() const | Gets image resolution. |
| [get_Width](../imagedevice/get_width/)() const | Gets image output width. |
| [ImageDevice](../imagedevice/imagedevice/)() | Abstract initializer for [ImageDevice](../imagedevice/) descendants, set resolution to 150x150. |
| [ImageDevice](../imagedevice/imagedevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Abstract initializer for [ImageDevice](../imagedevice/) descendants. |
| [ImageDevice](../imagedevice/imagedevice/)(int32_t, int32_t) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](../imagedevice/imagedevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions and default resolution (=150). |
| [ImageDevice](../imagedevice/imagedevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions and resolution. |
| [ImageDevice](../imagedevice/imagedevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions and resolution. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Converts the page into Dicom and saves it in the output stream. |
| [Process](../pagedevice/process/)(System::SharedPtr\<Page\>, System::String) | Perfoms some operation on the given page and saves results into the file. |
| [set_CoordinateType](../imagedevice/set_coordinatetype/)(PageCoordinateType) | Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [set_FormPresentationMode](../imagedevice/set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Sets form presentation mode. |
| [set_RenderingOptions](../imagedevice/set_renderingoptions/)(System::SharedPtr\<Aspose::Pdf::RenderingOptions\>) | Sets rendering options. |
## See Also

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
