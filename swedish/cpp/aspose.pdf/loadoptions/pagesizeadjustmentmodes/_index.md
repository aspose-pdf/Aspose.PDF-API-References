---
title: "Aspose::Pdf::LoadOptions::PageSizeAdjustmentModes enum"
linktitle: "PageSizeAdjustmentModes"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LoadOptions::PageSizeAdjustmentModes enum. OBS! Funktionen är implementerad men har ännu inte gjorts tillgänglig i det offentliga API:t på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för ett exempel‑dokument i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf/loadoptions/pagesizeadjustmentmodes/
---
## PageSizeAdjustmentModes enum


OBS! Funktionen har implementerats men har ännu inte placerats i det offentliga API:et på grund av blockerande problem i OSHARED-lagret som upptäcktes för exempel-dokumentet.

```cpp
enum class PageSizeAdjustmentModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | 0 | I det här läget kommer resultatsidorna att ha den erforderliga sidstorleken som definierats i [LoadOptions](../), oavsett om innehållet efter konvertering hamnar utanför sidgränserna eller inte. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | 1 | Detta läge definierar ett sådant beteende: efter att konverteringsresultatet erhållits och faktum att något innehåll har trunkerats upptäckts, förstoras bredden på viewporten för att passa innehållet och konverteringen upprepas. Detta läge möjliggör att få färre sidor i resultatet i ett sådant fall men kräver upprepad rendering (och därmed mer bearbetningstid). |

## Anmärkningar


Representerar hur sidstorlek används under konvertering. Format (som HTML, EPUB etc.) har vanligtvis flytande layout, så de tillåter att anpassa den erforderliga sidstorleken. Men ibland specificerar innehållet horisontella positioner eller storlek som inte tillåter att placera innehållet i den erforderliga sidstorleken. I sådana fall kan vi definiera vad som ska göras (dvs. när innehållets storlek inte passar den initiala sidstorleken för den resulterande PDF‑dokumentet).
## Se även

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
