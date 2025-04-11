---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents-egenskap. Hämtar output intent vid det angivna indexet
type: docs
weight: 30
url: /sv/net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

Hämtar output intent vid det angivna *indexet*.

```csharp
public OutputIntent this[int index] { get; }
```

| Parameter | Beskrivning |
| --- | --- |
| index | Det nollbaserade indexet för output intent som ska hämtas. |

### Returvärde

Output intent vid det angivna *indexet*.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *index* är mindre än 0 eller *index* är lika med eller större än [`Count`](../count/). |
| InvalidOperationException | Dokumentet som innehåller samlingen har ingen katalog för att få åtkomst till OutputIntents. |

### Se Även

* klass [OutputIntent](../../outputintent/)
* klass [OutputIntents](../)
* namnrum [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)