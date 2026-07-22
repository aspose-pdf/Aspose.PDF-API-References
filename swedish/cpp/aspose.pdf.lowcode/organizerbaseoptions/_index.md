---
title: "Aspose::Pdf::LowCode::OrganizerBaseOptions klass"
linktitle: "OrganizerBaseOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::OrganizerBaseOptions klass. Representerar grundalternativ för plugins i C++."
type: docs
weight: 5200
url: /sv/cpp/aspose.pdf.lowcode/organizerbaseoptions/
---
## OrganizerBaseOptions class


Representerar grundalternativ för plugins.

```cpp
class OrganizerBaseOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                             public Aspose::Pdf::LowCode::IDataContainer,
                             public Aspose::Pdf::LowCode::ISaveInstruction
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i PdfOrganizer‑pluginens datainsamling. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i PdfOrganizer‑pluginens datainsamling. |
| [get_CloseInputStreams](./get_closeinputstreams/)() const | Stäng inmatningsströmmar efter att operationen är slutförd. |
| [get_CloseOutputStreams](./get_closeoutputstreams/)() const | Stäng utmatningsströmmar efter att operationen är slutförd. |
| [get_Inputs](./get_inputs/)() override | Returnerar datainsamlingen för OrganizerOptions‑pluginen. |
| [get_Outputs](./get_outputs/)() override | Hämtar samlingen av tillagda mål för att spara operationsresultat. |
| [set_CloseInputStreams](./set_closeinputstreams/)(bool) | Stäng inmatningsströmmar efter att operationen är slutförd. |
| [set_CloseOutputStreams](./set_closeoutputstreams/)(bool) | Stäng utmatningsströmmar efter att operationen är slutförd. |
## Se även

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
