---
title: Aspose::Pdf::Outlines class
linktitle: Outlines
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Outlines class. Class describes collection of outlines in C++.'
type: docs
weight: 12900
url: /cpp/aspose.pdf/outlines/
---
## Outlines class


Class describes collection of outlines.

```cpp
class Outlines : public System::Collections::Generic::ICollection<System::SharedPtr<OutlineItemCollection>>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) | Adds outline item to collection. |
| virtual [Clear](./clear/)() | Clears all items from the collection. |
| virtual [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const | Always throws NotImplementedException. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) | Copies the outline entries to an [System.Array](../../system/array/), starting at a particular [System.Array](../../system/array/) index. |
| virtual [get_Count](./get_count/)() const | Gets count. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Gets a value indicating whether the collection is read-only. |
| virtual [get_VisibleCount](./get_visiblecount/)() | Gets the total number of outline items at all levels in the document outline hierarchy. |
| virtual [GetEnumerator](./getenumerator/)() | Returns an enumerator that iterates through the collection. |
| virtual [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) | Remove outline collection item. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
