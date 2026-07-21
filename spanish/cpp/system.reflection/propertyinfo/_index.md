---
title: "Clase System::Reflection::PropertyInfo"
linktitle: "PropertyInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Reflection::PropertyInfo. Representa la información de la propiedad en C++."
type: docs
weight: 1000
url: /es/cpp/system.reflection/propertyinfo/
---
## PropertyInfo class


Representa información de la propiedad.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Obtiene un valor [MemberTypes](../membertypes/) que indica que este miembro es una propiedad. |
| [get_PropertyType](./get_propertytype/)() | Obtiene el tipo de la propiedad. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>) | Obtiene el valor de la propiedad de un objeto específico. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Obtiene el valor de la propiedad de un objeto específico. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Constructor. Propiedad con solo getter const. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) | Constructor. Propiedad con solo getter no const. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Constructor. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) | Constructor. Propiedad [Nullable](../../system/nullable/) con setter y getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) | Constructor. Propiedad [Nullable](../../system/nullable/) con solo getter const. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) | Constructor. Propiedad [Object](../../system/object/) con solo getter. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) | Construye información de la propiedad string. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) | Construye información de la propiedad string a partir de la clase con getter const. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) | Construye información de la propiedad [Decimal](../../system/decimal/). |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) | Construye información de la propiedad [Decimal](../../system/decimal/) a partir de la clase con getter const. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)()) | Construye información de la propiedad boolean. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)() const) | Construye información de la propiedad boolean a partir de la clase con getter const. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) | Construye información de la propiedad int64_t. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) | Construye información de la propiedad int64_t a partir de la clase con getter const. |
| [set_PropertyType](./set_propertytype/)(const TypeInfo\&) | Establece el tipo de esta propiedad. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) | Establece el valor de la propiedad en un objeto específico. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Establece el valor de la propiedad en un objeto específico. |
## Ver también

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
