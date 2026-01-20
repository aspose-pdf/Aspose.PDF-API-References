---
title: Aspose::Pdf::Devices::TextDevice class
linktitle: TextDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::TextDevice class. Represents class for converting pdf document pages into text in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.devices/textdevice/
---
## TextDevice class


Represents class for converting pdf document pages into text.

```cpp
class TextDevice : public Aspose::Pdf::Devices::PageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [get_Encoding](./get_encoding/)() const | Gets encoding of extracted text. |
| [get_ExtractionOptions](./get_extractionoptions/)() const | Gets text extraction options. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Convert page and save it as text stream. |
| [set_Encoding](./set_encoding/)(System::SharedPtr\<System::Text::Encoding\>) | Sets encoding of extracted text. |
| [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<Text::TextExtractionOptions\>) | Sets text extraction options. |
| [TextDevice](./textdevice/)(System::SharedPtr\<Text::TextExtractionOptions\>) | Initializes a new instance of the [TextDevice](./) with text extraction options. |
| [TextDevice](./textdevice/)() | Initializes a new instance of the [TextDevice](./) with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice](./textdevice/)(System::SharedPtr\<System::Text::Encoding\>) | Initializes a new instance of the [TextDevice](./) for the specified encoding. |
| [TextDevice](./textdevice/)(System::SharedPtr\<Text::TextExtractionOptions\>, System::SharedPtr\<System::Text::Encoding\>) | Initializes a new instance of the [TextDevice](./) for the specified encoding with text extraction options. |
## Remarks


The [TextDevice](./) object is basically used to extract text from pdf page. 
## See Also

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
