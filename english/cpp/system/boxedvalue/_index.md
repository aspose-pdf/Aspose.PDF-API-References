---
title: System::BoxedValue class
linktitle: BoxedValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::BoxedValue class. Represents a boxed value. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system/boxedvalue/
---
## BoxedValue class


Represents a boxed value. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase
```


| Parameter | Description |
| --- | --- |
| T | Type of the boxed value represented by the class |
## Methods

| Method | Description |
| --- | --- |
| [BoxedValue](./boxedvalue/)(const T\&) | Constructs an object that represents the specified value boxed. |
| [Equals](./equals/)(ptr) override | Determines the equality of the boxed values represented by the current and specified objects. |
| [GetHashCode](./gethashcode/)() const override | Returns a hash code for the current object. |
| [GetType](./gettype/)() const override | Gets actual type of object. |
| [GetTypeCode](./gettypecode/)() const override | Returns the value representing the type of the boxed value represented by the current object. |
| [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Returns numeric value of boxed object if it can be cast too, zero otherwise. |
| [is](./is/)() const | Determines if the type of the boxed value represented by the current object is **V**. |
| [IsBoxedEnum](./isboxedenum/)() override | Determines if current object represents a boxed value of enum type. |
| static [Parse](../boxedvaluebase/parse/)(const TypeInfo\&, const String\&, bool) | Boxes the value of enumeration constant of the specified enumeration with the specified name. A parameter specifies if the case should be ignored when interpreting the string specifying the name of the enumeration constant. |
| static [Parse](../boxedvaluebase/parse/)(const TypeInfo\&, const String\&) | Boxes the value of enumeration constant of the specified enumeration with the specified name. |
| [ToString](./tostring/)() const override | Converts boxed value represented by current object to string. |
| [ToString](../boxedvaluebase/tostring/)(const System::String\&) const | Converts boxed object to string using specified format string. |
| [unbox](./unbox/)() const | Unboxes the value represented by the current object. |

## See Also

* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
