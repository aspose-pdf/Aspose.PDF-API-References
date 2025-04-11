---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType enum. Denna enum beskriver möjliga antialiasingåtgärder under konvertering
type: docs
weight: 5570
url: /sv/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

Denna enum beskriver möjliga antialiasingåtgärder under konvertering

```csharp
public enum AntialiasingProcessingType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | ingen speciell antialiasingbehandling används. Detta är ett optimalt alternativ för den överväldigande majoriteten av dokument och kräver ingen extra tid under konvertering |
| TryCorrectResultHtml | `1` | I sådana fall försöker konverteraren att upptäcka platser med angränsande bakgrundsgrafiska element och korrigera resultat-HTML på relevant sätt. Detta alternativ möjliggör förbättring av exportresultatet för dokument som innehåller bakgrunder byggda av flera angränsande grafiska element (för sådana dokument försöker PDF-renderare, t.ex. Acrobat Reader, vanligtvis att jämna ut gränserna för elementen under rendering. Med detta alternativ imiterar konverteraren det beteendet hos PDF-renderare. Detta alternativ möjliggör förbättring av layouten för exportresultatet för vissa specifika dokument (som använder sådana sammansatta bakgrunder), men det kräver extra tid för bearbetning (vanligtvis cirka 10-15% extra tid). Så användning av detta läge rekommenderas generellt inte. |

### Se Även

* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)