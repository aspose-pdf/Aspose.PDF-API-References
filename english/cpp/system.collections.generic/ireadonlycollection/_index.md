---
title: System::Collections::Generic::IReadOnlyCollection class
linktitle: IReadOnlyCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IReadOnlyCollection class. Interface of read-only collection of elements. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2800
url: /cpp/system.collections.generic/ireadonlycollection/
---
## IReadOnlyCollection class


Interface of read-only collection of elements. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IReadOnlyCollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_Count](./get_count/)() const | Gets number of elements in collection. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) | Collection type name. |
| [ValueType](./valuetype/) | RTTI information. |

## See Also

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
