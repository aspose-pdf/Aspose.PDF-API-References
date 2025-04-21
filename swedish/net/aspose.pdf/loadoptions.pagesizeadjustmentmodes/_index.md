---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes enum. OBS! Funktionen är implementerad men har ännu inte lagts till i den offentliga APIn eftersom ett blockerande problem i OSHARED-lagret avslöjades för exempel dokument. Representerar användningsläge för sidstorlek under konvertering. Format som HTML, EPUB etc. har vanligtvis flytande design, så det tillåter att anpassa den erforderliga sidstorleken. Men ibland har innehållet specifika horisontella positioner eller storlek som inte tillåter att innehållet passar in i den erforderliga sidstorleken. I sådana fall kan vi definiera vad som ska göras i detta fall, dvs när storleken på innehållet inte passar den erforderliga initiala sidstorleken för den resulterande PDF-dokumentet.
type: docs
weight: 6140
url: /sv/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

OBS! Funktionen är implementerad men har ännu inte lagts till i den offentliga API:n eftersom ett blockerande problem i OSHARED-lagret avslöjades för exempel dokument. Representerar användningsläge för sidstorlek under konvertering. Format (som HTML, EPUB etc.), har vanligtvis flytande design, så det tillåter att anpassa den erforderliga sidstorleken. Men ibland har innehållet specifika horisontella positioner eller storlek som inte tillåter att innehållet passar in i den erforderliga sidstorleken. I sådana fall kan vi definiera vad som ska göras i detta fall (dvs när storleken på innehållet inte passar den erforderliga initiala sidstorleken för den resulterande PDF-dokumentet).

```csharp
public enum PageSizeAdjustmentModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | I detta läge kommer resultat sidorna att ha den erforderliga sidstorleken definierad i LoadOptions, oavsett om innehållet efter konvertering går utanför sidgränserna eller inte. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Detta läge definierar ett sådant beteende: efter att ha fått konverteringsresultatet och upptäckten av att vissa innehåll har blivit avskuret, ökas bredden på portvyn för att passa innehållet och konverteringen upprepas. Detta läge möjliggör att få färre sidor i resultatet i sådana fall men kräver upprepad rendering (och därmed mer bearbetningstid). |

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)