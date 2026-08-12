---
title: "Класс System::Reflection::PropertyInfo"
linktitle: "PropertyInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Reflection::PropertyInfo. Представляет информацию о свойстве в C++."
type: docs
weight: 1000
url: /ru/cpp/system.reflection/propertyinfo/
---
## PropertyInfo class


Представляет информацию о свойстве.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Получает значение [MemberTypes](../membertypes/), указывающее, что этот член является свойством. |
| [get_PropertyType](./get_propertytype/)() | Получает тип свойства. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>) | Получает значение свойства из конкретного объекта. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Получает значение свойства из конкретного объекта. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Конструктор. Свойство только с const‑геттером. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) | Конструктор. Свойство только с non-const‑геттером. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Конструктор. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) | Конструктор. Свойство [Nullable](../../system/nullable/) с сеттером и геттером. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) | Конструктор. Свойство [Nullable](../../system/nullable/) только с const‑геттером. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) | Конструктор. Свойство [Object](../../system/object/) только с геттером. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) | Создаёт информацию о строковом свойстве. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) | Создаёт информацию о строковом свойстве из класса с const‑геттером. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) | Создаёт информацию о свойстве [Decimal](../../system/decimal/). |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) | Создаёт информацию о свойстве [Decimal](../../system/decimal/) из класса с const‑геттером. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)()) | Создаёт информацию о булевом свойстве. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)() const) | Создаёт информацию о булевом свойстве из класса с const‑геттером. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) | Создаёт информацию о свойстве int64_t. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) | Создаёт информацию о свойстве int64_t из класса с const‑геттером. |
| [set_PropertyType](./set_propertytype/)(const TypeInfo\&) | Устанавливает тип этого свойства. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) | Устанавливает значение свойства для конкретного объекта. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Устанавливает значение свойства для конкретного объекта. |
## См. также

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
