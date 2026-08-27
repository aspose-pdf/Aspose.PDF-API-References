---
title: "OutputIntents.Item"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OutputIntents‑egenskap. Hämtar output‑intentet på det angivna indexet."
type: docs
weight: 30
url: /sv/net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

Hämtar output‑intent på det angivna *indexet*.

```csharp
public OutputIntent this[int index] { get; }
```

| Parameter | Beskrivning |
| --- | --- |
| index | Det nollbaserade indexet för output‑intentet som ska hämtas. |

### Returvärde

Output‑intentet på det angivna *index*.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *index* är mindre än 0 eller *index* är lika med eller större än [`Count`](../count/). |
| InvalidOperationException | Dokumentet som innehåller samlingen har ingen katalog för att komma åt OutputIntents. |

### Se även

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


