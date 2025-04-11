---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.ExplicitDestinationType enum. Uppräkning av typer av explicita destinationer
type: docs
weight: 1690
url: /sv/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType uppräkning

Uppräkning av typer av explicita destinationer.

```csharp
public enum ExplicitDestinationType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| XYZ | `0` | Visa sidan med koordinaterna (vänster, topp) placerade i det övre vänstra hörnet av fönstret och innehållet på sidan förstorad med faktorn zoom. Ett nullvärde för någon av parametrarna vänster, topp eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoomvärde på 0 har samma betydelse som ett nullvärde. |
| Fit | `1` | Visa sidan med sitt innehåll förstorad precis tillräckligt för att passa hela sidan inom fönstret både horisontellt och vertikalt. Om de nödvändiga horisontella och vertikala förstoringsfaktorerna är olika, använd den mindre av de två, centrera sidan inom fönstret i den andra dimensionen. |
| FitH | `2` | Visa sidan med den vertikala koordinaten topp placerad vid den övre kanten av fönstret och innehållet på sidan förstorad precis tillräckligt för att passa hela bredden av sidan inom fönstret. Ett nullvärde för topp anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitV | `3` | Visa sidan med den horisontella koordinaten vänster placerad vid den vänstra kanten av fönstret och innehållet på sidan förstorad precis tillräckligt för att passa hela höjden av sidan inom fönstret. Ett nullvärde för vänster anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitR | `4` | Visa sidan med sitt innehåll förstorad precis tillräckligt för att passa rektangeln som specificeras av koordinaterna vänster, botten, höger och topp helt inom fönstret både horisontellt och vertikalt. Om de nödvändiga horisontella och vertikala förstoringsfaktorerna är olika, använd den mindre av de två, centrera rektangeln inom fönstret i den andra dimensionen. Ett nullvärde för någon av parametrarna kan resultera i oförutsägbart beteende. |
| FitB | `5` | Visa sidan med sitt innehåll förstorad precis tillräckligt för att passa dess avgränsningsruta helt inom fönstret både horisontellt och vertikalt. Om de nödvändiga horisontella och vertikala förstoringsfaktorerna är olika, använd den mindre av de två, centrera avgränsningsrutan inom fönstret i den andra dimensionen. |
| FitBH | `6` | Visa sidan med den vertikala koordinaten topp placerad vid den övre kanten av fönstret och innehållet på sidan förstorad precis tillräckligt för att passa hela bredden av dess avgränsningsruta inom fönstret. Ett nullvärde för topp anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitBV | `7` | Visa sidan med den horisontella koordinaten vänster placerad vid den vänstra kanten av fönstret och innehållet på sidan förstorad precis tillräckligt för att passa hela höjden av dess avgränsningsruta inom fönstret. Ett nullvärde för vänster anger att det aktuella värdet för den parametern ska behållas oförändrat. |

### Se Även

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)