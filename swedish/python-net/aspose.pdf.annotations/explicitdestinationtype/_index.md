---
title: "ExplicitDestinationType"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Enumererar typerna av explicita destinationer."
type: docs
weight: 1020
url: /sv/python-net/aspose.pdf.annotations/explicitdestinationtype/
---

## ExplicitDestinationType enumeration

Enumererar typerna av explicita destinationer.

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| XYZ | Visa sidan med koordinaterna (left, top) placerade i fönstrets övre vänstra hörn<br/>            och sidans innehåll förstorat med faktorn zoom. Ett null‑värde för någon av parametrarna<br/>            left, top eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. <br/>            Ett zoom‑värde på 0 har samma betydelse som ett null‑värde. |
| FIT | Visa sidan med dess innehåll förstorat precis så mycket att hela sidan får plats i fönstret<br/>            både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är<br/>            olika, använd den mindre av de två och centrera sidan i fönstret i den andra dimensionen. |
| FIT_H | Visa sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och<br/>            sidans innehåll förstorat precis tillräckligt för att passa hela sidans bredd inom fönstret.<br/>            Ett null-värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FIT_V | Visa sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant<br/>            och sidans innehåll förstorat precis tillräckligt för att passa hela sidans höjd inom fönstret.<br/>            Ett null-värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FIT_R | Visa sidan med dess innehåll förstorat precis tillräckligt för att passa den rektangel som anges av<br/>            koordinaterna left, bottom, right och top helt inom fönstret både horisontellt och vertikalt.<br/>            Om de erforderliga horisontella och vertikala förstorningsfaktorerna är olika, använd den mindre av<br/>            de två och centrera rektangeln inom fönstret i den andra dimensionen. Ett null-värde för någon<br/>            av parametrarna kan leda till oförutsägbart beteende. |
| FIT_B | Visa sidan med dess innehåll förstorat precis tillräckligt för att passa dess begränsningsruta helt inom<br/>            fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstorningsfaktorerna är olika, använd den mindre av de två och centrera begränsningsrutan inom fönstret i den andra dimensionen. |
| FIT_BH | Visa sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och<br/>            sidans innehåll förstorat precis tillräckligt för att passa hela bredden av dess begränsningsruta inom fönstret.<br/>            Ett null-värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat. |
| FIT_BV | Visa sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och<br/>            sidans innehåll förstorat precis tillräckligt för att passa hela höjden av dess begränsningsruta inom fönstret.<br/>            Ett null-värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat. |

### Se även

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

