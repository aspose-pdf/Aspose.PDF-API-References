---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineCollection klass. Representerar dokumentets strukturhierarki
type: docs
weight: 8000
url: /sv/net/aspose.pdf/outlinecollection/
---
## OutlineCollection klass

Representerar dokumentets strukturhierarki.

```csharp
public sealed class OutlineCollection : Outlines
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Antal objekt i samlingen. Vänligen förväxla inte med VisibleCount: VisibleCount får antalet synliga strukturobjekt på alla nivåer. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Hämtar ett strukturobjekt som representerar det första översta objektet i strukturen. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Hämtar strukturobjekt från samlingen efter index. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Hämtar ett strukturobjekt som representerar det sista översta objektet i strukturen. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Antalet är summan av antalet synliga underordnade strukturobjekt på alla nivåer. Observera: vänligen förväxla inte med Count som är antalet objekt i samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Lägger till strukturobjekt i samlingen. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Rensar alla objekt från samlingen. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Kontrollerar om samlingen innehåller det angivna objektet. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Kopierar strukturobjekten till en System.Array, med början vid ett särskilt System.Array-index. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Tar bort alla strukturobjekt från dokumentets struktur. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Tar bort strukturobjektet med angiven titel från dokumentets struktur. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Tar bort objekt efter index. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Kastar alltid NotImplementedException |

### Se Även

* klass [Outlines](../outlines/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)