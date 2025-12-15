---
title: Aspose::Pdf::Cells class
linktitle: Cells
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Cells class. Represents a cells collection of row in C++.'
type: docs
weight: 2000
url: /cpp/aspose.pdf/cells/
---
## Cells class


Represents a cells collection of row.

```cpp
class Cells : public System::Collections::Generic::IEnumerable<System::SharedPtr<Cell>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)() | Add cell to collection. |
| [Add](./add/)(System::String, System::SharedPtr\<Text::TextState\>) | Add cell to collection. |
| [Add](./add/)(System::String) | Add cell to collection. |
| [Add](./add/)(System::SharedPtr\<Text::TextFragment\>) | Add cell to collection. |
| [Add](./add/)(System::SharedPtr\<Cell\>) | Add cell to collection. |
| [begin](./begin/)() | Gets iterator pointing to the first element (if any) of the collection. |
| [begin](./begin/)() const | Gets iterator pointing to the first element (if any) of the const-qualified instance of the collection. |
| [cbegin](./cbegin/)() const | Gets iterator pointing to the first const-qualified element (if any) of the collection. |
| [Cells](./cells/)() |  |
| [cend](./cend/)() const | Gets iterator pointing right after the last const-qualified element (if any) of the collection. |
| [Dispose](./dispose/)() | Dispose method. |
| [end](./end/)() | Gets iterator pointing right after the last element (if any) of the collection. |
| [end](./end/)() const | Gets iterator pointing right after the last element (if any) of the const-qualified instance of the collection. |
| [get_Count](./get_count/)() | The items count. |
| [GetEnumerator](./getenumerator/)() override | Gets collection's enumerator. |
| [idx_get](./idx_get/)(int32_t) | Gets cells. |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Cell\>) | Sets cells. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<Cell\>) | Insert cell to collection. |
| [Remove](./remove/)(System::SharedPtr\<Cell\>) | Remove cell set from collection. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Remove cell set from collection. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets iterator pointing to the first element (if any)of the const-qualified instance of the collection. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets iterator pointing to the first element (if any) of the collection. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets iterator pointing right after the last element (if any)of the const-qualified instance of the collection. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets iterator pointing right after the last element (if any) of the collection. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [iterator](./iterator/) | Iterator type. |
| [iterator_holder_type](./iterator_holder_type/) | A collection type whose iterator types is used as iterator types in the current collection. |
| [virtualized_iterator](./virtualized_iterator/) | Virtualized type. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Virtualized element type. |
## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
