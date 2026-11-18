---
title: System::Reflection::ParameterInfo class
linktitle: ParameterInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::ParameterInfo class. Discovers the attributes of a parameter and provides access to parameter metadata. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.reflection/parameterinfo/
---
## ParameterInfo class


Discovers the attributes of a parameter and provides access to parameter metadata. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ParameterInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_DefaultValue](./get_defaultvalue/)() const | Gets the default value of the parameter. |
| [get_IsIn](./get_isin/)() const | Gets a value indicating whether this is an input parameter. |
| [get_IsOptional](./get_isoptional/)() const | Gets a value indicating whether this parameter is optional. |
| [get_IsOut](./get_isout/)() const | Gets a value indicating whether this is an output parameter. |
| [get_IsRetval](./get_isretval/)() const | Gets a value indicating whether this is a Retval parameter. |
| [get_Name](./get_name/)() const | Gets the name of the parameter. |
| [get_ParameterType](./get_parametertype/)() const | Gets the type of this parameter. |
| [get_Position](./get_position/)() const | Gets the zero-based position of the parameter in the formal parameter list. |
| [ParameterInfo](./parameterinfo/)() | Initializes a new instance of the [ParameterInfo](./) class. |
| [ParameterInfo](./parameterinfo/)(const String\&, int, const TypeInfo\&) | Initializes a new instance of the [ParameterInfo](./) class. |
| [SetName](./setname/)(const String\&) | Sets the name of the parameter. |
| [SetOptional](./setoptional/)(bool) | Sets the optional flag. |
| [SetParameterType](./setparametertype/)(const TypeInfo\&) | Sets the type of the parameter. |
| [SetPosition](./setposition/)(int) | Sets the position of the parameter in the parameter list. |
| [ToString](./tostring/)() const override | Returns a string that represents the current [ParameterInfo](./). |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
