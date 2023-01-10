---
title: OutlineItemCollection
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents outline entry in outline hierarchy of PDF document.
type: docs
weight: 1060
url: /python-net/aspose.pdf/outlineitemcollection/
---

## OutlineItemCollection class

Represents outline entry in outline hierarchy of PDF document.

The OutlineItemCollection type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|OutlineItemCollection(outlines)|Initializes a new instance of the OutlineItemCollection class|
## Properties
| Name | Description |
| :- | :- |
|visible_count|Gets the total number of outline items at all levels in the document outline hierarchy.|
|title|Gets or sets the title for this outline item.|
|destination|Gets or sets the destination for this outline item.|
|action|Gets or sets the action for this outline item.|
|color|Gets or sets the color for the title text of this outline item.|
|italic|Gets or sets italic flag for the title text of this outline item|
|bold|Gets or sets bold flag for the title text of this outline item|
|first|Gets the outline item representing the first top-level item in the outline hierarchy.|
|last|Gets the outline item representing the last top-level item in the outline hierarchy.|
|prev|Gets the outline item representing previous item relatively this item in the outline hierarchy.|
|next|Gets the outline item representing next item relatively this item in the outline hierarchy.|
|has_next|Check if outline item representing next item relatively this item in the outline hierarchy.|
|parent|Gets the parent object of this outline item in the outline hierarchy.|
|is_synchronized|Gets the value indicating whether access to this collection is synchronized (thread safe).|
|sync_root|Gets the object that can be used to synchronize access to this collection.|
|open|Get or sets open status (true/false) for outline item.|
|level|Gets hierarchy level of outline item.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets outline item from the collection using index.|
## Methods
| Name | Description |
| :- | :- |
|delete()|Deletes this outline item from the document outline hierarchy.|
|delete(name)|Deletes outline entry with specified name from the document outline hierarchy.|
|insert(index, outline)|Inserts the outline item into collection at the specified place.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

