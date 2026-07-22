---
title: "System::Threading::Tasks::WaitAny-metod"
linktitle: "WaitAny"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::WaitAny-metod. Väntar på att någon av de tillhandahållna Task-objekten ska slutföra körning i C++."
type: docs
weight: 2200
url: /sv/cpp/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) method


Väntar på någon av de angivna [Task](../task/)-objekten tills de har slutfört körningen.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | En array av [Task](../task/)-instanser att vänta på. |

### ReturnValue

Indexet för den slutförda uppgiften i tasks-arrayen.

## Se även

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) method


Väntar på någon av de angivna [Task](../task/)-objekten tills de har slutfört körningen.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | En array av [Task](../task/)-instanser att vänta på. |
| cancellationToken | const CancellationToken\& | En [CancellationToken](../../system.threading/cancellationtoken/) att observera medan du väntar på att taskarna ska slutföras. |

### ReturnValue

Indexet för den slutförda uppgiften i tasks-arrayen.

## Se även

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
