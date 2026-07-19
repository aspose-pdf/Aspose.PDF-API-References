---
title: "Метод System::Threading::Tasks::WaitAny"
linktitle: "WaitAny"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::Tasks::WaitAny. Ожидает завершения выполнения любого из предоставленных объектов Task в C++."
type: docs
weight: 2200
url: /ru/cpp/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) method


Ожидает завершения выполнения любого из предоставленных объектов [Task](../task/).

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | Массив экземпляров [Task](../task/), на которых следует ожидать. |

### ReturnValue

Индекс завершённой задачи в массиве задач.

## См. также

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) method


Ожидает завершения выполнения любого из предоставленных объектов [Task](../task/).

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | Массив экземпляров [Task](../task/), на которых следует ожидать. |
| cancellationToken | const CancellationToken\& | Токен [CancellationToken](../../system.threading/cancellationtoken/), наблюдаемый во время ожидания завершения задач. |

### ReturnValue

Индекс завершённой задачи в массиве задач.

## См. также

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
