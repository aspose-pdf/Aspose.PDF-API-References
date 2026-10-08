---
title: "OutputIntents.CopyTo"
linktitle: "CopyTo"
articleTitle: "CopyTo"
second_title: "Aspose.PDF for .NET API Reference"
description: "OutputIntents method. Copies the elements of the collection to the array,starting at the particular arrayIndex into the array."
type: docs
weight: 40
url: "/net/aspose.pdf/outputintents/copyto/"
product_version: "26.9"
---
## OutputIntents.CopyTo method

Copies the elements of the collection to the *array*,starting
 at the particular *arrayIndex* into the array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| array | OutputIntent[] | The one-dimensional array that is the destination of the output intents copied from the collection. The array must have zero-based indexing. |
| arrayIndex | Int32 | The zero-based index in *array* at which copying begins. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *array* is null. |
| ArgumentOutOfRangeException | *arrayIndex* is less than 0. |
| ArgumentException | The number of elements in the source `OutputIntents` is greater than the available space from *arrayIndex* to the end of the destination *array*. |

### See Also

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

