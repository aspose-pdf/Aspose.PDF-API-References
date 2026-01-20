---
title: Aspose::Pdf::Structure::ElementCollection class
linktitle: ElementCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Structure::ElementCollection class. Collection of base logical structure elements in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.structure/elementcollection/
---
## ElementCollection class


[Collection](../../aspose.pdf/collection/) of base logical structure elements.

```cpp
class ElementCollection : public System::Collections::Generic::IEnumerable<System::SharedPtr<Element>>
```

## Methods

| Method | Description |
| --- | --- |
| [begin](./begin/)() | Gets iterator pointing to the first element (if any) of the collection. |
| [begin](./begin/)() const | Gets iterator pointing to the first element (if any) of the const-qualified instance of the collection. |
| [cbegin](./cbegin/)() const | Gets iterator pointing to the first const-qualified element (if any) of the collection. |
| [cend](./cend/)() const | Gets iterator pointing right after the last const-qualified element (if any) of the collection. |
| [end](./end/)() | Gets iterator pointing right after the last element (if any) of the collection. |
| [end](./end/)() const | Gets iterator pointing right after the last element (if any) of the const-qualified instance of the collection. |
| [get_Count](./get_count/)() | Count of elements. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that iterates through the collection. |
| [idx_get](./idx_get/)(int32_t) | Gets [Element](../element/) by index. |
| [Remove](./remove/)(System::SharedPtr\<Element\>) | Remove item from collection. |
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
* Namespace [Aspose::Pdf::Structure](../)
* Library [Aspose.PDF for C++](../../)
