---
title: "Klass OutlineCollection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.OutlineCollection-klass. Representerar dokumentets dispositionshierarki"
type: docs
weight: 8140
url: /sv/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

Representerar dokumentets dispositionshierarki.

```csharp
public sealed class OutlineCollection : Outlines
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Antal objekt i samlingen. Vänligen förväxla inte med VisibleCount: VisibleCount får antalet synliga dispositionsobjekt på alla nivåer. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Hämtar ett dispositionsobjekt som representerar det första top‑nivåobjektet i dispositionen. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Hämtar ett dispositionsobjekt från samlingen efter index. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Hämtar ett dispositionsobjekt som representerar det sista top‑nivåobjektet i dispositionen. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Antal är summan av antalet synliga underordnade dispositionsobjekt på alla nivåer. Obs: förväxla inte med Count som är antalet objekt i samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Lägger till ett dispositionsobjekt i samlingen. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Rensar alla objekt från samlingen. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Kontrollerar om samlingen innehåller det angivna objektet. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Kopierar dispositionsobjekten till en System.Array, med start vid ett specifikt System.Array-index. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Raderar alla dispositionsobjekt från dokumentets disposition. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Raderar dispositionsobjektet med angiven titel från dokumentets disposition. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Ta bort objektet efter index. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Kastar alltid NotImplementedException |

### Se även

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


