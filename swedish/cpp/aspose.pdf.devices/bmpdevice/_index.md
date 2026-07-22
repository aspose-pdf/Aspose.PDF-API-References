---
title: "Aspose::Pdf::Devices::BmpDevice-klass"
linktitle: "BmpDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::BmpDevice-klass. Representerar bildenhet som hjälper till att spara PDF-dokumentets sidor i bmp i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class


Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som bmp.

```cpp
class BmpDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BmpDevice](./bmpdevice/)() | Initierar en ny instans av klassen [BmpDevice](./) med standardupplösning. |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [BmpDevice](./). |
| [BmpDevice](./bmpdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [BmpDevice](./) med angivna bilddimensioner och upplösning. |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [BmpDevice](./) med angiven sidstorlek och upplösning. |
| [BmpDevice](./bmpdevice/)(int32_t, int32_t) | Initierar en ny instans av klassen [BmpDevice](./) med angivna bilddimensioner, standardupplösning (=150). |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<PageSize\>\&) | Initierar en ny instans av klassen [BmpDevice](./) med angiven sidstorlek, standardupplösning (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Konverterar sidan till bmp och sparar den i utdataflödet. |
## Se även

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
