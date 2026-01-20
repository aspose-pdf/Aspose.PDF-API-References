---
title: Aspose::Pdf::Devices::BmpDevice class
linktitle: BmpDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::BmpDevice class. Represents image device that helps to save pdf document pages into bmp in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class


Represents image device that helps to save pdf document pages into bmp.

```cpp
class BmpDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [BmpDevice](./bmpdevice/)() | Initializes a new instance of the [BmpDevice](./) class with default resolution. |
| [BmpDevice](./bmpdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [BmpDevice](./) class. |
| [BmpDevice](./bmpdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [BmpDevice](./) class with provided image dimensions and resolution. |
| [BmpDevice](./bmpdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [BmpDevice](./) class with provided page size and resolution. |
| [BmpDevice](./bmpdevice/)(int32_t, int32_t) | Initializes a new instance of the [BmpDevice](./) class with provided image dimensions, default resolution (=150). |
| [BmpDevice](./bmpdevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [BmpDevice](./) class with provided page size, default resolution (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Converts the page into bmp and saves it in the output stream. |
## See Also

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
