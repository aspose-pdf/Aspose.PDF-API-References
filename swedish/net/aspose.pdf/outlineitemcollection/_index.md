---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineItemCollection klass. Representerar en outline-post i outline-hierarkin av PDF-dokument
type: docs
weight: 8010
url: /sv/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection klass

Representerar en outline-post i outline-hierarkin av PDF-dokument.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Initierar en instans av outline-objektet med hjälp av rot-hierarkin. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Hämtar eller sätter åtgärden för denna outline-post. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Hämtar eller sätter fetstilflagga för titeltexten av denna outline-post |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Hämtar eller sätter färgen för titeltexten av denna outline-post. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Antal objekt i samlingen. Vänligen förväxla inte med VisibleCount: VisibleCount hämtar antalet synliga outline-poster på alla nivåer. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Hämtar eller sätter destinationen för denna outline-post. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Hämtar outline-posten som representerar det första översta objektet i outline-hierarkin. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Kontrollerar om outline-posten representerar nästa objekt relativt denna post i outline-hierarkin. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Hämtar värdet som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Hämtar eller sätter kursivflagga för titeltexten av denna outline-post |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Hämtar outline-posten från samlingen med hjälp av index. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Hämtar outline-posten som representerar det sista översta objektet i outline-hierarkin. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Hämtar hierarkisk nivå av outline-posten. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Hämtar outline-posten som representerar nästa objekt relativt denna post i outline-hierarkin. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Hämtar eller sätter öppet status (true/false) för outline-posten. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Hämtar föräldraobjektet för denna outline-post i outline-hierarkin. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Hämtar outline-posten som representerar föregående objekt relativt denna post i outline-hierarkin. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Hämtar objektet som kan användas för att synkronisera åtkomst till denna samling. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Hämtar eller sätter titeln för denna outline-post. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Hämtar det totala antalet outline-poster på alla nivåer i dokumentets outline-hierarki. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Lägger till outline-posten i samlingen. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Rensar alla objekt från samlingen. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Kontrollerar om samlingen innehåller angivet objekt. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Kopierar outline-poster till en System.Array, som börjar vid ett visst System.Array-index. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Tar bort denna outline-post från dokumentets outline-hierarki. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Tar bort outline-posten med angivet namn från dokumentets outline-hierarki. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Infogar outline-posten i samlingen på den angivna platsen. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Tar bort objektet med index. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Tar bort outline-samlingsobjektet. |

### Se Även

* klass [Outlines](../outlines/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../aspose.pdf/)