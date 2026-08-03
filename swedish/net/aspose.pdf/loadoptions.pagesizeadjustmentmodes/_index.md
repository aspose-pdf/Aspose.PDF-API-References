---
title: "Enum LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes‑enum. OBS Funktionen är implementerad men har ännu inte publicerats i det offentliga API:et på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för exempel‑dokumentet. Representerar läge för användning av sidstorlek under konvertering. Format som HTML, EPUB etc. har vanligtvis flytande design så de tillåter att anpassa till önskad sidstorlek. Men ibland specificerar innehållet horisontella positioner eller storlek som inte tillåter att innehållet placeras i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras, dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF‑dokumentet."
type: docs
weight: 6280
url: /sv/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

OBS! Funktionen är implementerad men har ännu inte publicerats i det offentliga API:et på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för exempel‑dokumentet. Representerar läge för användning av sidstorlek under konvertering. Format (som HTML, EPUB etc.) har vanligtvis flytande design, så de tillåter att anpassa till önskad sidstorlek. Men ibland specificerar innehållet horisontella positioner eller storlek som inte tillåter att innehållet placeras i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras (dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF‑dokumentet).

```csharp
public enum PageSizeAdjustmentModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | I detta läge kommer resultatsidorna att ha den erforderliga sidstorleken som definierats i LoadOptions, oavsett om innehållet efter konvertering hamnar utanför sidgränserna eller inte. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Detta läge definierar ett sådant beteende: efter att konverteringsresultatet erhållits och faktum att något innehåll har trunkerats upptäckts, förstoras bredden på portvyn för att passa innehållet och konverteringen upprepas. Detta läge möjliggör färre sidor i resultatet i ett sådant fall men kräver upprepad rendering (och därmed mer bearbetningstid). |

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


