---
title: "Enum LoadOptions.MarginsAreaUsageModes"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. Representerar läge för användning av marginalområde under konvertering, som HTML, EPUB etc., och definierar behandlingen av instruktioner i importerat format relaterade till användning av marginaler"
type: docs
weight: 6270
url: /sv/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

Representerar läge för användning av marginalområde under konvertering (som HTML, EPUB etc.), definierar behandlingen av instruktioner i importerat format relaterade till användning av marginaler.

```csharp
public enum MarginsAreaUsageModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | I detta läge följer konverteraren formatet för det importerade dokumentet (t.ex. CSS för importerad HTML) vid användning av marginalområdet. Så om formatet för det importerade dokumentet kräver användning av marginalområdet för rendering, kommer konverteraren att tillåta det. |
| NeverPutContentOnMarginArea | `1` | Detta läge förbjuder strikt användning av marginalområdet, så konverteraren kommer aldrig att använda marginalområdet för rendering, även om CSS eller formatet för källdokumentet tillåter eller kräver det. |

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


