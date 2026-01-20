---
title: System::Collections::Generic::DefaultComparer class
linktitle: DefaultComparer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::DefaultComparer class. Default comparator class. Uses operator < and operator == to compare values. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.collections.generic/defaultcomparer/
---
## DefaultComparer class


Default comparator class. Uses operator < and operator == to compare values. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class T>class DefaultComparer : public System::Collections::Generic::IComparer<T>
```


| Parameter | Description |
| --- | --- |
| T | Type being compared. |
## Methods

| Method | Description |
| --- | --- |
| [Compare](./compare/)(typename ThisType::args_type, typename ThisType::args_type) const override | RTTI information. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | Interface implemented. |
| [ThisType](./thistype/) | Curent type. |

## See Also

* Class [IComparer](../icomparer/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
