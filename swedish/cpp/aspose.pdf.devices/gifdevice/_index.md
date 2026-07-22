---
title: "Aspose::Pdf::Devices::GifDevice-klass"
linktitle: "GifDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::GifDevice-klass. Representerar en bildenhet som hjälper till att spara pdf-dokumentsidor som gif i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.devices/gifdevice/
---
## GifDevice class


Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som gif.

```cpp
class GifDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GifDevice](./gifdevice/)() | Initierar en ny instans av [GifDevice](./)-klassen med standardupplösning. |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av [GifDevice](./)-klassen. |
| [GifDevice](./gifdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av [GifDevice](./)-klassen med angivna bilddimensioner och upplösning. |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av [GifDevice](./)-klassen med angiven sidstorlek och upplösning. |
| [GifDevice](./gifdevice/)(int32_t, int32_t) | Initierar en ny instans av [GifDevice](./)-klassen med angivna bilddimensioner, standardupplösning (=150). |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<PageSize\>\&) | Initierar en ny instans av [GifDevice](./)-klassen med angiven sidstorlek, standardupplösning (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Konverterar sidan till gif och sparar den i utdataflödet. |
## Se även

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
