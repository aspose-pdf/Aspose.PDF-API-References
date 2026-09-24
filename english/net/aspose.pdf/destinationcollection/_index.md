---
title: "DestinationCollection Class"
linktitle: "DestinationCollection"
articleTitle: "DestinationCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.DestinationCollection class. Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, ..."
type: docs
weight: 540
url: "/net/aspose.pdf/destinationcollection/"
keywords: "DestinationCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## DestinationCollection class

Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document.

```csharp
public sealed class DestinationCollection : IEnumerable
```

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets the number of elements contained in the collection. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| [Item](./item/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(*KeyValuePair<string, object>*) | Adds the specified item. |
| [Clear](./clear/) | Collection is read-only. Always throws NotSupportedException exception. |
| [Contains](./contains/)(*KeyValuePair<string, object>*) | Determines whether this instance contains the object. |
| [CopyTo](./copyto/)(*KeyValuePair<string, object>[], int*) |  |
| [GetEnumerator](./getenumerator/) | Returns the enumerator. |
| [GetExplicitDestination](./getexplicitdestination/)(*string, bool*) | Returns the explicit destination by the name. |
| [GetPageNumber](./getpagenumber/)(*string, bool*) | Returns the page number of destination by the name. |
| [IndexOf](./indexof/)(*KeyValuePair<string, object>*) | Returns the index of destination in collection. |
| [Remove](./remove/)(*KeyValuePair<string, object>*) | Removes the specified item. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

