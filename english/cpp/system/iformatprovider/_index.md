---
title: System::IFormatProvider class
linktitle: IFormatProvider
second_title: Aspose.PDF for C++ API Reference
description: 'System::IFormatProvider class. Defines a method that provides formatting information. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3800
url: /cpp/system/iformatprovider/
---
## IFormatProvider class


Defines a method that provides formatting information. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IFormatProvider : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetFormat](./getformat/)(const TypeInfo\&) | Returns an object that provides formatting services for the specified type. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
