---
title: "System::Threading::Timer::Change метод"
linktitle: "Изменение"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Timer::Change метод. Перепланирует или отменяет таймер в C++."
type: docs
weight: 200
url: /ru/cpp/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) method


Перепланирует или отменяет таймер.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| dueTime | int64_t | [Timeout](../../timeout/) перед следующим вызовом функции обратного вызова, в миллисекундах; отрицательные значения отменяют таймер, даже если он был запланирован. |
| period | int64_t | [Timeout](../../timeout/) между последовательными вызовами функции обратного вызова, в миллисекундах; неположительные значения означают, что таймер должен выполниться только один раз. |

## См. также

* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Change(System::TimeSpan, System::TimeSpan) method


Перепланирует или отменяет таймер.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| dueTime | System::TimeSpan | [Timeout](../../timeout/) перед следующим вызовом функции обратного вызова; отрицательные значения отменяют таймер, даже если он был запланирован. |
| period | System::TimeSpan | [Timeout](../../timeout/) между последовательными вызовами функции обратного вызова; не положительные значения означают, что таймер должен выполниться только один раз. |

## См. также

* Class [TimeSpan](../../../system/timespan/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
