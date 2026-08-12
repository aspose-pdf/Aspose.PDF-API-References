---
title: "System::Threading::Thread::Join метод"
linktitle: "Join"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Thread::Join метод. Присоединяет управляемый поток. Выполняет неограниченное ожидание при необходимости в C++."
type: docs
weight: 1400
url: /ru/cpp/system.threading/thread/join/
---
## Thread::Join() method


Ожидает завершения управляемого потока. Выполняет неограниченное ожидание при необходимости.

```cpp
void System::Threading::Thread::Join()
```

## См. также

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Thread::Join(int) method


Ожидает завершения управляемого потока. Выполняет ограниченное ожидание.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | Тайм‑аут ожидания в миллисекундах. |

### ReturnValue

True, если поток был успешно присоединён, false, если тайм-аут превышен.

## См. также

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Thread::Join(TimeSpan) method


Ожидает завершения управляемого потока. Выполняет ограниченное ожидание.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| timeout | TimeSpan | Объект [TimeSpan](../../../system/timespan/) задающий количество времени для ожидания завершения потока. |

### ReturnValue

True, если поток был успешно присоединён, false, если тайм-аут превышен.

## См. также

* Class [TimeSpan](../../../system/timespan/)
* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
