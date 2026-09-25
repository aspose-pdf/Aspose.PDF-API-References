---
title: "OutlineItemCollection Class"
linktitle: "OutlineItemCollection"
articleTitle: "OutlineItemCollection"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.OutlineItemCollection class. Represents outline entry in outline hierarchy of PDF document."
type: docs
weight: 2070
url: "/net/aspose.pdf/outlineitemcollection/"
keywords: "OutlineItemCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OutlineItemCollection class

Represents outline entry in outline hierarchy of PDF document.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Constructors

| Name | Description |
| --- | --- |
| [OutlineItemCollection](./outlineitemcollection/#constructor)(*[OutlineCollection](../../aspose.pdf/outlinecollection/)*) | Initializes outline item instance using root hierarchy object. |

## Properties

| Name | Description |
| --- | --- |
| [Action](./action/) { get; set; } | Gets or sets the action for this outline item. |
| [Bold](./bold/) { get; set; } | Gets or sets bold flag for the title text of this outline item. |
| [Color](./color/) { get; set; } | Gets or sets the color for the title text of this outline item. |
| [Count](./count/) { get; } | Count of collection items. Please dont confuse with VisibleCount: VisibleCount gets number of visible outline item on all levels. |
| [Destination](./destination/) { get; set; } | Gets or sets the destination for this outline item. |
| [First](./first/) { get; } | Gets the outline item representing the first top-level item in the outline hierarchy. |
| [HasNext](./hasnext/) { get; } | Check if outline item representing next item relatively this item in the outline hierarchy. |
| [IsReadOnly](./isreadonly/) { get; } | Gets a value indicating whether the collection is read-only. |
| [IsSynchronized](./issynchronized/) { get; } | Gets the value indicating whether access to this collection is synchronized (thread safe). |
| [Italic](./italic/) { get; set; } | Gets or sets italic flag for the title text of this outline item. |
| [Item](./item/) { get; } | Gets outline item from the collection using index. |
| [Last](./last/) { get; } | Gets the outline item representing the last top-level item in the outline hierarchy. |
| [Level](./level/) { get; } | Gets hierarchy level of outline item. |
| [Next](./next/) { get; } | Gets the outline item representing next item relatively this item in the outline hierarchy. |
| [Open](./open/) { get; set; } | Get or sets open status (true/false) for outline item. |
| [Parent](./parent/) { get; } | Gets the parent object of this outline item in the outline hierarchy. |
| [Prev](./prev/) { get; } | Gets the outline item representing previous item relatively this item in the outline hierarchy. |
| [SyncRoot](./syncroot/) { get; } | Gets the object that can be used to synchronize access to this collection. |
| [Title](./title/) { get; set; } | Gets or sets the title for this outline item. |
| [VisibleCount](./visiblecount/) { get; } | Gets the total number of outline items at all levels in the document outline hierarchy. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(*OutlineItemCollection*) | Adds outline item to collection. |
| [Clear](./clear/) | Clears all items from the collection. |
| [Contains](./contains/)(*OutlineItemCollection*) | Checks if collection contains given item. |
| [CopyTo](./copyto/)(*OutlineItemCollection[], int*) | Copies the outline entries to an System.Array, starting at a particular System.Array index. |
| [Delete](./delete/) | Deletes this outline item from the document outline hierarchy. |
| [Delete](./delete/)(*string*) | Deletes outline entry with specified name from the document outline hierarchy. |
| [GetEnumerator](./getenumerator/) | Returns an enumerator that iterates through the collection. |
| [Insert](./insert/)(*int, OutlineItemCollection*) | Inserts the outline item into collection at the specified place. |
| [Remove](./remove/)(*OutlineItemCollection*) | Remove outline collection item. |
| [Remove](./remove/)(*int*) | Remove item by index. |

### See Also

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

