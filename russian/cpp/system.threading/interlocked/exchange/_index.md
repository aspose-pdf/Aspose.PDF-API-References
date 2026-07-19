---
title: "System::Threading::Interlocked::Exchange метод"
linktitle: "Exchange"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Interlocked::Exchange метод. Обменивает значение переменной: сохраняет новое значение и возвращает значение, которое переменная имела непосредственно перед сохранением, в C++."
type: docs
weight: 400
url: /ru/cpp/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) method


Обменивает значение переменной: сохраняет новое значение и возвращает значение переменной, которое было непосредственно перед сохранением.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


| Параметр | Описание |
| --- | --- |
| T | Тип переменной. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| location1 | T\& | Ссылка на переменную для изменения. |
| value | T | Значение для сохранения. |

### ReturnValue

Значение переменной непосредственно перед изменением.

## См. также

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::Exchange(T\&, T) method


Обменивает значение переменной: сохраняет новое значение и возвращает значение переменной, которое было непосредственно перед сохранением. Не реализовано.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


| Параметр | Описание |
| --- | --- |
| T | Тип переменной. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| location1 | T\& | Ссылка на переменную для изменения. |
| value | T | Значение для сохранения. |

### ReturnValue

Значение переменной непосредственно перед изменением.

## См. также

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
