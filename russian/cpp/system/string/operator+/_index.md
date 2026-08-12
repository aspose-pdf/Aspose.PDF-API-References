---
title: "System::String::operator+ метод"
linktitle: "operator+"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::String::operator+ метод. Добавляет символ в конец строки в C++."
type: docs
weight: 2800
url: /ru/cpp/system/string/operator+/
---
## String::operator+(char_t) const method


Добавляет символ в конец строки.

```cpp
String System::String::operator+(char_t x) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | char_t | Символ для добавления. |

### ReturnValue

[String](../) concatenation result.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const String\&) const method


[String](../) concatenation operator.

```cpp
String System::String::operator+(const String &str) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | [String](../) для добавления в конец текущей. |

### ReturnValue

Конкатенированная строка.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


[String](../) concatenation with string literal or character string pointer.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


| Параметр | Описание |
| --- | --- |
| T | Одна из форм строкового литерала или указателя на строку символов. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg | const T\& | Сущность для конкатенации с текущей строкой. |

### ReturnValue

Конкатенированная строка.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


Добавляет строковое представление объекта ссылочного типа в конец строки.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


| Параметр | Описание |
| --- | --- |
| T | тип указателя. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) для преобразования в строку с помощью вызова [ToString()](../tostring/) и добавления к текущей строке. |

### ReturnValue

[String](../) concatenation result.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


Добавляет строковое представление объекта значимого типа в конец строки.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения, для которого вызывается [ToString()](../tostring/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) для преобразования в строку с помощью вызова [ToString()](../tostring/) и добавления к текущей строке. |

### ReturnValue

[String](../) concatenation result.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(double) const method


Добавляет строковое представление числа с плавающей точкой в конец строки.

```cpp
String System::String::operator+(double d) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| d | double | Значение для преобразования в строку и добавления. |

### ReturnValue

[String](../) concatenation result.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(int) const method


Добавляет строковое представление целочисленного значения в конец строки.

```cpp
String System::String::operator+(int i) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int | Целочисленное значение для преобразования в строку и добавления. |

### ReturnValue

[String](../) concatenation result.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(int64_t) const method


Добавляет строковое представление целочисленного значения в конец строки.

```cpp
String System::String::operator+(int64_t v) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| v | int64_t | Значение для преобразования в строку и добавления к добавлению. |

### ReturnValue

[String](../) concatenation result.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(T) const method


Добавляет строковое представление логического значения в конец строки.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения для конкатенации со строкой. Должен быть bool |

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) значение для преобразования в строку и добавления. |

### ReturnValue

[String](../) concatenation result.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(uint32_t) const method


Добавляет строковое представление беззнакового целого значения в конец строки.

```cpp
String System::String::operator+(uint32_t i) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | uint32_t | Значение для преобразования в строку и добавления. |

### ReturnValue

[String](../) concatenation result.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
