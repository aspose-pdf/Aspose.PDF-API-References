---
title: HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF för .NET API Referens
description: Denna uppräkning beskriver möjliga kantutjämningsåtgärder under konvertering
type: docs
weight: 3440
url: /sv/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

Denna uppräkning beskriver möjliga kantutjämningsåtgärder under konvertering

```csharp
public enum AntialiasingProcessingType
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | ingen speciell kantutjämningsbehandling används. Detta är ett optimalt alternativ för en överväldigande majoritet av dokument och det kräver inte ytterligare tid under konvertering |
| TryCorrectResultHtml | `1` | I sådana fall försöker omvandlaren att upptäcka platser med angränsande bakgrundsgrafiska -element och korrekta resultat-HTML på ett relevant sätt. Det här alternativet tillåter förbättrade exportresultat för dokument som innehåller backgrounds byggda från flera närliggande grafiska element (för sådana typer av dokument som PDF-renderare , t.ex. Acrobat Reader, brukar försöka jämna gränser för element under rendering. Med det här alternativet imiterar omvandlaren beteendet hos PDF-renderare. Det här alternativet tillåter förbättra layouten av resultatet av exporten för vissa specifika dokument (som använder sådana sammansatta bakgrunder), men det kräver ytterligare tid för bearbetning (vanligtvis cirka 10-15 % av ytterligare tid). Så användning av detta läge rekommenderas i allmänhet inte. |

### Se även

* class [HtmlSaveOptions](../htmlsaveoptions)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->