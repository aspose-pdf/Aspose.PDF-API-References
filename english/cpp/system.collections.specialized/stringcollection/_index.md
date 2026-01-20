---
title: System::Collections::Specialized::StringCollection class
linktitle: StringCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Specialized::StringCollection class. Indexed list of strings. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.collections.specialized/stringcollection/
---
## StringCollection class


Indexed list of strings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringCollection : public System::Collections::Generic::IEnumerable<System::String>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::String\&) | Adds value to the end of the list. |
| [AddRange](./addrange/)(const ArrayPtr\<System::String\>\&) | Add elements into container. |
| [begin](./begin/)() | Returns an iterator to the first element of the container. If the container is empty, the returned iterator will be equal to [end()](./end/). |
| [begin](./begin/)() const | Returns an iterator to the first element of the const-qualified container. If the container is empty, the returned iterator will be equal to [end()](./end/). |
| [cbegin](./cbegin/)() const | Returns an iterator to the first const-qualified element of the container. If the container is empty, the returned iterator will be equal to [cend()](./cend/). |
| [cend](./cend/)() const | Returns an iterator to the element following the last element of the container. This element acts as a placeholder; attempting to access it results in undefined behavior. |
| [Clear](./clear/)() | Deletes all elements. |
| [Contains](./contains/)(const System::String\&) const | Checks whether specific string is present in container. |
| [CopyTo](./copyto/)(const ArrayPtr\<System::String\>\&, const int32_t) const | Copy elements to existing arra elements. |
| [crbegin](./crbegin/)() const | Returns a reverse iterator to the first element of the reversed container. It corresponds to the last element of the non-reversed container. If the container is empty, the returned iterator is equal to [crend()](./crend/). |
| [crend](./crend/)() const | Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior. |
| [data](./data/)() | Internal data structure accessor. |
| [data](./data/)() const | Internal data structure accessor. |
| [end](./end/)() | Returns an iterator to the element following the last element of the container. This element acts as a placeholder; attempting to access it results in undefined behavior. |
| [end](./end/)() const | Returns an iterator to the element following the last element of the const-qualified container. This element acts as a placeholder; attempting to access it results in undefined behavior. |
| [get_Count](./get_count/)() const | Gets number of elements in collection. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator iterating through current collection. |
| [idx_get](./idx_get/)(int) const | Gets value at specified position. |
| [idx_set](./idx_set/)(int, const System::String\&) | Sets value at specified position. |
| [IndexOf](./indexof/)(const System::String\&) const | Looks for specific string in container. |
| [Insert](./insert/)(int, const System::String\&) | Inserts specific value into container. |
| [operator[]](./operator[]/)(int) | Accessor function. |
| [rbegin](./rbegin/)() | Returns a reverse iterator to the first element of the reversed container. It corresponds to the last element of the non-reversed container. If the container is empty, the returned iterator is equal to [rend()](./rend/). |
| [rbegin](./rbegin/)() const | Returns a reverse iterator to the first element of the reversed container. It corresponds to the last element of the non-reversed container. If the container is empty, the returned iterator is equal to [rend()](./rend/). |
| [Remove](./remove/)(const System::String\&) | Removes first occurrence of specified string. |
| [RemoveAt](./removeat/)(int) | Removes element at specified position. |
| [rend](./rend/)() | Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior. |
| [rend](./rend/)() const | Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior. |
| [StringCollection](./stringcollection/)() | Constructs empty string collection. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
| [iterator](./iterator/) | Iterator type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
