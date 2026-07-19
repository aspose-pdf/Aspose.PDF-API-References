---
title: "Конструктор System::Threading::Timer::Timer"
linktitle: "Timer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::Threading::Timer::Timer. Конструктор на C++."
type: docs
weight: 100
url: /ru/cpp/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor


Конструктор.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | TimerCallback | Функция, вызываемая таймером. |

## См. также

* Typedef [TimerCallback](../../timercallback/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor


Конструктор.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | TimerCallback | Функция, вызываемая таймером. |
| state | const System::SharedPtr\<System::Object\>\& | Аргумент функции обратного вызова. |
| dueTime | int64_t | [Timeout](../../timeout/) перед первым вызовом функции обратного вызова, в миллисекундах; отрицательные значения не планируют таймер после создания, поэтому его можно перенастроить позже. |
| period | int64_t | [Timeout](../../timeout/) между последовательными вызовами функции обратного вызова, в миллисекундах; неположительные значения означают, что таймер должен выполниться только один раз. |

## См. также

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor


Конструктор.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | TimerCallback | Функция, вызываемая таймером. |
| state | const System::SharedPtr\<System::Object\>\& | Аргумент функции обратного вызова. |
| dueTime | System::TimeSpan | [Timeout](../../timeout/) перед первым вызовом функции обратного вызова; отрицательные значения не планируют таймер после создания, поэтому его можно перенастроить позже. |
| period | System::TimeSpan | [Timeout](../../timeout/) между последовательными вызовами функции обратного вызова; не положительные значения означают, что таймер должен выполниться только один раз. |

## См. также

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
