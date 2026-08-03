---
title: "Enum DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.DocSaveOptionsRecognitionMode enum. Gör det möjligt att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument."
type: docs
weight: 3890
url: /sv/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

Gör det möjligt att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument.

```csharp
public enum RecognitionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Textbox | `0` | Detta läge är snabbt och bra för att maximalt bevara det ursprungliga utseendet på PDF-filen, men redigerbarheten i det resulterande dokumentet kan vara begränsad. |
| Flow | `1` | Fullständigt igenkänningsläge, motorn utför gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och skapa ett maximalt redigerbart dokument. Nackdelen är att utdata-dokumentet kan se annorlunda ut än den ursprungliga PDF-filen. |
| EnhancedFlow | `2` | Ett alternativt Flow-läge som stödjer igenkänning av tabeller. |

## Anmärkningar

Använd Textbox-läget när det resulterande dokumentet inte kommer att redigeras kraftigt vidare. Textboxar är enkla att modifiera när det inte finns mycket att göra.

Använd Flow-läget när utdata-dokumentet kräver vidare redigering. Paragrafer och textrader i flow-läget möjliggör enkel modifiering av text, men ej stödda formateringsobjekt kommer att se sämre ut än i Textbox-läget.

### Se även

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


