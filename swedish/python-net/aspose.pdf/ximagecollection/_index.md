---
title: "XImageCollection"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen som representerar XImage-samling."
type: docs
weight: 1690
url: /sv/python-net/aspose.pdf/ximagecollection/
---

## XImageCollection class

Klassen som representerar XImage-samling.

Typen XImageCollection exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_synchronized | Returnerar true om objektet är synkroniserat. |
| sync_root | Returnerar synkroniseringsobjekt. |
| names | Hämtar en array med bildnamn. |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar bild från samlingen enligt dess index. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| add(image) | Lägger till en ny bild i bildlistan. Denna metod lägger till bilden som referens till samma PdfObject (vilket möjliggör att minska filstorleken) |
| add(image) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| add(image, filter_type) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| add(image, quality) | Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet. |
| delete(index) | Tar bort ett index från samlingen med index. |
| delete(index, action) | Tar bort bilden från samlingen med index och utför den åtgärd som anges av parametern action. |
| delete(name) | Tar bort objektet från samlingen med namn. |
| delete(name, action) | Tar bort objektet från samlingen med namn. |
| delete() | Tar bort ett index från samlingen med index. |
| replace(index, stream) | Ersätt bilden i samlingen med en annan bild. |
| replace(index, stream, quality, is_black_and_white) | Ersätt bilden i samlingen med en annan bild. |
| replace(index, stream, quality) | Ersätt bilden i samlingen med en annan bild. |
| get_image_name(image) | Returnerar namn i bildlistan som är nyckeln för den angivna bilden. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

