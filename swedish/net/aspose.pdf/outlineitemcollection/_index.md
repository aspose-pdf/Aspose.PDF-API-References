---
title: "Klass OutlineItemCollection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.OutlineItemCollection klass. Representerar post i outline-hierarkin för PDF-dokument."
type: docs
weight: 8150
url: /sv/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

Representerar ett dispositionsinlägg i dispositionshierarkin för ett PDF-dokument.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Initierar outline-item-instans med rot-hierarkiobjekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Hämtar eller anger åtgärden för detta outline-item. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Hämtar eller anger fetstilflagga för titeltexten för detta outline-item |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Hämtar eller anger färgen för titeltexten för detta outline-item. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Antal objekt i samlingen. Vänligen förväxla inte med VisibleCount: VisibleCount får antalet synliga dispositionsobjekt på alla nivåer. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Hämtar eller anger destinationen för detta outline-item. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Hämtar outline-item som representerar det första toppnivå-objektet i outline-hierarkin. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Kontrollerar om outline-item representerar nästa objekt relativt detta objekt i outline-hierarkin. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Hämtar värdet som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Hämtar eller anger kursivflagga för titeltexten för detta outline-item. |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Hämtar outline-item från samlingen med hjälp av index. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Hämtar outline-item som representerar det sista toppnivå-objektet i outline-hierarkin. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Hämtar hierarkinivå för outline-item. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Hämtar outline-item som representerar nästa objekt relativt detta objekt i outline-hierarkin. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Hämtar eller anger öppetillstånd (true/false) för outline-item. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Hämtar föräldraobjektet för detta outline-item i outline-hierarkin. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Hämtar outline-item som representerar föregående objekt relativt detta objekt i outline-hierarkin. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Hämtar objektet som kan användas för att synkronisera åtkomst till denna samling. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Hämtar eller anger titeln för detta outline-item. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Hämtar det totala antalet outline-items på alla nivåer i dokumentets outline-hierarki. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Lägger till ett dispositionsobjekt i samlingen. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Rensar alla objekt från samlingen. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Kontrollerar om samlingen innehåller angivet objekt. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Kopierar outline-poster till en System.Array, med start vid ett specifikt System.Array-index. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Tar bort detta outline-item från dokumentets outline-hierarki. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Tar bort outline-post med angivet namn från dokumentets outline-hierarki. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Infogar outline-item i samlingen på den angivna platsen. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Ta bort objektet efter index. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Ta bort outline-samlingens objekt. |

### Se även

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


