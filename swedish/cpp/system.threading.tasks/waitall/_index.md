---
title: "System::Threading::Tasks::WaitAll metod"
linktitle: "WaitAll"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::WaitAll metod. Väntar på att alla de tillhandahållna Task‑objekten ska slutföra körning i C++."
type: docs
weight: 2000
url: /sv/cpp/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) method


Väntar på att alla de tillhandahållna [Task](../task/)-objekten ska slutföra körning.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | En array av [Task](../task/)-instanser att vänta på. |

## Se även

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) method


Väntar på att alla de tillhandahållna [Task](../task/)-objekten ska slutföra körning.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | En array av [Task](../task/)-instanser att vänta på. |
| cancellationToken | const CancellationToken\& | En [CancellationToken](../../system.threading/cancellationtoken/) att observera medan du väntar på att taskarna ska slutföras. |

## Se även

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
