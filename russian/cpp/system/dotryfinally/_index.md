---
title: "Метод System::DoTryFinally"
linktitle: "DoTryFinally"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::DoTryFinally. Единственная функция, эмулирующая поведение оператора try[-catch]-finally в C#. При переводе оператора try[-catch]-finally из C# с включённой опцией переводчика finally_statement_as_lambda, установленной в true, оператор переводится в вызов этого метода в C++."
type: docs
weight: 17000
url: /ru/cpp/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) method


Единственная функция, эмулирующая поведение оператора try[-catch]-finally в C#. При переводе оператора try[-catch]-finally из C# с включённой опцией переводчика finally_statement_as_lambda, установленной в true, оператор переводится в вызов этого метода.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объект‑функции, реализующего часть try[-catch] оператора try[-catch]-finally, который эмулируется. |
| F | Тип объект‑функции, реализующего часть finally оператора try[-catch]-finally, который эмулируется. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryBlock | T\&& | Объект‑функция, тело которого содержит реализацию части try[-catch] оператора try[-catch]-finally, который эмулируется |
| finallyBlock | F\\&& | Объект функции, тело которого содержит реализацию части finally оператора try[-catch]-finally, эмулируемого |

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DoTryFinally(T\&&, F\&&) method


Единственная функция, эмулирующая поведение оператора try[-catch]-finally в C#. При переводе оператора try[-catch]-finally в C# с включённой опцией переводчика finally_statement_as_lambda, установленной в true, оператор переводится в вызов этого метода. Эта перегрузка обрабатывает случай, когда значение, возвращаемое объектом функции, реализующей часть try[-catch] оператора try[-catch]-finally, имеет тип bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объект‑функции, реализующего часть try[-catch] оператора try[-catch]-finally, который эмулируется. |
| F | Тип объект‑функции, реализующего часть finally оператора try[-catch]-finally, который эмулируется. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryBlock | T\&& | Объект‑функция, тело которого содержит реализацию части try[-catch] оператора try[-catch]-finally, который эмулируется |
| finallyBlock | F\\&& | Объект функции, тело которого содержит реализацию части finally оператора try[-catch]-finally, эмулируемого |

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DoTryFinally(T\&&, F\&&) method


Единственная функция, эмулирующая поведение оператора try[-catch]-finally в C#. При переводе оператора try[-catch]-finally в C# с включённой опцией переводчика finally_statement_as_lambda, установленной в true, оператор переводится в вызов этого метода. Эта перегрузка обрабатывает случай, когда значение, возвращаемое объектом функции, реализующей часть try[-catch] оператора try[-catch]-finally, имеет тип bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объект‑функции, реализующего часть try[-catch] оператора try[-catch]-finally, который эмулируется. |
| F | Тип объект‑функции, реализующего часть finally оператора try[-catch]-finally, который эмулируется. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| tryBlock | T\&& | Объект‑функция, тело которого содержит реализацию части try[-catch] оператора try[-catch]-finally, который эмулируется |
| finallyBlock | F\\&& | Объект функции, тело которого содержит реализацию части finally оператора try[-catch]-finally, эмулируемого |

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
