---
title: "Метод System::ObjectType::GetType"
linktitle: "GetType"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ObjectType::GetType. Реализует перевод typeof(). Перегрузка для примитивных типов в C++."
type: docs
weight: 100
url: /ru/cpp/system/objecttype/gettype/
---
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для примитивных типов.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанный тип.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для enum‑типов.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанный тип.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для структур и указателей.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанную структуру.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Параметр | Описание |
| --- | --- |
| T | [Nullable](../../nullable/) тип. |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанную структуру.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Параметр | Описание |
| --- | --- |
| T | Тип MutlicastDelegate. |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанную структуру.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для структур и указателей.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанную структуру или тип указываемого объекта, если вызывается для [SmartPtr](../../smartptr/).

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для uint8_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для int32_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для int64_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Реализует перевод typeof(). Перегрузка для [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const String\&) method


Реализует перевод typeof(). Перегрузка для строкового типа.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую тип [String](../../string/).

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Реализует перевод typeof(). Перегрузка для умных указателей.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип указателя объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для получения [TypeInfo](../../typeinfo/). |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую конечный класс переданного объекта.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Реализует перевод typeof(). Перегрузка для структур.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип структуры. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для получения [TypeInfo](../../typeinfo/). |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую конечный класс переданного объекта.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Реализует перевод typeof(). Перегрузка для исключений.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип [Exception](../../exception/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для получения [TypeInfo](../../typeinfo/). |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую конечный класс переданного объекта.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T) method


Реализует перевод typeof(). Перегрузка для примитивных типов.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T | IGNORED |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую тип переданного объекта.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T) method


Реализует перевод typeof(). Перегрузка для типов [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


| Параметр | Описание |
| --- | --- |
| T | [Nullable](../../nullable/) тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T | IGNORED |

### ReturnValue

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую тип переданного объекта.

## См. также

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
