---
title: System::BoxedValueBase class
linktitle: BoxedValueBase
second_title: Aspose.PDF for C++ API Reference
description: 'System::BoxedValueBase class. A base class that defines an interface and implements some fundamental methods of a descendant class that represents a boxed value. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system/boxedvaluebase/
---
## BoxedValueBase class


A base class that defines an interface and implements some fundamental methods of a descendant class that represents a boxed value. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BoxedValueBase : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetTypeCode](./gettypecode/)() const | Returns the value representing the type of the boxed value represented by the current object. |
| virtual [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const | Converts the boxed represented by the current object to 64-bit integer value. |
| virtual [IsBoxedEnum](./isboxedenum/)() | Determines if current object represents a boxed value of enum type. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&, bool) | Boxes the value of enumeration constant of the specified enumeration with the specified name. A parameter specifies if the case should be ignored when interpreting the string specifying the name of the enumeration constant. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&) | Boxes the value of enumeration constant of the specified enumeration with the specified name. |
| [ToString](./tostring/)(const System::String\&) const | Converts boxed object to string using specified format string. |
| virtual [ToString](./tostring/)() const | Analog of C# [Object.ToString()](../object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
