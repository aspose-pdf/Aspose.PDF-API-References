---
title: "PageCollection"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Samling av PDF-dokumentsidor."
type: docs
weight: 1100
url: /sv/python-net/aspose.pdf/pagecollection/
---

## PageCollection class

Samling av PDF-dokumentsidor.

PageCollection-typen exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_synchronized | Returnerar true om objektet är synkroniserat. |
| sync_root | Hämtar synkroniseringsobjektet för samlingen. |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar sidan efter index. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| add(entity) | Lägger till sidan i samlingen. |
| add() | Lägger till sidan i samlingen. |
| add(pages) | Lägger till alla sidor från listan i samlingen. |
| add(pages) | Lägger till alla sidor från arrayen i samlingen. |
| delete(index) | Raderar angiven sida. |
| delete() | Raderar angiven sida. |
| delete(pages) | Raderar sidor vars nummer anges i arrayen. |
| accept(visitor) | Accepterar [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer. |
| accept(visitor) | Accepterar [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt. |
| accept(visitor) | Accepterar [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| accept(visitor) | Accepterar [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| insert(page_number) | Infogar en tom sida i samlingen på den angivna positionen. |
| insert(page_number, entity) | Infogar en tom sida i samlingen på den angivna positionen. |
| insert(page_number, pages) | Infogar sidor från samlingen i dokumentet. |
| insert(page_number, pages) | Infogar sidor från arrayen i dokumentet. |
| index_of(entity) | Returnerar index för den angivna sidan. |
| flatten() | Tar bort alla fält som finns på sidorna och placerar deras värden istället. |
| free_memory() | Rensar cachad data. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

