---
title: "método System::ObjectType::GetType"
linktitle: "GetType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "método System::ObjectType::GetType. Implementa la traducción de typeof(). Sobrecarga para tipos primitivos en C++."
type: docs
weight: 100
url: /es/cpp/system/objecttype/gettype/
---
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para tipos primitivos.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo especificado.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para tipos enumerados.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo especificado.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para estructuras y punteros.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la estructura especificada.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la estructura especificada.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo MutlicastDelegate. |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la estructura especificada.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para estructuras y punteros.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la estructura especificada o el tipo apuntado si se solicita para [SmartPtr](../../smartptr/).

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para uint8_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Ver también

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Ver también

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para int32_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Ver también

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para int64_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Ver también

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Ver también

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementa la traducción de typeof(). Sobrecarga para [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Ver también

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const String\&) method


Implementa la traducción de typeof(). Sobrecarga para tipo string.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo [String](../../string/).

## Ver también

* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implementa la traducción de typeof(). Sobrecarga para punteros inteligentes.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto puntero. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obtener [TypeInfo](../../typeinfo/). |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la clase final del objeto pasado.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implementa la traducción de typeof(). Sobrecarga para estructuras.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de estructura. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obtener [TypeInfo](../../typeinfo/). |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la clase final del objeto pasado.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implementa la traducción de typeof(). Sobrecarga para excepciones.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Exception](../../exception/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obtener [TypeInfo](../../typeinfo/). |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la clase final del objeto pasado.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T) method


Implementa la traducción de typeof(). Sobrecarga para tipos primitivos.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T | IGNORED |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo del objeto pasado.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T) method


Implementa la traducción de typeof(). Sobrecarga para tipos [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T | IGNORED |

### ReturnValue

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo del objeto pasado.

## Ver también

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
