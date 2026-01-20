---
title: System::Reflection::PropertyInfo::PropertyInfo constructor
linktitle: PropertyInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::PropertyInfo::PropertyInfo constructor. Constructor. Property with only const getter in C++.'
type: docs
weight: 100
url: /cpp/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Constructor. Property with only const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() const | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Constructor. Property with only non-const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) constructor


Constructs boolean property information from class with const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(bool) | Setter method. |
| get_prop_method | bool(ClassType::*)() const | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) constructor


Constructs boolean property information.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(bool) | Setter method. |
| get_prop_method | bool(ClassType::*)() | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) constructor


Constructs int64_t property information from class with const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(int64_t) | Setter method. |
| get_prop_method | int64_t(ClassType::*)() const | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) constructor


Constructs int64_t property information.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(int64_t) | Setter method. |
| get_prop_method | int64_t(ClassType::*)() | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) constructor


Constructs [Decimal](../../../system/decimal/) property information from class with const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(System::Decimal) | Setter method. |
| get_prop_method | System::Decimal(ClassType::*)() const | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) constructor


Constructs [Decimal](../../../system/decimal/) property information.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(System::Decimal) | Setter method. |
| get_prop_method | System::Decimal(ClassType::*)() | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) constructor


Constructor. [Nullable](../../../system/nullable/) property with const getter only.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(System::Nullable\<NullableType\>) | Setter method. |
| get_prop_method | System::Nullable\<NullableType\>(ClassType::*)() const | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [Nullable](../../../system/nullable/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) constructor


Constructor. [Nullable](../../../system/nullable/) property with setter and getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(System::Nullable\<NullableType\>) | Setter method. |
| get_prop_method | System::Nullable\<NullableType\>(ClassType::*)() | Getter method. |

## See Also

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


| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(System::SharedPtr\<PropertyType\>) | Setter method. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() const | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Constructor. [Object](../../../system/object/) property with getter only.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(System::SharedPtr\<PropertyType\>) | Setter method. |
| get_prop_method | System::SharedPtr\<PropertyType\>(ClassType::*)() | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) constructor


Constructs string property information from class with const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(System::String) | Setter method. |
| get_prop_method | System::String(ClassType::*)() const | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) constructor


Constructs string property information.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Property name. |
| set_prop_method | void(ClassType::*)(System::String) | Setter method. |
| get_prop_method | System::String(ClassType::*)() | Getter method. |

## See Also

* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
