---
title: "AppearanceDictionary"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Annoteringsutseendedictionary som specificerar hur annoteringen ska presenteras visuellt på sidan."
type: docs
weight: 60
url: /sv/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Annoteringsutseendedictionary som specificerar hur annoteringen ska presenteras visuellt på sidan.

Typen AppearanceDictionary exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_fixed_size | Hämtar ett värde som indikerar om ordboken har en fast storlek. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | D).state‑värden,<br/>            där N - normal utseende, R - rullningsutseende, D - nedtryckt utseende och state - namnet på tillståndet<br/>            (t.ex. På, Av för kryssrutor). |
| värden | Hämtar listan över ordbokens värden. <br/>            Resultatsamlingen innehåller listan över XForm‑objekt. |
| is_synchronized | Hämtar ett värde som indikerar om åtkomst till ordboken är synkroniserad (trådsäker). |
| sync_root | Hämtar ett objekt som kan användas för att synkronisera åtkomst till ordboken. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| add(key, value) | Lägger till ett element med den angivna nyckeln och värdet. |
| add(key, value) | Lägg till X‑form för angiven nyckel. |
| copy_to(array, index) | Kopierar elementen i ordboken till en Array, med start vid ett specifikt Array‑index. |
| contains_key(key) | Bestämmer om denna ordbok innehåller den angivna nyckeln. |
| remove(key) | Tar bort nyckel från ordboken. |
| try_get_value(key, value) | Försöker hitta nyckeln i ordboken och hämtar värdet om det hittas. |

### Se även

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

