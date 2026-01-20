---
title: System::Reflection::PropertyInfo class
linktitle: PropertyInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::PropertyInfo class. Represents property information in C++.'
type: docs
weight: 1000
url: /cpp/system.reflection/propertyinfo/
---
## PropertyInfo class


Represents property information.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Methods

| Method | Description |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Gets a [MemberTypes](../membertypes/) value indicating that this member is a property. |
| [get_PropertyType](./get_propertytype/)() | Gets property type. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>) | Gets property value from specific object. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Gets property value from specific object. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Constructor. Property with only const getter. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) | Constructor. Property with only non-const getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Constructor. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) | Constructor. [Nullable](../../system/nullable/) property with setter and getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) | Constructor. [Nullable](../../system/nullable/) property with const getter only. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) | Constructor. [Object](../../system/object/) property with getter only. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) | Constructs string property information. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) | Constructs string property information from class with const getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) | Constructs [Decimal](../../system/decimal/) property information. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) | Constructs [Decimal](../../system/decimal/) property information from class with const getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)()) | Constructs boolean property information. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)() const) | Constructs boolean property information from class with const getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) | Constructs int64_t property information. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) | Constructs int64_t property information from class with const getter. |
| [set_PropertyType](./set_propertytype/)(const TypeInfo\&) | Sets the type of this property. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) | Sets property value to specific object. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Sets property value to specific object. |
## See Also

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
