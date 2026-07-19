---
title: "System::ExplicitCast method"
linktitle: "ExplicitCast"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ExplicitCast. Преобразует исходный тип в тип результата с использованием явного приведения. Используется, когда исходный и результирующий типы одинаковы в C++."
type: docs
weight: 19000
url: /ru/cpp/system/explicitcast/
---
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется, когда исходный и результирующий типы одинаковы.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Enum [Base64FormattingOptions](../base64formattingoptions/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется, когда требуется простое приведение, похожее на конструктор.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для обёрток исключений.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для приведения объекта к исключению.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется, когда и исходный, и результирующий типы являются умными указателями (без явного [SmartPtr<...>](../smartptr/) в типе результата).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется, когда и исходный, и результирующий типы являются умными указателями (с явным [SmartPtr<...>](../smartptr/) в типе результата).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для распаковки объекта в nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для упаковки nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для распаковки nullable‑объекта.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для упаковки enum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для копирования значимых типов в кучу, когда значимый тип должен быть представлен как умный указатель (в обобщениях, ограниченных типом интерфейса, но специализированных структурой, реализующей этот интерфейс).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для получения интерфейсов из значимых типов.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для общей упаковки.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для упаковки [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для распаковки интерфейсов.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для общей распаковки.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для приведения к nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется для приведения между массивами.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(Source) method


Преобразует исходный тип в тип результата с использованием явного приведения. Используется при приведении сырого указателя к умному указателю.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | Source | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
