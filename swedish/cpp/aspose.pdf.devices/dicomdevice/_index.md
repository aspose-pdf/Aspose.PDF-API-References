---
title: "Aspose::Pdf::Devices::DicomDevice klass"
linktitle: "DicomDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::DicomDevice-klass. Representerar bildenhet som hjälper till att spara PDF-dokumentets sidor i Dicom-format i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class


Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor i Dicom-format.

```cpp
class DicomDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DicomDevice](./dicomdevice/)() | Initierar en ny instans av klassen [DicomDevice](./) med standardupplösning. |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [DicomDevice](./). |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<PageSize\>\&) | Initierar en ny instans av klassen [DicomDevice](./) med angiven sidstorlek, med standardupplösning (=150). |
| [DicomDevice](./dicomdevice/)(int32_t, int32_t) | Initierar en ny instans av klassen [DicomDevice](./) med angivna bilddimensioner, med standardupplösning (=150). |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [DicomDevice](./) med angiven sidstorlek och upplösning. |
| [DicomDevice](./dicomdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [DicomDevice](./) med angivna bilddimensioner och upplösning. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Konverterar sidan till Dicom och sparar den i utdataflödet. |
## Se även

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
