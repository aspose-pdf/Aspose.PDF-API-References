---
title: System::IComparable class
linktitle: IComparable
second_title: Aspose.PDF for C++ API Reference
description: 'System::IComparable class. Defines a method that compares two objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3300
url: /cpp/system/icomparable/
---
## IComparable class


Defines a method that compares two objects. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IComparable : public virtual System::Object
```


| Parameter | Description |
| --- | --- |
| T | The type of the objects with which the current object gets compared |
## Methods

| Method | Description |
| --- | --- |
| virtual [CompareTo](./compareto/)(T) | Compares the current object with the specified object. |

## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
