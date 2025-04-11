---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptionsRecognitionMode enum. När en PDF-fil som vanligtvis har fast layout konverteras försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och producera resultat i flödeslayout. Denna egenskap justerar den konverteringen för denna eller den önskvärda metoden för igenkänning av innehåll
type: docs
weight: 4070
url: /sv/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode-uppräkning

När en PDF-fil (som vanligtvis har fast layout) konverteras, försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och producera resultat i flödeslayout. Denna egenskap justerar den konverteringen för denna eller den önskvärda metoden för igenkänning av innehåll.

```csharp
public enum RecognitionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Flöde | `0` | Full igenkänningsläge, motorn försöker utföra gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och producera xhtml i flödeslayout. |
| PdfFlöde | `1` | Huvudidén med denna konvertering baseras på att spara den "naturliga" ordningen av innehållsrendering som bildas under bearbetningen av pdf-dokument. I allmänhet behåller pdf-dokument en topp-till-botten, vänster-till-höger renderingsordning (se bilaga directions.png). Denna antagande möjliggör att skapa en enkelvägsalgoritm som kommer att omvandla Aps-element som har positioner (fast layout) till flödesformat som HTML, EPUB, DOC. Detta läge kommer att vara särskilt användbart för konvertering från PDF(APS) till EPUB, eftersom EPUB-formatet utvecklades för e-läsare som Kindle eller smarttelefoner. Skärmstorleken på dessa enheter är vanligtvis mindre än storleken på en vanlig PC-skärm. Därför är det bättre att spara innehållet i EPUB-dokument i flödesformat för korrekt rendering på skärmar med olika storlekar. I detta läge kommer varje kolumn att läggas till slutet av föregående kolumn vilket gör att den logiska strukturen av det transformerade dokumentet kan bevaras under "sidan" i EPUB-läsare. Denna prestation möjliggör korrekt rendering av vetenskapliga eller tidskriftsartiklar. |
| Fast | `2` | Detta läge är snabbt och bra för att maximalt bevara det ursprungliga utseendet på sidorna, men tyvärr stöder många EPUB-läsare inte xhtml med fast layout |

### Se Även

* klass [EpubSaveOptions](../epubsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)