---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF för Java API-referens"
description: "ATTENTION! Funktionen är implementerad men har ännu inte lagts till i det offentliga API:t på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för exempel‑dokumentet. Representerar lägesanvändning av sidstorlek."
type: docs
weight: 2810
url: /sv/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

OBS! Funktionen är implementerad men har ännu inte placerats i det offentliga API:t på grund av blockerande problem i OSHARED-lagret som upptäcktes för exempel-dokumentet. Representerar användningsläge för sidstorlek under konvertering. Format (som HTML, EPUB etc) har vanligtvis flytande design, så den tillåter att anpassa till önskad sidstorlek. Men ibland specificerar innehållet horisontella positioner eller storlek som inte tillåter att placera innehållet i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras i detta fall (dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF-dokumentet).

## Fält

| Fält | Beskrivning |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Detta läge definierar sådant beteende: efter att konverteringsresultatet erhållits och faktum att något innehåll har trunkerats upptäckts, förstoras portvyns bredd för att passa innehållet och konverteringen upprepas. Detta läge möjliggör färre sidor i resultatet i ett sådant fall men kräver upprepad rendering (och därmed mer bearbetningstid). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | I detta läge kommer resultatsidorna att ha den erforderliga sidstorleken som definierats i LoadOptions, oavsett om innehållet efter konvertering hamnar utanför sidgränserna eller inte. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Detta läge definierar sådant beteende: efter att konverteringsresultatet erhållits och faktum att något innehåll har trunkerats upptäckts, förstoras portvyns bredd för att passa innehållet och konverteringen upprepas. Detta läge möjliggör färre sidor i resultatet i ett sådant fall men kräver upprepad rendering (och därmed mer bearbetningstid).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

I detta läge kommer resultatsidorna att ha den erforderliga sidstorleken som definierats i LoadOptions, oavsett om innehållet efter konvertering hamnar utanför sidgränserna eller inte.
