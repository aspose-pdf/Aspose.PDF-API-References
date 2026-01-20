---
title: System::BoxedEnum class
linktitle: BoxedEnum
second_title: Aspose.PDF for C++ API Reference
description: 'System::BoxedEnum class. Represents boxed enumeration value. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system/boxedenum/
---
## BoxedEnum class


Represents boxed enumeration value. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```


| Parameter | Description |
| --- | --- |
| E | Type of the enumeration value |
| UT | The underlying type of enumeration **E** |
## Methods

| Method | Description |
| --- | --- |
| [BoxedEnum](./boxedenum/)(E) | Constructs an instance that represents the specified enumeration value. |
| [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Converts the value of the boxed enumeration constant to 64-bit integer value. |
| [IsBoxedEnum](./isboxedenum/)() override | Determines whether the current object represents a boxed value of enum type. |
| [ToString](./tostring/)() const override | Converts boxed value represented by the current object to string. |

## See Also

* Class [BoxedValue](../boxedvalue/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
