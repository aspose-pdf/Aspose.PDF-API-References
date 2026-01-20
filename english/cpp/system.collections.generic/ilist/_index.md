---
title: System::Collections::Generic::IList class
linktitle: IList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IList class. Interface of indexed container of elements. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2600
url: /cpp/system.collections.generic/ilist/
---
## IList class


Interface of indexed container of elements. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IList : public System::Collections::Generic::ICollection<T>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [get_IsFixedSize](./get_isfixedsize/)() | Checks whether the collection is of fixed size. |
| virtual [idx_get](./idx_get/)(int) const | Gets element at specified index. |
| virtual [idx_set](./idx_set/)(int, T) | Sets element at specified index. |
| virtual [IndexOf](./indexof/)(const T\&) const | Gets index of first appearance of item in container. |
| virtual [Insert](./insert/)(int, const T\&) | Inserts element into specified position, shifting other elements. |
| virtual [RemoveAt](./removeat/)(int) | Removes element at specified index. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | RTTI information. |
| [ThisType](./thistype/) | This type. |
| [ValueType](./valuetype/) | Value type. |

## See Also

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
