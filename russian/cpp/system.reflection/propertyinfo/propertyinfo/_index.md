---
title: "System::Reflection::PropertyInfo::PropertyInfo конструктор"
linktitle: "PropertyInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Reflection::PropertyInfo::PropertyInfo конструктор. Конструктор. Свойство только с const геттером в C++."
type: docs
weight: 100
url: /ru/cpp/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Конструктор. Свойство только с const‑геттером.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() const | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Конструктор. Свойство только с non-const‑геттером.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) constructor


Создаёт информацию о булевом свойстве из класса с const‑геттером.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(bool) | Метод установки. |
| get_prop_method | bool(ClassType::*)() const | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) constructor


Создаёт информацию о булевом свойстве.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(bool) | Метод установки. |
| get_prop_method | bool(ClassType::*)() | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) constructor


Создаёт информацию о свойстве int64_t из класса с const‑геттером.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(int64_t) | Метод установки. |
| get_prop_method | int64_t(ClassType::*)() const | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) constructor


Создаёт информацию о свойстве int64_t.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(int64_t) | Метод установки. |
| get_prop_method | int64_t(ClassType::*)() | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) constructor


Создаёт информацию о свойстве [Decimal](../../../system/decimal/) из класса с const‑геттером.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(System::Decimal) | Метод установки. |
| get_prop_method | System::Decimal(ClassType::*)() const | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) constructor


Создаёт информацию о свойстве [Decimal](../../../system/decimal/).

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(System::Decimal) | Метод установки. |
| get_prop_method | System::Decimal(ClassType::*)() | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) constructor


Конструктор. Свойство [Nullable](../../../system/nullable/) только с const‑геттером.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(System::Nullable\<NullableType\>) | Метод установки. |
| get_prop_method | System::Nullable\<NullableType\>(ClassType::*)() const | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [Nullable](../../../system/nullable/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) constructor


Конструктор. Свойство [Nullable](../../../system/nullable/) с сеттером и геттером.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(System::Nullable\<NullableType\>) | Метод установки. |
| get_prop_method | System::Nullable\<NullableType\>(ClassType::*)() | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [Nullable](../../../system/nullable/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Конструктор.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(System::SharedPtr\<PropertyType\>) | Метод установки. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() const | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Конструктор. Свойство [Object](../../../system/object/) только с геттером.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(System::SharedPtr\<PropertyType\>) | Метод установки. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) constructor


Создаёт информацию о строковом свойстве из класса с const‑геттером.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(System::String) | Метод установки. |
| get_prop_method | System::String(ClassType::*)() const | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) constructor


Создаёт информацию о строковом свойстве.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, к которому принадлежит свойство. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя свойства. |
| set_prop_method | void(ClassType::*)(System::String) | Метод установки. |
| get_prop_method | System::String(ClassType::*)() | Метод получения. |

## См. также

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
