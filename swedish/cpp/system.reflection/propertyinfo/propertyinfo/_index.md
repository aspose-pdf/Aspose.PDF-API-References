---
title: "System::Reflection::PropertyInfo::PropertyInfo konstruktor"
linktitle: "PropertyInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Reflection::PropertyInfo::PropertyInfo konstruktor. Konstruktor. Egenskap med endast const-getter i C++."
type: docs
weight: 100
url: /sv/cpp/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Konstruktor. Egenskap med endast const-getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() const | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Konstruktor. Egenskap med endast icke-const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) constructor


Skapar information om boolesk egenskap från klass med const-getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(bool) | Setter-metod. |
| get_prop_method | bool(ClassType::*)() const | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) constructor


Skapar information om boolesk egenskap.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(bool) | Setter-metod. |
| get_prop_method | bool(ClassType::*)() | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) constructor


Skapar information om int64_t-egenskap från klass med const-getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(int64_t) | Setter-metod. |
| get_prop_method | int64_t(ClassType::*)() const | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) constructor


Skapar information om int64_t-egenskap.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(int64_t) | Setter-metod. |
| get_prop_method | int64_t(ClassType::*)() | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) constructor


Skapar [Decimal](../../../system/decimal/) egenskapsinformation från klass med const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(System::Decimal) | Setter-metod. |
| get_prop_method | System::Decimal(ClassType::*)() const | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) constructor


Skapar [Decimal](../../../system/decimal/) egenskapsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(System::Decimal) | Setter-metod. |
| get_prop_method | System::Decimal(ClassType::*)() | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) constructor


Konstruktor. [Nullable](../../../system/nullable/) egenskap med endast const getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(System::Nullable\<NullableType\>) | Setter-metod. |
| get_prop_method | System::Nullable\<NullableType\>(ClassType::*)() const | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [Nullable](../../../system/nullable/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) constructor


Konstruktor. [Nullable](../../../system/nullable/) egenskap med setter och getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(System::Nullable\<NullableType\>) | Setter-metod. |
| get_prop_method | System::Nullable\<NullableType\>(ClassType::*)() | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [Nullable](../../../system/nullable/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Konstruktor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(System::SharedPtr\<PropertyType\>) | Setter-metod. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() const | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Konstruktor. [Object](../../../system/object/) egenskap med endast getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(System::SharedPtr\<PropertyType\>) | Setter-metod. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) constructor


Skapar information om string-egenskap från klass med const-getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(System::String) | Setter-metod. |
| get_prop_method | System::String(ClassType::*)() const | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) constructor


Skapar information om string-egenskap.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(System::String) | Setter-metod. |
| get_prop_method | System::String(ClassType::*)() | Getter-metod. |

## Se även

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
