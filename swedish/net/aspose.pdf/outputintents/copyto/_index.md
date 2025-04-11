---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents metod. Kopierar elementen i samlingen till arrayen som börjar vid det specifika arrayIndex i arrayen
type: docs
weight: 70
url: /sv/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo metod

Kopierar elementen i samlingen till *arrayen*, som börjar vid det specifika *arrayIndex* i arrayen.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | OutputIntent[] | Den endimensionella arrayen som är destinationen för output intents kopierade från samlingen. Arrayen måste ha nollbaserad indexering. |
| arrayIndex | Int32 | Den nollbaserade index i *arrayen* där kopieringen börjar. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *array* är null. |
| ArgumentOutOfRangeException | *arrayIndex* är mindre än 0. |
| ArgumentException | Antalet element i källan [`OutputIntents`](../) är större än det tillgängliga utrymmet från *arrayIndex* till slutet av destinationen *array*. |

### Se Även

* klass [OutputIntent](../../outputintent/)
* klass [OutputIntents](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)