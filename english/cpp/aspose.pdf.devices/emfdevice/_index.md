---
title: Aspose::Pdf::Devices::EmfDevice class
linktitle: EmfDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::EmfDevice class. Represents image device that helps to save pdf document pages into emf in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.devices/emfdevice/
---
## EmfDevice class


Represents image device that helps to save pdf document pages into emf.

```cpp
class EmfDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [EmfDevice](./emfdevice/)() | Initializes a new instance of the [EmfDevice](./) class with default resolution of raster image written to emf. |
| [EmfDevice](./emfdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [EmfDevice](./) class. |
| [EmfDevice](./emfdevice/)(int32_t, int32_t) | Initializes a new instance of the [EmfDevice](./) class with provided image dimensions, and default resolution for the raster image written to emf (=150) |
| [EmfDevice](./emfdevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [EmfDevice](./) class with provided page size, and default resolution for the raster image written to emf (=150) |
| [EmfDevice](./emfdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided image dimensions, and resolution for the raster image written to emf. |
| [EmfDevice](./emfdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](../jpegdevice/) class with provided page size, and resolution for the raster image written to emf. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Converts the page into emf and saves it in the output stream. |
## See Also

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
