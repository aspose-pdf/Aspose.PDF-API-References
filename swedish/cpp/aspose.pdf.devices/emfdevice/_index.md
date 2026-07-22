---
title: "Aspose::Pdf::Devices::EmfDevice class"
linktitle: "EmfDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::EmfDevice class. Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor till emf i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.devices/emfdevice/
---
## EmfDevice class


Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som emf.

```cpp
class EmfDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EmfDevice](./emfdevice/)() | Initierar en ny instans av klassen [EmfDevice](./) med standardupplösning för rasterbilden som skrivs till emf. |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [EmfDevice](./). |
| [EmfDevice](./emfdevice/)(int32_t, int32_t) | Initierar en ny instans av klassen [EmfDevice](./) med angivna bilddimensioner och standardupplösning för rasterbilden som skrivs till emf (=150). |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<PageSize\>\&) | Initierar en ny instans av klassen [EmfDevice](./) med angiven sidstorlek och standardupplösning för rasterbilden som skrivs till emf (=150). |
| [EmfDevice](./emfdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [JpegDevice](../jpegdevice/) med angivna bilddimensioner och upplösning för rasterbilden som skrivs till emf. |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [JpegDevice](../jpegdevice/) med angiven sidstorlek och upplösning för rasterbilden som skrivs till emf. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Konverterar sidan till emf och sparar den i utdataflödet. |
## Se även

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
