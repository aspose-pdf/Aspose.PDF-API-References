---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna enum beskriver möjliga antialiasing‑åtgärder under konvertering."
type: docs
weight: 2000
url: /sv/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Denna enum beskriver möjliga antialiasing‑åtgärder under konvertering.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | Ingen speciell kantutjämningsbehandling används. Detta är ett optimalt alternativ för överväldigande majoriteten av dokument och kräver ingen extra tid under konvertering |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | I ett sådant fall försöker konverteraren att upptäcka platser med intilliggande bakgrundsgrafiska element och korrigera resultat‑HTML på ett relevant sätt. Detta alternativ möjliggör förbättring av exportresultatet för dokument som innehåller bakgrunder byggda av flera intilliggande grafiska element (för den här typen av dokument försöker PDF‑renderare, t.ex. Acrobat Reader, vanligtvis jämna ut elementens gränser under rendering. Med detta alternativ efterliknar konverteraren detta beteende hos PDF‑renderare. Detta alternativ möjliggör förbättring av layouten på exportresultatet för vissa specifika dokument (som använder sådana sammansatta bakgrunder), men det kräver extra tid för bearbetning (vanligtvis omkring 10‑15 % extra tid). Så användning av detta läge i allmänna fall rekommenderas inte. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

Ingen speciell kantutjämningsbehandling används. Detta är ett optimalt alternativ för överväldigande majoriteten av dokument och kräver ingen extra tid under konvertering

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

I ett sådant fall försöker konverteraren att upptäcka platser med intilliggande bakgrundsgrafiska element och korrigera resultat‑HTML på ett relevant sätt. Detta alternativ möjliggör förbättring av exportresultatet för dokument som innehåller bakgrunder byggda av flera intilliggande grafiska element (för den här typen av dokument försöker PDF‑renderare, t.ex. Acrobat Reader, vanligtvis jämna ut elementens gränser under rendering. Med detta alternativ efterliknar konverteraren detta beteende hos PDF‑renderare. Detta alternativ möjliggör förbättring av layouten på exportresultatet för vissa specifika dokument (som använder sådana sammansatta bakgrunder), men det kräver extra tid för bearbetning (vanligtvis omkring 10‑15 % extra tid). Så användning av detta läge i allmänna fall rekommenderas inte.
