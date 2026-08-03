---
title: "Enum ExplicitDestinationType"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.ExplicitDestinationType-enum. Enumererar typerna av explicita destinationer."
type: docs
weight: 1780
url: /sv/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enumeration

Enumererar typerna av explicita destinationer.

```csharp
public enum ExplicitDestinationType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| XYZ | `0` | Visa sidan med koordinaterna (left, top) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorad med zoomfaktorn. Ett null‑värde för någon av parametrarna left, top eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoomvärde på 0 har samma betydelse som ett null‑värde. |
| Fit | `1` | Visa sidan med dess innehåll förstorad tillräckligt för att passa hela sidan inom fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringsfaktorerna är olika, använd den mindre av de två och centrera sidan inom fönstret i den andra dimensionen. |
| FitH | `2` | Visa sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstorad tillräckligt för att passa hela sidans bredd inom fönstret. Ett null‑värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitV | `3` | Visa sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorad tillräckligt för att passa hela sidans höjd inom fönstret. Ett null‑värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitR | `4` | Visa sidan med dess innehåll förstorad tillräckligt för att passa rektangeln som anges av koordinaterna left, bottom, right och top helt inom fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringsfaktorerna är olika, använd den mindre av de två och centrera rektangeln inom fönstret i den andra dimensionen. Ett null‑värde för någon av parametrarna kan leda till oförutsägbart beteende. |
| FitB | `5` | Visa sidan med dess innehåll förstorad tillräckligt för att passa dess omgivande ruta helt inom fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringsfaktorerna är olika, använd den mindre av de två och centrera den omgivande rutan inom fönstret i den andra dimensionen. |
| FitBH | `6` | Visa sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstorad tillräckligt för att passa hela bredden av dess omgivande ruta inom fönstret. Ett null‑värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitBV | `7` | Visa sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat tillräckligt för att passa hela höjden av dess begränsningsruta inom fönstret. Ett null‑värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |

### Se även

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


