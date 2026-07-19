---
title: "Метод System::ObjectExt::ToString"
linktitle: "ToString"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ObjectExt::ToString. Замена метода ToString из C# для работы с любым типом C++ в C++."
type: docs
weight: 1400
url: /ru/cpp/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) литерал для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const Nullable\<T\>\&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


| Параметр | Описание |
| --- | --- |
| T | [Nullable](../../nullable/) тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const Nullable\<T\>\& | [Nullable](../../nullable/) объект для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | [Enum](../../enum/) тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) значение для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип умного указателя. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) значение для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип структуры. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | Значение структуры для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Параметр | Описание |
| --- | --- |
| T | Скалярный тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\&& | Скалярное значение для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Параметр | Описание |
| --- | --- |
| T | Скалярный тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\&& | Скалярное значение для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип умного указателя или [ExceptionWrapper](../../exceptionwrapper/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\& | Умный указатель или [ExceptionWrapper](../../exceptionwrapper/) для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Скалярный тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\& | Скалярное значение для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип структуры. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\& | Значение структуры для преобразования в строку. |

### ReturnValue

[String](../../string/) representation of **obj**.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
