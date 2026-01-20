---
title: System::Collections::Generic::_ValueList class
linktitle: _ValueList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::_ValueList class. Implements list of dictionary''s values. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.collections.generic/_valuelist/
---
## _ValueList class


Implements list of dictionary's values. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Dict>class _ValueList : public System::Collections::Generic::_ValueCollection<Dict>
```


| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) type. |
## Methods

| Method | Description |
| --- | --- |
| [_ValueList](./_valuelist/)(const typename Dict::Ptr\&) | Initializes collection referencing specified dictionary. |
| virtual [idx_get](./idx_get/)(int) const | Gets value at specified position. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [TValue](./tvalue/) | Value type. |

## See Also

* Class [_ValueCollection](../_valuecollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
