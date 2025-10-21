---
title: System::Collections::Generic::SortedDictionary class
linktitle: SortedDictionary
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::SortedDictionary class. Sorted dictionary type forward declaration in C++.'
type: docs
weight: 4000
url: /cpp/system.collections.generic/sorteddictionary/
---
## SortedDictionary class


Sorted dictionary type forward declaration.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [get_Comparer](./get_comparer/)() const | Gets the [IComparer<TKey>](../icomparer/) used to order the elements of the SortedDictionary<TKey,TValue>. |
| static [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Singleton accessor function. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator to iterate through current dictionary. |
| [rbegin](./rbegin/)() | Gets a reverse iterator to the last element of collection (first in reverse). |
| [rbegin](./rbegin/)() const | Gets a reverse iterator to the last element of the const-qualified collection (first in reverse). |
| [rend](./rend/)() | Gets a reverse iterator for a non-existent element before the start of the collection. |
| [rend](./rend/)() const | Gets a reverse iterator for a non-existent element before the start of the const-qualified collection. |
| [SortedDictionary](./sorteddictionary/)() | Constructs empty dictionary. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Constructs empty dictionary. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Copy constructor. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Copy constructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
| [IEnumerablePtr](./ienumerableptr/) | Collection of same elements. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) type. |
| [iterator](./iterator/) | Iterator type. |
| [KeyCollection](./keycollection/) | Key collection type. |
| [KVPair](./kvpair/) | Key-value pair type. |
| [map_t](./map_t/) | Underlying data type. |
| [Ptr](./ptr/) | Pointer type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
| [this_t](./this_t/) | Self type. |
| [ValueCollection](./valuecollection/) | Value collection type. |
## Remarks


Sorted dictionary class wrapping STL map. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

## See Also

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
