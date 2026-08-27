---
title: "Enum EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.EpubSaveOptionsRecognitionMode-enum. När en PDF-fil som vanligtvis har fast layout konverteras försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa dokumentets ursprungliga avsikt och producera resultat i flödeslayout. Denna egenskap justerar den konverteringen för denna eller den önskade metoden för igenkänning av innehåll."
type: docs
weight: 4190
url: /sv/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

När en PDF-fil (som vanligtvis har fast layout) konverteras, försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa den ursprungliga författarens avsikt och producera resultat i flödeslayout. Denna egenskap finjusterar den konverteringen för den ena eller andra önskade metoden för innehållsigenkänning.

```csharp
public enum RecognitionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Flow | `0` | Fullt igenkänningsläge, motorn försöker utföra gruppering och flernivåanalys för att återställa dokumentets ursprungliga avsikt och producera xhtml i flödeslayout. |
| PdfFlow | `1` | Huvudidén med denna konvertering baseras på att spara den "naturliga" ordningen för innehållsrendering som bildas under bearbetning av pdf-dokument. I allmänna fall behåller pdf-dokument top‑down, left‑right renderingsordning (se bilagan directions.png). Detta antagande möjliggör att skapa en enkelvägsalgoritm som omvandlar Aps‑element som har positioner (fixed‑layout) till flödesformat som HTML, EPUB, DOC. Detta läge kommer vara särskilt användbart för konvertering från PDF(APS) till EPUB, eftersom EPUB‑formatet utvecklades för e‑readers som Kindle eller smartphones. Skärmstorleken på dessa enheter är vanligtvis mindre än skärmstorleken på en vanlig PC. Därför är det bättre att spara innehållet i EPUB‑dokument i flödesformat för korrekt rendering på skärmar med olika storlekar. I detta läge kommer varje kolumn att läggas till i slutet av föregående kolumn, vilket möjliggör att behålla den logiska strukturen i det transformerade dokumentet under "pagination" i EPUB‑läsare. Detta resultat möjliggör korrekt rendering av vetenskapliga eller magasinartiklar. |
| Fixed | `2` | Detta läge är snabbt och bra för att maximalt bevara de ursprungliga sidornas utseende, men tyvärr stödjer många EPUB‑läsare inte xhtml med fast layout. |

### Se även

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


