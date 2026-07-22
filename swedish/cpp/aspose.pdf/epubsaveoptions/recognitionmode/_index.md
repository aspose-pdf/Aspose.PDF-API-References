---
title: "Aspose::Pdf::EpubSaveOptions::RecognitionMode enum"
linktitle: "RecognitionMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::EpubSaveOptions::RecognitionMode enum. När en PDF‑fil (som vanligtvis har fast layout) konverteras, försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa den ursprungliga författarens avsikt och producera ett resultat i flödeslayout. Denna egenskap justerar den konverteringen för den önskade metoden för innehållsigenkänning i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf/epubsaveoptions/recognitionmode/
---
## RecognitionMode enum


När en PDF‑fil (som vanligtvis har fast layout) konverteras försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa den ursprungliga författarens avsikt och producera resultat i flödeslayout. Denna egenskap justerar den konverteringen för den önskade metoden för innehållsigenkänning.

```cpp
enum class RecognitionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Flow | 0 | Fullt igenkänningsläge, motorn försöker utföra gruppering och flernivåanalys för att återställa den ursprungliga författarens avsikt och producera XHTML i flödeslayout. |
| PdfFlow | 1 | Huvudidén med denna konvertering bygger på att bevara den \"naturliga\" ordningen för innehållsrendering som bildas under bearbetning av PDF‑dokument. I allmänna fall behåller PDF‑dokument en topp‑till‑botten, vänster‑till‑höger renderingsordning (se bilagan directions.png). Detta antagande möjliggör att skapa en enkel‑spår‑algoritm som omvandlar Aps‑element med positioner (fast layout) till flödesformat som HTML, EPUB, DOC. Detta läge är särskilt användbart för konvertering från PDF (APS) till EPUB, eftersom EPUB‑formatet utvecklades för e‑readers som Kindle eller smartphones. Skärmstorleken på dessa enheter är vanligtvis mindre än skärmstorleken på en vanlig PC. Därför är det bättre att spara innehållet i EPUB‑dokument i flödesformat för korrekt rendering på skärmar med olika storlekar. I detta läge läggs varje kolumn till i slutet av föregående kolumn, vilket möjliggör att behålla den logiska strukturen i det omvandlade dokumentet under \"paginerings\" i EPUB‑läsare. Detta möjliggör korrekt rendering av vetenskapliga eller tidskriftsartiklar. |
| Fast | 2 | Detta läge är snabbt och bra för att maximalt bevara originalutseendet på sidorna, men tyvärr stödjer många EPUB‑läsare inte XHTML med fast layout. |

## Se även

* Class [EpubSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
