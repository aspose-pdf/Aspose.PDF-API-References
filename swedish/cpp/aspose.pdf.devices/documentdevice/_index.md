---
title: "Aspose::Pdf::Devices::DocumentDevice klass"
linktitle: "DocumentDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::DocumentDevice klass. Abstrakt klass för alla enheter som används för att bearbeta hela pdf-dokumentet i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.devices/documentdevice/
---
## DocumentDevice class


Abstrakt klass för alla enheter som används för att bearbeta hela PDF-dokumentet.

```cpp
class DocumentDevice : public Aspose::Pdf::Devices::PageDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DocumentDevice](./documentdevice/)() |  |
| virtual [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Varje enhet representerar någon operation på dokumentet, t.ex. kan vi konvertera pdf-dokumentet till ett annat format. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Bearbetar hela dokumentet och sparar resultatet i en ström. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Bearbetar hela dokumentet och sparar resultatet i en fil. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, int32_t, int32_t, const System::String\&) | Bearbetar vissa sidor i dokumentet och sparar resultatet i en fil. |
## Se även

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
