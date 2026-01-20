---
title: Aspose::Pdf::Devices::PngDevice class
linktitle: PngDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::PngDevice class. Represents image device that helps to save pdf document pages into png in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.devices/pngdevice/
---
## PngDevice class


Represents image device that helps to save pdf document pages into png.

```cpp
class PngDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [get_TransparentBackground](./get_transparentbackground/)() const | Gets if image has transparent background. |
| [PngDevice](./pngdevice/)() | Initializes a new instance of the [PngDevice](./) class with default resolution. |
| [PngDevice](./pngdevice/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [PngDevice](./) class. |
| [PngDevice](./pngdevice/)(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [PngDevice](./) class with provided image dimensions and resolution. |
| [PngDevice](./pngdevice/)(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Initializes a new instance of the [PngDevice](./) class with provided page size and resolution. |
| [PngDevice](./pngdevice/)(int32_t, int32_t) | Initializes a new instance of the [PngDevice](./) class with provided image dimensions, default resolution (=150). |
| [PngDevice](./pngdevice/)(System::SharedPtr\<PageSize\>) | Initializes a new instance of the [PngDevice](./) class with provided page size, default resolution (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Converts the page into png and saves it in the output stream. |
| [set_TransparentBackground](./set_transparentbackground/)(bool) | Sets if image has transparent background. |
## See Also

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
