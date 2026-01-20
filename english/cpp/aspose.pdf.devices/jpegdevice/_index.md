---
title: Aspose::Pdf::Devices::JpegDevice class
linktitle: JpegDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::JpegDevice class. Represents image device that helps to save pdf document pages into jpeg in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class


Represents image device that helps to save pdf document pages into jpeg.

```cpp
class JpegDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [JpegDevice](./jpegdevice/)() | Initializes a new instance of the [JpegDevice](./) class with default resolution and maximum quality. |
| [JpegDevice](./jpegdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](./) class. |
| [JpegDevice](./jpegdevice/)(int32_t) | Initializes a new instance of the [JpegDevice](./) class. |
| [JpegDevice](./jpegdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, int32_t) | Initializes a new instance of the [JpegDevice](./) class. |
| [JpegDevice](./jpegdevice/)(int32_t, int32_t) | Initializes a new instance of the [JpegDevice](./) class with provided image dimensions, default resolution (=150) and maximum quality. |
| [JpegDevice](./jpegdevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [JpegDevice](./) class with provided page size, default resolution (=150) and maximum quality. |
| [JpegDevice](./jpegdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](./) class with provided image dimensions, resolution and maximum quality. |
| [JpegDevice](./jpegdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [JpegDevice](./) class with provided page size, resolution and maximum quality. |
| [JpegDevice](./jpegdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, int32_t) | Initializes a new instance of the [JpegDevice](./) class with provided image dimensions, resolution and quality. |
| [JpegDevice](./jpegdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, int32_t) | Initializes a new instance of the [JpegDevice](./) class with provided page size, resolution and quality. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Converts the page into jpeg and saves it in the output stream. |
## See Also

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
