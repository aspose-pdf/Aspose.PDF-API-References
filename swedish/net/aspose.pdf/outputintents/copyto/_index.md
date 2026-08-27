---
title: "OutputIntents.CopyTo"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OutputIntents‑metod. Kopierar elementen i samlingen till arrayen med start vid det angivna arrayIndex till arrayen"
type: docs
weight: 70
url: /sv/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

Kopierar elementen i samlingen till *array*, med start vid det specifika *arrayIndex* i arrayen.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | OutputIntent[] | Den endimensionella arrayen som är destinationen för de output‑intents som kopierats från samlingen. Arrayen måste ha nollbaserad indexering. |
| arrayIndex | Int32 | Det nollbaserade indexet i *array* där kopieringen börjar. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *array* är null. |
| ArgumentOutOfRangeException | *arrayIndex* är mindre än 0. |
| ArgumentException | Antalet element i källan [`OutputIntents`](../) är större än det tillgängliga utrymmet från *arrayIndex* till slutet av destinationen *array*. |

### Se även

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


