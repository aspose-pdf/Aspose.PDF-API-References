---
title: Aspose::Pdf::Rows class
linktitle: Rows
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Rows class. Represents a rows collection of table in C++.'
type: docs
weight: 17100
url: /cpp/aspose.pdf/rows/
---
## Rows class


Represents a rows collection of table.

```cpp
class Rows : public System::Collections::Generic::IEnumerable<System::SharedPtr<Row>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)() | Add row to collection. |
| [Add](./add/)(System::SharedPtr\<Row\>) | Add row to cellection. |
| [begin](./begin/)() | Gets iterator pointing to the first element (if any) of the collection. |
| [begin](./begin/)() const | Gets iterator pointing to the first element (if any) of the const-qualified instance of the collection. |
| [cbegin](./cbegin/)() const | Gets iterator pointing to the first const-qualified element (if any) of the collection. |
| [cend](./cend/)() const | Gets iterator pointing right after the last const-qualified element (if any) of the collection. |
| [Dispose](./dispose/)() | Dispose. |
| [end](./end/)() | Gets iterator pointing right after the last element (if any) of the collection. |
| [end](./end/)() const | Gets iterator pointing right after the last element (if any) of the const-qualified instance of the collection. |
| [get_Count](./get_count/)() | The items count. |
| [GetEnumerator](./getenumerator/)() override | Gets collection's enumerator. |
| [idx_get](./idx_get/)(int32_t) | Gets row. |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<Row\>) | Sets row. |
| [IndexOf](./indexof/)(System::SharedPtr\<Row\>) | Returns index of row in collection. |
| [Remove](./remove/)(System::SharedPtr\<Row\>) | Remove row from collection. |
| [RemoveAt](./removeat/)(int32_t) | Remove row at position from collection. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Remove row set from collection. |
| [Rows](./rows/)() |  |
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
