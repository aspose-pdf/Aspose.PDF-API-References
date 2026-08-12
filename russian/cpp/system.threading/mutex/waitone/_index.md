---
title: "Метод System::Threading::Mutex::WaitOne"
linktitle: "WaitOne"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::Mutex::WaitOne. Блокирует мьютекс. Выполняет неограниченное ожидание при необходимости в C++."
type: docs
weight: 500
url: /ru/cpp/system.threading/mutex/waitone/
---
## Mutex::WaitOne() method


Блокирует мьютекс. При необходимости выполняет неограниченное ожидание.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### ReturnValue

Всегда возвращает true, так как не возвращается, пока мьютекс не будет заблокирован.

## См. также

* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Mutex::WaitOne(int) method


Блокирует мьютекс. При необходимости выполняет ожидание.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | Тайм‑аут ожидания в миллисекундах. |

### ReturnValue

Возвращает true, если мьютекс был заблокирован, или false, если время ожидания превышено.

## См. также

* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Mutex::WaitOne(TimeSpan) method


Блокирует мьютекс. При необходимости выполняет ожидание.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| timeout | TimeSpan | Объект [System::TimeSpan](../../../system/timespan/), представляющий количество миллисекунд для ожидания, или объект [System::TimeSpan](../../../system/timespan/), представляющий -1 миллисекунду для бесконечного ожидания. |

### ReturnValue

Возвращает true, если мьютекс был заблокирован, или false, если время ожидания превышено.

## См. также

* Class [TimeSpan](../../../system/timespan/)
* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
