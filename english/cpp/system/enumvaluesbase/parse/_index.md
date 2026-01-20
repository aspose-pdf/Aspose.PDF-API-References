---
title: System::EnumValuesBase::Parse method
linktitle: Parse
second_title: Aspose.PDF for C++ API Reference
description: 'System::EnumValuesBase::Parse method. Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name in C++.'
type: docs
weight: 400
url: /cpp/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse method


Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | const TypeInfo\& | The [TypeInfo](../../typeinfo/) object representing the type of the enumeration value to return |
| str | const String\& | The name of the enum constant |
| ignoreCase | bool | Specifeis if the case should be ignored when interpreting the name of the enum constant |

### ReturnValue

An object that represents the value of the enum constant whose name is specified in **str**.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
