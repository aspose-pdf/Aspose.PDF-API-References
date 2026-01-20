---
title: System::Collections::Generic::_KeyList class
linktitle: _KeyList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::_KeyList class. Implements list of dictionary''s keys. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.collections.generic/_keylist/
---
## _KeyList class


Implements list of dictionary's keys. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Dict>class _KeyList : public System::Collections::Generic::_KeyCollection<Dict>
```


| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) type. |
## Methods

| Method | Description |
| --- | --- |
| [_KeyList](./_keylist/)(const typename Dict::Ptr\&) | Initializes collection referencing specified dictionary. |
| [Contains](./contains/)(const TKey\&) const override | Checks if specified key is present in collection. |
| [idx_get](./idx_get/)(int) const override | Gets key at specified position. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [TKey](./tkey/) | Key type. |

## See Also

* Class [_KeyCollection](../_keycollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
