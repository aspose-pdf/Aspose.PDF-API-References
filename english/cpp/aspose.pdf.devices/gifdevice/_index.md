---
title: Aspose::Pdf::Devices::GifDevice class
linktitle: GifDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::GifDevice class. Represents image device that helps to save pdf document pages into gif in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.devices/gifdevice/
---
## GifDevice class


Represents image device that helps to save pdf document pages into gif.

```cpp
class GifDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [GifDevice](./gifdevice/)() | Initializes a new instance of the [GifDevice](./) class with default resolution. |
| [GifDevice](./gifdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [GifDevice](./) class. |
| [GifDevice](./gifdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [GifDevice](./) class with provided image dimensions and resolution. |
| [GifDevice](./gifdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [GifDevice](./) class with provided page size and resolution. |
| [GifDevice](./gifdevice/)(int32_t, int32_t) | Initializes a new instance of the [GifDevice](./) class with provided image dimensions, default resolution (=150). |
| [GifDevice](./gifdevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [GifDevice](./) class with provided page size, default resolution (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Converts the page into gif and saves it in the output stream. |
## See Also

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
