---
title: "Aspose::Pdf::DocSaveOptions::RecognitionMode enum"
linktitle: "RecognitionMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DocSaveOptions::RecognitionMode enum. Tillåter att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument i C++."
type: docs
weight: 2700
url: /sv/cpp/aspose.pdf/docsaveoptions/recognitionmode/
---
## RecognitionMode enum


Gör det möjligt att kontrollera hur ett PDF-dokument konverteras till ett ordbehandlingsdokument.

```cpp
enum class RecognitionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Textruta | 0 | Detta läge är snabbt och bra för att maximalt bevara PDF-filens ursprungliga utseende, men redigerbarheten i det resulterande dokumentet kan vara begränsad. |
| Flow | 1 | Fullständig igenkänningsläge, motorn utför gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och skapa ett maximalt redigerbart dokument. Nackdelen är att utdata‑dokumentet kan se annorlunda ut än den ursprungliga PDF‑filen. |
| EnhancedFlow | 2 | Ett alternativt [Flow](../../../aspose.pdf.flow/) läge som stödjer igenkänning av tabeller. |

## Anmärkningar


Använd [RecognitionMode::Textbox](./) läget när det resulterande dokumentet inte kommer att redigeras kraftigt vidare. Textrutor är enkla att modifiera när det inte finns mycket att göra.

Använd [RecognitionMode::Flow](./) läget när utdata-dokumentet behöver ytterligare redigering. [Paragraphs](../../paragraphs/) och textrader i flödesläget möjliggör enkel modifiering av text, men ej stödjade formateringsobjekt ser sämre ut än i [RecognitionMode::Textbox](./) läget.
## Se även

* Class [DocSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
