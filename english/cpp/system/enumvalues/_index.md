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
| [GetValueOf](./getvalueof/)(const String\&, bool) const override | Returns boxed value of the enum constant with the specified name. |
| [GetValues](./getvalues/)() const override | Returns an array containing all values of enumeration **E**. |
| static [GetValues](../enumvaluesbase/getvalues/)(const TypeInfo\&) | Returns an array containing all values of the specified enumeration type. |
| static [Parse](../enumvaluesbase/parse/)(const TypeInfo\&, const String\&, bool) | Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name. |
| virtual [~EnumValues](./~enumvalues/)() | Destructor. |

## See Also

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
