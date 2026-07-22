---
title: "Aspose::Pdf::Devices::PngDevice-klass"
linktitle: "PngDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::PngDevice-klass. Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som PNG i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.pdf.devices/pngdevice/
---
## PngDevice class


Representerar bildenhet som hjälper till att spara pdf-dokumentets sidor som png.

```cpp
class PngDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_TransparentBackground](./get_transparentbackground/)() const | Hämtar om bilden har transparent bakgrund. |
| [PngDevice](./pngdevice/)() | Initierar en ny instans av klassen [PngDevice](./) med standardupplösning. |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [PngDevice](./). |
| [PngDevice](./pngdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [PngDevice](./) med angivna bilddimensioner och upplösning. |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [PngDevice](./) med angiven sidstorlek och upplösning. |
| [PngDevice](./pngdevice/)(int32_t, int32_t) | Initierar en ny instans av klassen [PngDevice](./) med angivna bilddimensioner, standardupplösning (=150). |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<PageSize\>\&) | Initierar en ny instans av klassen [PngDevice](./) med angiven sidstorlek, standardupplösning (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Konverterar sidan till PNG och sparar den i utdataflödet. |
| [set_TransparentBackground](./set_transparentbackground/)(bool) | Ställer in om bilden har transparent bakgrund. |
## Se även

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
