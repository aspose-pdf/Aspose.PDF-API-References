---
title: "System::Reflection::PropertyInfo::PropertyInfo constructor"
linktitle: "PropertyInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Reflection::PropertyInfo::PropertyInfo constructor. Constructor. Propiedad con solo getter const en C++."
type: docs
weight: 100
url: /es/cpp/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Constructor. Propiedad con solo getter const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() const | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Constructor. Propiedad con solo getter no const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) constructor


Construye información de la propiedad boolean a partir de la clase con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(bool) | Método setter. |
| get_prop_method | bool(ClassType::*)() const | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) constructor


Construye información de la propiedad boolean.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(bool) | Método setter. |
| get_prop_method | bool(ClassType::*)() | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) constructor


Construye información de la propiedad int64_t a partir de la clase con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(int64_t) | Método setter. |
| get_prop_method | int64_t(ClassType::*)() const | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) constructor


Construye información de la propiedad int64_t.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(int64_t) | Método setter. |
| get_prop_method | int64_t(ClassType::*)() | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) constructor


Construye la información de la propiedad [Decimal](../../../system/decimal/) a partir de la clase con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(System::Decimal) | Método setter. |
| get_prop_method | System::Decimal(ClassType::*)() const | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) constructor


Construye la información de la propiedad [Decimal](../../../system/decimal/).

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(System::Decimal) | Método setter. |
| get_prop_method | System::Decimal(ClassType::*)() | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) constructor


Constructor. Propiedad [Nullable](../../../system/nullable/) con solo getter const.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(System::Nullable\<NullableType\>) | Método setter. |
| get_prop_method | System::Nullable\<NullableType\>(ClassType::*)() const | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [Nullable](../../../system/nullable/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) constructor


Constructor. Propiedad [Nullable](../../../system/nullable/) con setter y getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(System::Nullable\<NullableType\>) | Método setter. |
| get_prop_method | System::Nullable\<NullableType\>(ClassType::*)() | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [Nullable](../../../system/nullable/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Constructor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(System::SharedPtr\<PropertyType\>) | Método setter. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() const | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Constructor. Propiedad [Object](../../../system/object/) con solo getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(System::SharedPtr\<PropertyType\>) | Método setter. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) constructor


Construye información de la propiedad string a partir de la clase con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(System::String) | Método setter. |
| get_prop_method | System::String(ClassType::*)() const | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) constructor


Construye información de la propiedad string.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(System::String) | Método setter. |
| get_prop_method | System::String(ClassType::*)() | Método getter. |

## Ver también

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
