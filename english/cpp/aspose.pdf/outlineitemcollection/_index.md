---
title: Aspose::Pdf::OutlineItemCollection class
linktitle: OutlineItemCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OutlineItemCollection class. Represents outline entry in outline hierarchy of PDF document in C++.'
type: docs
weight: 12600
url: /cpp/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class


Represents outline entry in outline hierarchy of PDF document.

```cpp
class OutlineItemCollection : public Aspose::Pdf::Outlines
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Adds outline item to collection. |
| [Clear](./clear/)() override | Clears all items from the collection. |
| [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const override | Checks if collection contains given item. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) override | Copies the outline entries to an [System.Array](../../system/array/), starting at a particular [System.Array](../../system/array/) index. |
| [Delete](./delete/)() | Deletes this outline item from the document outline hierarchy. |
| [Delete](./delete/)(System::String) | Deletes outline entry with specified name from the document outline hierarchy. |
| [get_Action](./get_action/)() | Gets the action for this outline item. |
| [get_Bold](./get_bold/)() | Gets bold flag for the title text of this outline item. |
| [get_Color](./get_color/)() | Gets the color for the title text of this outline item. |
| [get_Count](./get_count/)() const override | Count of collection items. Please dont confuse with VisibleCount: VisibleCount gets number of visible outline item on all levels. |
| [get_Destination](./get_destination/)() | Gets the destination for this outline item. |
| [get_First](./get_first/)() const | Gets the outline item representing the first top-level item in the outline hierarchy. |
| [get_HasNext](./get_hasnext/)() | Check if outline item representing next item relatively this item in the outline hierarchy. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether the collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Gets the value indicating whether access to this collection is synchronized (thread safe). |
| [get_Italic](./get_italic/)() | Gets italic flag for the title text of this outline item. |
| [get_Last](./get_last/)() | Gets the outline item representing the last top-level item in the outline hierarchy. |
| [get_Level](./get_level/)() | Gets hierarchy level of outline item. |
| [get_Next](./get_next/)() | Gets the outline item representing next item relatively this item in the outline hierarchy. |
| [get_Open](./get_open/)() | Get or sets open status (true/false) for outline item. |
| [get_Parent](./get_parent/)() | Gets the parent object of this outline item in the outline hierarchy. |
| [get_Prev](./get_prev/)() | Gets the outline item representing previous item relatively this item in the outline hierarchy. |
| [get_SyncRoot](./get_syncroot/)() const | Gets the object that can be used to synchronize access to this collection. |
| [get_Title](./get_title/)() | Gets the title for this outline item. |
| [get_VisibleCount](./get_visiblecount/)() override | Gets the total number of outline items at all levels in the document outline hierarchy. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that iterates through the collection. |
| [idx_get](./idx_get/)(int32_t) | Gets outline item from the collection using index. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<OutlineItemCollection\>) | Inserts the outline item into collection at the specified place. |
| [OutlineItemCollection](./outlineitemcollection/)(System::SharedPtr\<OutlineCollection\>) | Initializes outline item instance using root hierarchy object. |
| [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Remove outline collection item. |
| [Remove](./remove/)(int32_t) | Remove item by index. |
| [set_Action](./set_action/)(System::SharedPtr\<Annotations::PdfAction\>) | Sets the action for this outline item. |
| [set_Bold](./set_bold/)(bool) | Sets bold flag for the title text of this outline item. |
| [set_Color](./set_color/)(System::Drawing::Color) | Sets the color for the title text of this outline item. |
| [set_Destination](./set_destination/)(System::SharedPtr\<Annotations::IAppointment\>) | Sets the destination for this outline item. |
| [set_Italic](./set_italic/)(bool) | Sets italic flag for the title text of this outline item. |
| [set_Open](./set_open/)(bool) | Get or sets open status (true/false) for outline item. |
| [set_Title](./set_title/)(System::String) | Sets the title for this outline item. |
## See Also

* Class [Outlines](../outlines/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
