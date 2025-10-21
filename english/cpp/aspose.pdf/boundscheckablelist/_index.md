---
title: Aspose::Pdf::BoundsCheckableList class
linktitle: BoundsCheckableList
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::BoundsCheckableList class. Represents BoundsCheckableList - wrapper around System.Collections.Generic.List in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf/boundscheckablelist/
---
## BoundsCheckableList class


Represents [BoundsCheckableList](./) - wrapper around [System.Collections.Generic.List](../../system.collections.generic/list/).

```cpp
template<typename T>class BoundsCheckableList : public System::Collections::Generic::IList<T>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const T\&) override | Adds an object to the end of the [System.Collections.Generic.List](../../system.collections.generic/list/) depending on "boundsCheckMode" parameter. |
| [begin](./begin/)() | Gets iterator pointing to the first element (if any) of the collection. |
| [begin](./begin/)() const | Gets iterator pointing to the first element (if any) of the const-qualified instance of the collection. |
| [BoundsCheckableList](./boundscheckablelist/)() | Initializes a new instance of the [BoundsCheckableList](./) class. |
| [BoundsCheckableList](./boundscheckablelist/)(BoundsCheckMode, double, double) | Initializes a new instance of the [BoundsCheckableList](./) class. |
| [cbegin](./cbegin/)() const | Gets iterator pointing to the first const-qualified element (if any) of the collection. |
| [cend](./cend/)() const | Gets iterator pointing right after the last const-qualified element (if any) of the collection. |
| [Clear](./clear/)() override | Removes all elements from the [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [Contains](./contains/)(const T\&) const override | Determines whether an element is in the [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int32_t) override | Copies the entire [System.Collections.Generic.List](../../system.collections.generic/list/) to a compatible one-dimensional array, starting at the specified index of the target array. |
| [end](./end/)() | Gets iterator pointing right after the last element (if any) of the collection. |
| [end](./end/)() const | Gets iterator pointing right after the last element (if any) of the const-qualified instance of the collection. |
| [get_Count](./get_count/)() const override | Gets the number of elements contained in the [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets the value indicating if collection is readonly. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that iterates through the [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [idx_get](./idx_get/)(int32_t) const override | Gets paragraph from or to collection. |
| [idx_set](./idx_set/)(int32_t, T) override | Sets paragraph from or to collection. |
| [IndexOf](./indexof/)(const T\&) const override | Searches for the specified object and returns the zero-based index of the first occurrence within the entire [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [Insert](./insert/)(int32_t, const T\&) override | Inserts an element into the [System.Collections.Generic.List](../../system.collections.generic/list/) at the specified index. |
| [Remove](./remove/)(const T\&) override | Removes the first occurrence of a specific object from the [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [RemoveAt](./removeat/)(int32_t) override | Removes the element at the specified index of the [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode, double, double) | Updates boundsCheckMode parameter for initialized collection. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode) | Updates boundsCheckMode parameter for initialized collection. |
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

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
