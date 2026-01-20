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
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Converts the page into Dicom and saves it in the output stream. |
## See Also

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
