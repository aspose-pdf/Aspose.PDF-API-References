---
title: System::Collections::ObjectModel::Collection class
linktitle: Collection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::ObjectModel::Collection class. Base type for generic collection. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.collections.objectmodel/collection/
---
## Collection class


Base type for generic collection. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class T>class Collection : public System::Collections::Generic::IList<T>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Nested classes

* Class [reverse_iterator_prototype](./reverse_iterator_prototype/)
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const T\&) override | Adds value to container. |
| [Clear](./clear/)() override | Deletes all elements. |
| [Collection](./collection/)() | Creates empty collection. |
| [Collection](./collection/)(SharedPtr\<Generic::IList\<T\>\>) |  |
| [Contains](./contains/)(const T\&) const override | Checks if item is present in collection. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Copies collection elements into existing array elements. |
| [crbegin](./crbegin/)() const | Gets a reverse iterator to the last const-qualified element of collection (first in reverse). |
| [crend](./crend/)() const | Gets a reverse iterator for a non-existent const-qualified element before the start of the collection. |
| [get_Count](./get_count/)() const override | Gets number of elements. |
| [get_Items](./get_items/)() | Internal data structure accessor. |
| [get_Items](./get_items/)() const | Internal data structure accessor. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator to iterate through collection. |
| [idx_get](./idx_get/)(int) const override | Gets value at specified index. |
| [idx_set](./idx_set/)(int, T) override | Sets value at specified index. |
| [IndexOf](./indexof/)(const T\&) const override | Looks for element in collection. |
| [Insert](./insert/)(int, const T\&) override | Inserts item into specified position. |
| [operator[]](./operator[]/)(int) | Gets value at specified index. |
| [operator[]](./operator[]/)(int) const | Gets value at specified index. |
| [rbegin](./rbegin/)() | Gets a reverse iterator to the last element of collection (first in reverse). |
| [rbegin](./rbegin/)() const | Gets a reverse iterator to the last element of the const-qualified collection (first in reverse). |
| [Remove](./remove/)(const T\&) override | Removes specific item. |
| [RemoveAt](./removeat/)(int) override | Removes item at specific position. |
| [rend](./rend/)() | Gets a reverse iterator for a non-existent element before the start of the collection. |
| [rend](./rend/)() const | Gets a reverse iterator for a non-existent element before the start of the const-qualified collection. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Makes stored pointers weak (if applicable). |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_reverse_iterator](./const_reverse_iterator/) |  |
| [reverse_iterator](./reverse_iterator/) |  |

## See Also

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
