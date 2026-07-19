---
title: "System::Threading::WaitHandle::WaitOne метод"
linktitle: "WaitOne"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::WaitHandle::WaitOne метод. Ожидает, пока дескриптор не сработает бесконечно в C++."
type: docs
weight: 600
url: /ru/cpp/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() method


Ожидает срабатывания дескриптора бесконечно долго.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### ReturnValue

Всегда возвращает истину, так как тайм-аут не происходит.

## См. также

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(int) method


Ожидает срабатывания дескриптора.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) для ожидания, в миллисекундах; -1 означает бесконечное ожидание, 0 — проверка и возврат, положительные значения — тайм-ауты. |

### ReturnValue

Истина, если дескриптор сработал, ложь, если тайм-аут превышен.

## См. также

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(int, bool) method


Ожидает срабатывания дескриптора.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) для ожидания, в миллисекундах; -1 означает бесконечное ожидание, 0 — проверка и возврат, положительные значения — тайм-ауты. |
| exitContext | bool | Если истина, ожидание должно снять блокировку с дескриптора перед ожиданием. |

### ReturnValue

Истина, если дескриптор сработал, ложь, если тайм-аут превышен.

## См. также

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(TimeSpan) method


Ожидает срабатывания дескриптора.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| timeout | TimeSpan | Объект [System::TimeSpan](../../../system/timespan/), представляющий количество миллисекунд для ожидания, или объект [System::TimeSpan](../../../system/timespan/), представляющий -1 миллисекунду для бесконечного ожидания. |

### ReturnValue

Истина, если дескриптор сработал, ложь, если тайм-аут превышен.

## См. также

* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
