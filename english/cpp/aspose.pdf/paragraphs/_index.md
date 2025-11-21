---
title: Aspose::Pdf::Paragraphs class
linktitle: Paragraphs
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Paragraphs class. This class represents paragraph collection in C++.'
type: docs
weight: 14600
url: /cpp/aspose.pdf/paragraphs/
---
## Paragraphs class


This class represents paragraph collection.

```cpp
class Paragraphs : public System::Collections::Generic::IEnumerable<System::SharedPtr<BaseParagraph>>,
                   public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<BaseParagraph\>) | Add paragraph to collection. |
| [begin](./begin/)() | Gets iterator pointing to the first element (if any) of the collection. |
| [begin](./begin/)() const | Gets iterator pointing to the first element (if any) of the const-qualified instance of the collection. |
| [cbegin](./cbegin/)() const | Gets iterator pointing to the first const-qualified element (if any) of the collection. |
| [cend](./cend/)() const | Gets iterator pointing right after the last const-qualified element (if any) of the collection. |
| [Clear](./clear/)() | Clear paragraphs. |
| [Clone](./clone/)() override | Clones a new [Clone](./clone/) object. |
| [cpp_switch_last_paragraph_to_week](./cpp_switch_last_paragraph_to_week/)() |  |
| [end](./end/)() | Gets iterator pointing right after the last element (if any) of the collection. |
| [end](./end/)() const | Gets iterator pointing right after the last element (if any) of the const-qualified instance of the collection. |
| [get_Count](./get_count/)() | Get paragraphs count. |
| [GetEnumerator](./getenumerator/)() override | Gets the enumerator. |
| [GetRange](./getrange/)(int32_t, int32_t) | Remove paragraphs range. |
| [idx_get](./idx_get/)(int32_t) | Gets paragraph from or to collection. |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<BaseParagraph\>) | Sets paragraph from or to collection. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<BaseParagraph\>) | Insert paragraph to collection. |
| [InsertRange](./insertrange/)(int32_t, System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<BaseParagraph\>\>\>) | Inserts the elements of a collection into the list at the specified index. |
| [Paragraphs](./paragraphs/)() |  |
| [Remove](./remove/)(System::SharedPtr\<BaseParagraph\>) | Remove paragraph from collection. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Remove paragraphs range. |
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
* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
