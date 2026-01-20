---
title: System::Collections::Generic::SortedList class
linktitle: SortedList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::SortedList class. Sorted list wrapping FlatMap structure. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 4200
url: /cpp/system.collections.generic/sortedlist/
---
## SortedList class


Sorted list wrapping FlatMap structure. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```


| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| [crbegin](./crbegin/)() const | Gets a reverse iterator to the last const-qualified element of collection (first in reverse). |
| [crend](./crend/)() const | Gets a reverse iterator for a non-existent const-qualified element before the start of the collection. |
| [get_Capacity](./get_capacity/)() const | Gets current list capacity. |
| virtual [get_Keys](./get_keys/)() const | Accesses key collection. |
| virtual [get_Values](./get_values/)() const | Accesses value collection. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator iterating through current list. |
| [IndexOfKey](./indexofkey/)(TKey) const | Looks for specific key. |
| [IndexOfValue](./indexofvalue/)(TValue) const | Looks for specific value. |
| [rbegin](./rbegin/)() | Gets a reverse iterator to the last element of collection (first in reverse). |
| [rbegin](./rbegin/)() const | Gets a reverse iterator to the last element of the const-qualified collection (first in reverse). |
| [RemoveAt](./removeat/)(int) | Removes item at specified position. |
| [rend](./rend/)() | Gets a reverse iterator for a non-existent element before the start of the collection. |
| [rend](./rend/)() const | Gets a reverse iterator for a non-existent element before the start of the const-qualified collection. |
| [set_Capacity](./set_capacity/)(int) | Sets current list capacity. |
| [SortedList](./sortedlist/)() | Constructs empty list. |
| [SortedList](./sortedlist/)(const SharedPtr\<IComparer\<TKey\>\>\&) | Constructs empty list. |
| [SortedList](./sortedlist/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Copy constructor. |
| [SortedList](./sortedlist/)(const map_t\&) | Copy constructor. |
| [SortedList](./sortedlist/)(int) | Constructs empty list. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
| [IEnumerablePtr](./ienumerableptr/) | Collection of same pairs type. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) type. |
| [iterator](./iterator/) | Iterator type. |
| [KeyCollection](./keycollection/) | Key collection type. |
| [KVPair](./kvpair/) | Key value pair type. |
| [map_t](./map_t/) | Underlying data type. |
| [Ptr](./ptr/) | Pointer type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
| [this_t](./this_t/) | This type. |
| [ValueCollection](./valuecollection/) | Value collection type. |

## See Also

* Class [SortedListHelper](../sortedlisthelper/)
* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
