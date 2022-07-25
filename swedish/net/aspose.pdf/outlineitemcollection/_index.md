---
title: OutlineItemCollection
second_title: Aspose.PDF för .NET API Referens
description: Representerar konturpost i konturhierarkin för PDF-dokument.
type: docs
weight: 5770
url: /sv/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

Representerar konturpost i konturhierarkin för PDF-dokument.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection)(OutlineCollection) | Initierar dispositionsförekomst med hjälp av rothierarkiobjekt. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action) { get; set; } | Hämtar eller ställer in åtgärden för detta dispositionsobjekt. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold) { get; set; } | Får eller ställer in fet flagga för titeltexten för denna dispositionsartikel |
| [Color](../../aspose.pdf/outlineitemcollection/color) { get; set; } | Hämtar eller ställer in färgen för titeltexten för detta dispositionsobjekt. |
| override [Count](../../aspose.pdf/outlineitemcollection/count) { get; } | Antal samlingsobjekt. Blanda inte ihop med VisibleCount: VisibleCount får antalet synliga dispositionsobjekt på alla nivåer. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination) { get; set; } | Hämtar eller ställer in destinationen för denna disposition. |
| [First](../../aspose.pdf/outlineitemcollection/first) { get; } | Hämtar dispositionsobjektet som representerar det första objektet på toppnivå i dispositionshierarkin. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext) { get; } | Kontrollera om dispositionsobjektet representerar nästa objekt relativt detta objekt i dispositionshierarkin. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly) { get; } | Får ett värde som indikerar om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized) { get; } | Hämtar värdet som anger om åtkomst till denna samling är synkroniserad (trådsäker). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic) { get; set; } | Hämtar eller sätter kursiv flagga för titeltexten för denna dispositionsartikel |
| [Item](../../aspose.pdf/outlineitemcollection/item) { get; } | Hämtar dispositionsobjekt från samlingen med hjälp av index. |
| [Last](../../aspose.pdf/outlineitemcollection/last) { get; } | Hämtar dispositionsobjektet som representerar det sista objektet på toppnivå i dispositionshierarkin. |
| [Level](../../aspose.pdf/outlineitemcollection/level) { get; } | Får hierarkinivå för dispositionsobjektet. |
| [Next](../../aspose.pdf/outlineitemcollection/next) { get; } | Hämtar dispositionsobjektet som representerar nästa objekt relativt detta objekt i dispositionshierarkin. |
| [Open](../../aspose.pdf/outlineitemcollection/open) { get; set; } | Hämta eller ställer in öppen status (sant/falskt) för dispositionsobjekt. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent) { get; } | Hämtar det överordnade objektet för detta dispositionsobjekt i dispositionshierarkin. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev) { get; } | Hämtar dispositionsobjektet som representerar föregående objekt relativt detta objekt i dispositionshierarkin. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot) { get; } | Hämtar objektet som kan användas för att synkronisera åtkomst till denna samling. |
| [Title](../../aspose.pdf/outlineitemcollection/title) { get; set; } | Hämtar eller ställer in titeln för detta dispositionsobjekt. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount) { get; } | Hämtar det totala antalet dispositionsobjekt på alla nivåer i dokumentets dispositionshierarkin. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add)(OutlineItemCollection) | Lägger till dispositionsobjekt till samlingen. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear)() | Rensar alla objekt från samlingen. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains)(OutlineItemCollection) | Kontrollerar om samlingen innehåller ett visst föremål. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto)(OutlineItemCollection[], int) | Kopierar konturposterna till en System.Array, med början på ett visst System.Array-index. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete#delete)() | Tar bort denna disposition från dokumentets dispositionshierarki. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete#delete_1)(string) | Tar bort konturpost med angivet namn från dokumentkonturhierarkin. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert)(int, OutlineItemCollection) | Infogar dispositionsobjektet i samlingen på angiven plats. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove#remove_1)(int) | Ta bort objekt efter index. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove#remove)(OutlineItemCollection) | Ta bort kontursamlingsobjekt. |

### Se även

* class [Outlines](../outlines)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
