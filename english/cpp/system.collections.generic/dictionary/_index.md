---
title: System::Collections::Generic::Dictionary class
linktitle: Dictionary
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::Dictionary class. Forward declaration of Dictionary class in C++.'
type: docs
weight: 1100
url: /cpp/system.collections.generic/dictionary/
---
## Dictionary class


Forward declaration of [Dictionary](./) class.

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [Dictionary](./dictionary/)() | Creates empty dictionary. |
| [Dictionary](./dictionary/)(const map_t\&) | Copies data from map. |
| [Dictionary](./dictionary/)(int) | Overload which corresponds to creating pre-allocated dictionary; does no allocation, actually. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Copy constructor. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Copy constructor. |
| [Dictionary](./dictionary/)(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Creates empty dictionary. |
| [Dictionary](./dictionary/)(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Creates empty dictionary. |
| [GetEnumerator](./getenumerator/)() override | Creates enumerator object. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Pointer to enumerable interface. |
| [IEnumeratorPtr](./ienumeratorptr/) | Pointer to enumerator. |
| [KeyCollection](./keycollection/) | RTTI information. |
| [KVPair](./kvpair/) | Key-value pair type. |
| [map_t](./map_t/) | Underlying data type. |
| [Ptr](./ptr/) | Pointer type. |
| [ValueCollection](./valuecollection/) | Collection of values to extract. |
## Remarks


[Dictionary](./) that maps values to keys. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Create the Dictionary-class instance.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // Fill the dictionary.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // Print the dictionary items.
  for (const auto &pair: dictionary)
  {
    std::cout << pair.get_Key() << " - " << pair.get_Value() << std::endl;
  }

  return 0;
}
/*
This code example produces the following output:
0 - Foo
1 - Bar
2 - Baz
*/
```

## See Also

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
