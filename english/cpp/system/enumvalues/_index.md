---
title: System::EnumValues class
linktitle: EnumValues
second_title: Aspose.PDF for C++ API Reference
description: 'System::EnumValues class. Provides meta information about enumeration constants of enum type E in C++.'
type: docs
weight: 2300
url: /cpp/system/enumvalues/
---
## EnumValues class


Provides meta information about enumeration constants of enum type **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```


| Parameter | Description |
| --- | --- |
| E | The type of enumeration |
## Methods

| Method | Description |
| --- | --- |
| [EnumValues](./enumvalues/)() | Constructs an instance. |
| [GetNames](./getnames/)() const override | Returns an array containing all names of enumeration **E**. |
| static [GetNames](../enumvaluesbase/getnames/)(const TypeInfo\&) | Retrieves an array of the names of the constants in a specified enumeration. |
| [GetUnderlyingType](./getunderlyingtype/)() const override | Returns the underlying type of the specified enumeration. |
| static [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const TypeInfo\&) | Returns the underlying type of the specified enumeration. |
| [GetValueOf](./getvalueof/)(const String\&, bool) const override | Returns boxed value of the enum constant with the specified name. |
| [GetValueOf](./getvalueof/)(long) const override | Returns boxed value of the enum constant with the specified value. |
| [GetValues](./getvalues/)() const override | Returns an array containing all values of enumeration **E**. |
| static [GetValues](../enumvaluesbase/getvalues/)(const TypeInfo\&) | Returns an array containing all values of the specified enumeration type. |
| static [Parse](../enumvaluesbase/parse/)(const TypeInfo\&, const String\&, bool) | Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, uint64_t) | Converts the specified 64-bit unsigned integer value to an enumeration member. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, const SharedPtr\<Object\>\&) | Converts the specified object with an integer value to an enumeration member. |
| virtual [~EnumValues](./~enumvalues/)() | Destructor. |

## See Also

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
