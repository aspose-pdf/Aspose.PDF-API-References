---
title: "Aspose::Pdf::Facades::DefaultMetadataProperties enum"
linktitle: "DefaultMetadataProperties"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::DefaultMetadataProperties enum. Uppräkning av standard XMP-egenskaper i C++."
type: docs
weight: 4300
url: /sv/cpp/aspose.pdf.facades/defaultmetadataproperties/
---
## DefaultMetadataProperties enum


Enumeration av standard-XMP-egenskaper.

```cpp
enum class DefaultMetadataProperties
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Advisory | 0 | xmp:Advisory property. En oordnad array som specificerar egenskaper som redigerades utanför författarprogrammet. Varje objekt bör innehålla ett enda /// namnrymd och XPath separerade med ett ASCII-mellanslag |
| BaseURL | 1 | xmp:BaseURL property. Bas-URL:en för relativa URL:er i dokumentets innehåll. Om detta dokument innehåller internetlänkar och dessa länkar är relativa, /// så är de relativa till denna bas-URL. Denna egenskap tillhandahåller ett standardiserat sätt för inbäddade relativa URL:er att tolkas av verktyg. /// Webbutvecklingsverktyg bör sätta värdet baserat på deras uppfattning om var URL:er kommer att tolkas |
| CreateDate | 2 | xmp:CreateDate property. Datum och tid då resursen ursprungligen skapades. |
| CreatorTool | 3 | xmp:CreatorTool property. Namnet på det första kända verktyget som användes för att skapa resursen. |
| Identifier | 4 | xmp:Identifier-egenskap. En oordnad matris av textsträngar som entydigt identifierar resursen inom en given kontext |
| MetadataDate | 5 | xmp:MetadataDate-egenskap. Datum och tid då någon metadata för denna resurs senast ändrades |
| ModifyDate | 6 | xmp:ModifyDate-egenskap. Datum och tid då resursen senast modifierades. |
| Nickname | 7 | xmp:Nickname-egenskap. Ett kort informellt namn för resursen. |
| Thumbnails | 8 | xmp:Thumbnails-egenskap. En alternativ matris av miniatyrbilder för en fil, som kan skilja sig i egenskaper såsom storlek eller bildkodning. |

## Se även

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
