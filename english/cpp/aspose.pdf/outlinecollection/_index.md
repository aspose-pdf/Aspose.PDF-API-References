---
title: Aspose::Pdf::OutlineCollection class
linktitle: OutlineCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OutlineCollection class. Represents document outline hierarchy in C++.'
type: docs
weight: 12700
url: /cpp/aspose.pdf/outlinecollection/
---
## OutlineCollection class


Represents document outline hierarchy.

```cpp
class OutlineCollection : public Aspose::Pdf::Outlines
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Adds outline item to collection. |
| [Clear](./clear/)() override | Clears all items from the collection. |
| [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const override | Checks does collection contains given item. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) override | Copies the outline items to an [System.Array](../../system/array/), starting at a particular [System.Array](../../system/array/) index. |
| [Delete](./delete/)() | Deletes all outline items from the document outline. |
| [Delete](./delete/)(System::String) | Deletes the outline item with specified title from the document outline. |
| [get_Count](./get_count/)() const override | Count of collection items. Please dont confuse with VisibleCount: VisibleCount gets number of visible outline item on all levels. |
| [get_First](./get_first/)() const | Gets an outline item representing the first top-level item in the outline. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether the collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [get_Last](./get_last/)() | Gets an outline item representing the last top-level item in the outline. |
| [get_SyncRoot](./get_syncroot/)() const | Gets an object that can be used to synchronize access to this collection. |
| [get_VisibleCount](./get_visiblecount/)() override | Count is the sum of the number of visible descendent outline items at all levels. [Note](../note/): please don't confuse with Count which is number if items in collection. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that iterates through the collection. |
| [idx_get](./idx_get/)(int32_t) | Gets outline item from collection by index. |
| [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Always throws NotImplementedException |
| [Remove](./remove/)(int32_t) | Remove item by index. |
## See Also

* Class [Outlines](../outlines/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
