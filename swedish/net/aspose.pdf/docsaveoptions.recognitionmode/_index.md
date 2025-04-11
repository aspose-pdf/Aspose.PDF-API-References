---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptionsRecognitionMode enum. Möjliggör kontroll över hur ett PDF-dokument konverteras till ett ordbehandlingsdokument
type: docs
weight: 3770
url: /sv/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode-uppräkning

Möjliggör kontroll över hur ett PDF-dokument konverteras till ett ordbehandlingsdokument.

```csharp
public enum RecognitionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Textbox | `0` | Detta läge är snabbt och bra för att maximalt bevara det ursprungliga utseendet av PDF-filen, men redigerbarheten av det resulterande dokumentet kan vara begränsad. |
| Flow | `1` | Fullständigt igenkänningsläge, motorn utför gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och producera ett maximalt redigerbart dokument. Nackdelen är att det utgående dokumentet kan se annorlunda ut än den ursprungliga PDF-filen. |
| EnhancedFlow | `2` | Ett alternativt Flow-läge som stöder igenkänning av tabeller. |

## Anmärkningar

Använd Textbox-läget när det resulterande dokumentet inte kommer att redigeras mycket vidare. Textboxar är lätta att modifiera när det inte finns mycket att göra.

Använd Flow-läget när det utgående dokumentet behöver ytterligare redigering. Stycken och textrader i flow-läget möjliggör enkel modifiering av text, men osupporterade formateringsobjekt kommer att se sämre ut än i Textbox-läget.

### Se Även

* klass [DocSaveOptions](../docsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)