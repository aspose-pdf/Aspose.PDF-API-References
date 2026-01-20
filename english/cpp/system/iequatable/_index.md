---
title: System::IEquatable class
linktitle: IEquatable
second_title: Aspose.PDF for C++ API Reference
description: 'System::IEquatable class. Defines a method that determines the equality of two objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3700
url: /cpp/system/iequatable/
---
## IEquatable class


Defines a method that determines the equality of two objects. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IEquatable : public virtual System::Object
```


| Parameter | Description |
| --- | --- |
| T | The type of the compared objects |
## Methods

| Method | Description |
| --- | --- |
| virtual [Equals](./equals/)(T) | Determines if the the current and specified objects are equal. |

## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
