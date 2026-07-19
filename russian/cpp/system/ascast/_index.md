---
title: "Метод System::AsCast"
linktitle: "AsCast"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::AsCast. Приводит тип источника к типу результата с помощью оператора приведения ''as''. Используется, когда в C++ требуется простое приведение, похожее на конструктор."
type: docs
weight: 14000
url: /ru/cpp/system/ascast/
---
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью оператора приведения 'as'. Используется, когда требуется простое приведение, похожее на конструктор.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью оператора приведения 'as'. Используется, когда типы источника и результата одинаковы.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью оператора приведения 'as'. Используется для обёрток исключений.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения. Возвращает nullptr, если преобразование недоступно.

## См. также

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется для приведения объекта к исключению.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения. Возвращает nullptr, если преобразование недоступно.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется, когда и источник, и результат являются умными указателями.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения. Возвращает nullptr, если преобразование недоступно.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется, когда и источник, и результат являются умными указателями (с явным [SmartPtr<...>](../smartptr/) в типе результата).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения. Возвращает nullptr, если преобразование недоступно.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется для распаковки объекта в nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения. Возвращает пустой nullable, если преобразование недоступно.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Недопустимая распаковка в не-объектный тип.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Всегда возвращает null.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Недопустимая распаковка в не-объектный тип.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Всегда возвращает null.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется для упаковки nullable-объекта.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется для упаковки обычного объекта.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется для упаковки обычного объекта.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется для распаковки строки.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется для приведения к nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Преобразует тип источника в тип результата с помощью приведения оператором 'as'. Используется для приведения между массивами.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Параметр | Описание |
| --- | --- |
| Источник | Тип источника. |
| Результат | Тип результата. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) для приведения. |

### ReturnValue

Результат приведения. Возвращает nullptr, если преобразование для любого элемента массива недоступно.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
