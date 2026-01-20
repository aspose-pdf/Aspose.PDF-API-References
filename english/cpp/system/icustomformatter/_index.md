---
title: System::ICustomFormatter class
linktitle: ICustomFormatter
second_title: Aspose.PDF for C++ API Reference
description: 'System::ICustomFormatter class. Defines a method that performs custom formatting of a string representation of a value represented by the specified object. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3500
url: /cpp/system/icustomformatter/
---
## ICustomFormatter class


Defines a method that performs custom formatting of a string representation of a value represented by the specified object. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICustomFormatter : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Format](./format/)(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) | Returns a string representation of a value represented by the current object using the specified format. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
