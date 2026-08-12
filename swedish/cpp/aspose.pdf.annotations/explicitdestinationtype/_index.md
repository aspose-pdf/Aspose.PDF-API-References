---
title: "Aspose::Pdf::Annotations::ExplicitDestinationType enum"
linktitle: "ExplicitDestinationType"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::ExplicitDestinationType enum. Enumererar typerna av explicita destinationer i C++."
type: docs
weight: 13100
url: /sv/cpp/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enum


Enumererar typerna av explicita destinationer.

```cpp
enum class ExplicitDestinationType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| XYZ | 0 | Visa sidan med koordinaterna (vänster, topp) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorat med zoom‑faktorn. Ett null‑värde för någon av parametrarna vänster, topp eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoom‑värde på 0 har samma betydelse som ett null‑värde. |
| Fit | 1 | Visa sidan med dess innehåll förstorat precis så att hela sidan får plats i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringarna är olika, använd den mindre av dem och centrera sidan i fönstret i den andra dimensionen. |
| FitH | 2 | Visa sidan med den vertikala koordinaten topp placerad vid fönstrets överkant och sidans innehåll förstorat precis så att hela sidans bredd får plats i fönstret. Ett null‑värde för topp anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitV | 3 | Visa sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat tillräckligt för att passa hela sidans höjd inom fönstret. Ett nullvärde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitR | 4 | Visa sidan med dess innehåll förstorat tillräckligt för att den rektangel som anges av koordinaterna left, bottom, right och top får plats helt inom fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstorningsfaktorerna är olika, använd den mindre av de två och centrera rektangeln inom fönstret i den andra dimensionen. Ett nullvärde för någon av parametrarna kan leda till oförutsägbart beteende. |
| FitB | 5 | Visa sidan med dess innehåll förstorat tillräckligt för att dess begränsningsruta får plats helt inom fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstorningsfaktorerna är olika, använd den mindre av de två och centrera begränsningsrutan inom fönstret i den andra dimensionen. |
| FitBH | 6 | Visa sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstorat tillräckligt för att den hela bredden av dess begränsningsruta får plats inom fönstret. Ett nullvärde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FitBV | 7 | Visa sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat tillräckligt för att den hela höjden av dess begränsningsruta får plats inom fönstret. Ett nullvärde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |

## Se även

* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
