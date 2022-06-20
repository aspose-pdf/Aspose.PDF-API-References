---
title: OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Represents outline entry in outline hierarchy of PDF document.
type: docs
weight: 5770
url: /net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

Represents outline entry in outline hierarchy of PDF document.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Constructors

| Name | Description |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection)(OutlineCollection) | Initializes outline item instance using root hierarchy object. |

## Properties

| Name | Description |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action) { get; set; } | Gets or sets the action for this outline item. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold) { get; set; } | Gets or sets bold flag for the title text of this outline item |
| [Color](../../aspose.pdf/outlineitemcollection/color) { get; set; } | Gets or sets the color for the title text of this outline item. |
| override [Count](../../aspose.pdf/outlineitemcollection/count) { get; } | Count of collection items. Please dont confuse with VisibleCount: VisibleCount gets number of visible outline item on all levels. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination) { get; set; } | Gets or sets the destination for this outline item. |
| [First](../../aspose.pdf/outlineitemcollection/first) { get; } | Gets the outline item representing the first top-level item in the outline hierarchy. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext) { get; } | Check if outline item representing next item relatively this item in the outline hierarchy. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly) { get; } | Gets a value indicating whether the collection is read-only. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized) { get; } | Gets the value indicating whether access to this collection is synchronized (thread safe). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic) { get; set; } | Gets or sets italic flag for the title text of this outline item |
| [Item](../../aspose.pdf/outlineitemcollection/item) { get; } | Gets outline item from the collection using index. |
| [Last](../../aspose.pdf/outlineitemcollection/last) { get; } | Gets the outline item representing the last top-level item in the outline hierarchy. |
| [Level](../../aspose.pdf/outlineitemcollection/level) { get; } | Gets hierarchy level of outline item. |
| [Next](../../aspose.pdf/outlineitemcollection/next) { get; } | Gets the outline item representing next item relatively this item in the outline hierarchy. |
| [Open](../../aspose.pdf/outlineitemcollection/open) { get; set; } | Get or sets open status (true/false) for outline item. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent) { get; } | Gets the parent object of this outline item in the outline hierarchy. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev) { get; } | Gets the outline item representing previous item relatively this item in the outline hierarchy. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot) { get; } | Gets the object that can be used to synchronize access to this collection. |
| [Title](../../aspose.pdf/outlineitemcollection/title) { get; set; } | Gets or sets the title for this outline item. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount) { get; } | Gets the total number of outline items at all levels in the document outline hierarchy. |

## Methods

| Name | Description |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add)(OutlineItemCollection) | Adds outline item to collection. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear)() | Clears all items from the collection. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains)(OutlineItemCollection) | Checks if collection contains given item. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto)(OutlineItemCollection[], int) | Copies the outline entries to an System.Array, starting at a particular System.Array index. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete#delete)() | Deletes this outline item from the document outline hierarchy. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete#delete_1)(string) | Deletes outline entry with specified name from the document outline hierarchy. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert)(int, OutlineItemCollection) | Inserts the outline item into collection at the specified place. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove#remove_1)(int) | Remove item by index. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove#remove)(OutlineItemCollection) | Remove outline collection item. |

### See Also

* class [Outlines](../outlines)
* namespace [Aspose.Pdf](../../aspose.pdf)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
