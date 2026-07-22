---
title: "Aspose::Pdf::HtmlSaveOptions::AntialiasingProcessingType enum"
linktitle: "AntialiasingProcessingType"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::AntialiasingProcessingType enum. Denna enum beskriver möjliga antialiasing‑åtgärder under konvertering i C++."
type: docs
weight: 5100
url: /sv/cpp/aspose.pdf/htmlsaveoptions/antialiasingprocessingtype/
---
## AntialiasingProcessingType enum


Denna enum beskriver möjliga antialiasing-åtgärder under konvertering.

```cpp
enum class AntialiasingProcessingType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoAdditionalProcessing | 0 | Inga speciella antialiasing‑åtgärder används. Detta är ett optimalt alternativ för den överväldigande majoriteten av dokument och kräver ingen extra tid under konverteringen. |
| TryCorrectResultHtml | 1 | I sådant fall försöker konverteraren att upptäcka områden med intilliggande bakgrundsgrafiska element och korrigera den resulterande HTML:n på ett lämpligt sätt. Detta alternativ möjliggör förbättring av exportresultatet för dokument som innehåller bakgrunder byggda av flera intilliggande grafiska element (för sådana dokument försöker PDF‑renderare, t.ex. Acrobat Reader, vanligtvis mjuka upp elementens gränser under rendering. Med detta alternativ efterliknar konverteraren detta beteende hos PDF‑renderare. Detta alternativ förbättrar layouten av exportresultatet för vissa specifika dokument (som använder sådana sammansatta bakgrunder), men det kräver extra tid för bearbetning (vanligtvis omkring 10‑15 % extra tid). Så användning av detta läge i allmänna fall rekommenderas inte. |

## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
