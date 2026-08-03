---
title: "Enum HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType‑enum. Denna enum beskriver möjliga antialiasing‑åtgärder under konvertering"
type: docs
weight: 5700
url: /sv/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

Denna enum beskriver möjliga antialiasing‑åtgärder under konvertering

```csharp
public enum AntialiasingProcessingType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | Ingen speciell antialiasing‑behandling används. Detta är ett optimalt alternativ för den överväldigande majoriteten av dokument och kräver ingen extra tid under konvertering |
| TryCorrectResultHtml | `1` | I ett sådant fall försöker konverteraren att upptäcka områden med intilliggande bakgrundsgrafiska element och korrigera den resulterande HTML på ett relevant sätt. Detta alternativ möjliggör förbättring av exportresultatet för dokument som innehåller bakgrunder byggda av flera intilliggande grafiska element (för sådana dokument försöker PDF‑renderare, t.ex. Acrobat Reader, vanligtvis mjuka upp elementens gränser under rendering. Med detta alternativ efterliknar konverteraren detta beteende hos PDF‑renderare. Detta alternativ möjliggör förbättring av layouten för exportresultatet för vissa specifika dokument (som använder sådana sammansatta bakgrunder), men det kräver extra tid för bearbetning (vanligtvis omkring 10‑15 % extra tid). Så användning av detta läge i allmänna fall rekommenderas inte. |

### Se även

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


