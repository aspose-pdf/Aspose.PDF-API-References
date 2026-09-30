---
title: "BoundsCheckableList<T> Class"
linktitle: "BoundsCheckableList<T>"
articleTitle: "BoundsCheckableList<T>"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.BoundsCheckableList class. Represents BoundsCheckableList - wrapper around System.Collections.Generic.List."
type: docs
weight: 220
url: "/net/aspose.pdf/boundscheckablelist-1/"
keywords: "BoundsCheckableList<T>, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## BoundsCheckableList&lt;T&gt; class

Represents BoundsCheckableList - wrapper around System.Collections.Generic.List.

```csharp
public class BoundsCheckableList<T> : IList<T>
    where T : IBoundsCheckableItem
```

## Type Parameters

| Name | Description |
| --- | --- |
| T |  |

## Constructors

| Name | Description |
| --- | --- |
| [BoundsCheckableList](./boundscheckablelist/#constructor)() | Initializes a new instance of the BoundsCheckableList class. |
| [BoundsCheckableList](./boundscheckablelist/#constructor_1)(BoundsCheckMode, double, double) | Initializes a new instance of the BoundsCheckableList class. |

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets the number of elements contained in the System.Collections.Generic.List. |
| [IsReadOnly](./isreadonly/) { get; } | Gets the value indicating if collection is readonly. |
| [Item](./item/) { get; set; } | Gets or sets paragraph from or to collection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(T) | Adds an object to the end of the System.Collections.Generic.List depending on "boundsCheckMode" parameter. |
| [Clear](./clear/)() | Removes all elements from the System.Collections.Generic.List. |
| [Contains](./contains/)(T) | Determines whether an element is in the System.Collections.Generic.List. |
| [CopyTo](./copyto/)(T[], int) |  |
| [GetEnumerator](./getenumerator/)() | Returns an enumerator that iterates through the System.Collections.Generic.List. |
| [IndexOf](./indexof/)(T) | Searches for the specified object and returns the zero-based index of the first occurrence within the entire System.Collections.Generic.List. |
| [Insert](./insert/)(int, T) | Inserts an element into the System.Collections.Generic.List at the specified index. |
| [Remove](./remove/)(T) | Removes the first occurrence of a specific object from the System.Collections.Generic.List. |
| [RemoveAt](./removeat/)(int) | Removes the element at the specified index of the System.Collections.Generic.List. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode) | Updates boundsCheckMode parameter for initialized collection. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode, double, double) | Updates boundsCheckMode parameter for initialized collection. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

