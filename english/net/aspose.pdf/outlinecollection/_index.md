---
title: "OutlineCollection Class"
linktitle: "OutlineCollection"
articleTitle: "OutlineCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.OutlineCollection class. Represents document outline hierarchy."
type: docs
weight: 2060
url: "/net/aspose.pdf/outlinecollection/"
keywords: "OutlineCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OutlineCollection class

Represents document outline hierarchy.

```csharp
public sealed class OutlineCollection : Outlines
```

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Count of collection items. Please dont confuse with VisibleCount: VisibleCount gets number of visible outline item on all levels. |
| [First](./first/) { get; } | Gets an outline item representing the first top-level item in the outline. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| [IsSynchronized](./issynchronized/) { get; } | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [Item](./item/) { get; } | Gets outline item from collection by index. |
| [Last](./last/) { get; } | Gets an outline item representing the last top-level item in the outline. |
| [SyncRoot](./syncroot/) { get; } | Gets an object that can be used to synchronize access to this collection. |
| [VisibleCount](./visiblecount/) { get; } | Count is the sum of the number of visible descendent outline items at all levels. Note: please don't confuse with Count which is number if items in collection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(*OutlineItemCollection*) | Adds outline item to collection. |
| [Clear](./clear/) | Clears all items from the collection. |
| [Contains](./contains/)(*OutlineItemCollection*) | Checks does collection contains given item. |
| [CopyTo](./copyto/)(*OutlineItemCollection[], int*) | Copies the outline items to an System.Array, starting at a particular System.Array index. |
| [Delete](./delete/) | Deletes all outline items from the document outline. |
| [Delete](./delete/)(*string*) | Deletes the outline item with specified title from the document outline. |
| [GetEnumerator](./getenumerator/) | Returns an enumerator that iterates through the collection. |
| [Remove](./remove/)(*OutlineItemCollection*) | Always throws NotImplementedException. |
| [Remove](./remove/)(*int*) | Remove item by index. |

### See Also

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

