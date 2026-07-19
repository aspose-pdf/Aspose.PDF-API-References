---
title: "System::Threading::WaitHandle::WaitAll метод"
linktitle: "WaitAll"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::WaitHandle::WaitAll метод. Ожидает, пока все дескрипторы не сработают в C++."
type: docs
weight: 100
url: /ru/cpp/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


Ожидает срабатывания всех дескрипторов.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Дескрипторы для ожидания. |

### ReturnValue

Истина, когда каждый элемент в waitHandles получил сигнал; иначе метод никогда не возвращается.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


Информация RTTI.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Дескрипторы для ожидания. |
| millisecondsTimeout | int | [Timeout](../../timeout/) для ожидания, в миллисекундах; -1 означает бесконечное ожидание, 0 — проверка и возврат, положительные значения — тайм-ауты. |

### ReturnValue

Истина, если все дескрипторы сработали, ложь, если тайм-аут превышен.
## Примечания


Ожидает срабатывания всех дескрипторов.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


Ожидает срабатывания всех дескрипторов.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Дескрипторы для ожидания. |
| timeout | TimeSpan | Объект [System::TimeSpan](../../../system/timespan/), представляющий количество миллисекунд для ожидания, или объект [System::TimeSpan](../../../system/timespan/), представляющий -1 миллисекунду для бесконечного ожидания. |

### ReturnValue

Истина, если все дескрипторы сработали, ложь, если тайм-аут превышен.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
