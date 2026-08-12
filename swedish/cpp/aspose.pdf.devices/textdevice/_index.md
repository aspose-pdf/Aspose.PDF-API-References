---
title: "Aspose::Pdf::Devices::TextDevice class"
linktitle: "TextDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::TextDevice-klass. Representerar en klass för att konvertera pdf-dokumentsidor till text i C++."
type: docs
weight: 1300
url: /sv/cpp/aspose.pdf.devices/textdevice/
---
## TextDevice class


Representerar klass för att konvertera pdf-dokumentets sidor till text.

```cpp
class TextDevice : public Aspose::Pdf::Devices::PageDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Encoding](./get_encoding/)() const | Hämtar kodning för extraherad text. |
| [get_ExtractionOptions](./get_extractionoptions/)() const | Hämtar alternativ för textutvinning. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Konvertera sidan och spara den som textström. |
| [set_Encoding](./set_encoding/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Ställer in kodning för extraherad text. |
| [set_ExtractionOptions](./set_extractionoptions/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&) | Ställer in alternativ för textutvinning. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&) | Initierar en ny instans av [TextDevice](./) med alternativ för textutdrag. |
| [TextDevice](./textdevice/)() | Initierar en ny instans av [TextDevice](./) med rå textformateringsläge och Unicode-textkodning. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Initierar en ny instans av [TextDevice](./) för den angivna kodningen. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&, const System::SharedPtr\<System::Text::Encoding\>\&) | Initierar en ny instans av [TextDevice](./) för den angivna kodningen med alternativ för textutdrag. |
## Anmärkningar


Objektet [TextDevice](./) används i huvudsak för att extrahera text från en pdf-sida.
## Se även

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
