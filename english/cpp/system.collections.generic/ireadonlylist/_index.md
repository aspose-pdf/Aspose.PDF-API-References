---
title: System::Collections::Generic::IReadOnlyList class
linktitle: IReadOnlyList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IReadOnlyList class. Interface of read-only indexed container of elements. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3000
url: /cpp/system.collections.generic/ireadonlylist/
---
## IReadOnlyList class


Interface of read-only indexed container of elements. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IReadOnlyList : public System::Collections::Generic::IReadOnlyCollection<T>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| virtual [idx_get](./idx_get/)(int32_t) const | Gets element at specified index. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | RTTI information. |
| [ThisType](./thistype/) | This type. |
| [ValueType](./valuetype/) | Value type. |

## See Also

* Class [IReadOnlyCollection](../ireadonlycollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
