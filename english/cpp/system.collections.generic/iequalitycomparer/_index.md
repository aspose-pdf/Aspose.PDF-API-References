---
title: System::Collections::Generic::IEqualityComparer class
linktitle: IEqualityComparer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEqualityComparer class. Interface providing means to compare two objects for equality. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2400
url: /cpp/system.collections.generic/iequalitycomparer/
---
## IEqualityComparer class


Interface providing means to compare two objects for equality. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IEqualityComparer : public virtual System::Object
```


| Parameter | Description |
| --- | --- |
| T | Type being compared. |
## Methods

| Method | Description |
| --- | --- |
| virtual [Equals](./equals/)(T, T) const | RTTI information. |
| virtual [GetHashCode](./gethashcode/)(T) const | Gets hash code for some object. |

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
