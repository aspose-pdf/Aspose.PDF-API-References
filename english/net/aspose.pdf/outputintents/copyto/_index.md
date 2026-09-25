---
title: "OutputIntents.CopyTo"
linktitle: "CopyTo"
articleTitle: "CopyTo"
second_title: "Aspose.PDF for .NET API Reference"
description: "OutputIntents method. Copies the elements of the collection to the array,starting at the particular arrayIndex into the array."
type: docs
weight: 40
url: "/net/aspose.pdf/outputintents/copyto/"
product_version: "26.9.0"
---
## CopyTo(OutputIntent[], int) {#copyto}

Copies the elements of the collection to the *array*,starting
 at the particular *arrayIndex* into the array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| array | OutputIntent[] | The one-dimensional array that is the destination of the output intents copied
 from the collection. The array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in *array* at which copying begins. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *array* is null. |
| ArgumentOutOfRangeException | *arrayIndex* is less than 0. |
| ArgumentException | The number of elements in the source <see cref="T:Aspose.Pdf.OutputIntents" /> is greater than the available space
 from *arrayIndex* to the end of the destination *array*. |

### See Also

* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

