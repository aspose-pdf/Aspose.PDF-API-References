---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. Representerar användningsläge för marginalområdet under konvertering som HTML EPUB etc definierar behandling av instruktioner från det importerade formatet relaterat till användning av marginaler
type: docs
weight: 6130
url: /sv/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes uppräkning

Representerar användningsläge för marginalområdet under konvertering (som HTML, EPUB etc), definierar behandling av instruktioner från det importerade formatet relaterat till användning av marginaler.

```csharp
public enum MarginsAreaUsageModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | I detta läge följer konverteraren formatet av det importerade dokumentet (t.ex. CSS av importerad HTML) i användningen av marginalområdet. Så, om formatet av det importerade dokumentet kräver användning av marginalområdet för rendering, kommer konverteraren att tillåta det |
| NeverPutContentOnMarginArea | `1` | Detta läge förbjuder strikt användning av marginalområdet, så konverteraren kommer aldrig att använda marginalområdet för rendering, även om CSS eller formatet av källdokumentet tillåter eller kräver det |

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)