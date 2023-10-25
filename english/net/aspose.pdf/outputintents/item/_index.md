---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents property. Gets the output intent at the specified index
type: docs
weight: 30
url: /net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

Gets the output intent at the specified *index*.

```csharp
public OutputIntent this[int index] { get; }
```

| Parameter | Description |
| --- | --- |
| index | The zero-based index of the output intent to get. |

### Return Value

The output intent at the specified *index*.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* is less than 0 or *index* is equal to or greater than [`Count`](../count/). |
| InvalidOperationException | The document that contains the collection has no catalog to access the OutputIntents. |

### See Also

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


