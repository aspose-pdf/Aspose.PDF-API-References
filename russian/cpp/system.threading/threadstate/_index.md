---
title: "System::Threading::ThreadState enum"
linktitle: "ThreadState"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::ThreadState enum. Состояние потока в C++."
type: docs
weight: 2000
url: /ru/cpp/system.threading/threadstate/
---
## ThreadState enum


Состояние потока.

```cpp
enum class ThreadState
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) работает. |
| StopRequested | 1 | [Thread](../thread/) остановка запрошена. |
| SuspendRequested | 2 | [Thread](../thread/) приостановка запрошена. |
| Фоновый | 4 | Поток выполняется в фоновом режиме. |
| Unstarted | 8 | [Thread](../thread/) не запущен. |
| Stopped | 16 | [Thread](../thread/) остановлен. |
| WaitSleepJoin | 32 | [Thread](../thread/) ожидает присоединения. |
| Suspended | 64 | [Thread](../thread/) приостановлен. |
| AbortRequested | 128 | [Thread](../thread/) запрошено прерывание. |
| Aborted | 256 | [Thread](../thread/) прерван. |

## См. также

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
