---
title: "System::Reflection::PropertyInfo-klass"
linktitle: "PropertyInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Reflection::PropertyInfo-klass. Representerar egenskapsinformation i C++."
type: docs
weight: 1000
url: /sv/cpp/system.reflection/propertyinfo/
---
## PropertyInfo class


Representerar egenskapsinformation.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Hämtar ett [MemberTypes](../membertypes/)-värde som indikerar att denna medlem är en egenskap. |
| [get_PropertyType](./get_propertytype/)() | Hämtar egenskapstyp. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>) | Hämtar egenskapsvärde från ett specifikt objekt. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Hämtar egenskapsvärde från ett specifikt objekt. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Konstruktor. Egenskap med endast const-getter. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) | Konstruktor. Egenskap med endast icke-const getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Konstruktor. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) | Konstruktor. [Nullable](../../system/nullable/) egenskap med setter och getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) | Konstruktor. [Nullable](../../system/nullable/) egenskap med endast const-getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) | Konstruktor. [Object](../../system/object/) egenskap med endast getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) | Skapar information om string-egenskap. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) | Skapar information om string-egenskap från klass med const-getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) | Skapar information om [Decimal](../../system/decimal/) egenskap. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) | Skapar information om [Decimal](../../system/decimal/) egenskap från klass med const-getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)()) | Skapar information om boolesk egenskap. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)() const) | Skapar information om boolesk egenskap från klass med const-getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) | Skapar information om int64_t-egenskap. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) | Skapar information om int64_t-egenskap från klass med const-getter. |
| [set_PropertyType](./set_propertytype/)(const TypeInfo\&) | Ställer in typen för denna egenskap. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) | Sätter egenskapsvärde på ett specifikt objekt. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Sätter egenskapsvärde på ett specifikt objekt. |
## Se även

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
