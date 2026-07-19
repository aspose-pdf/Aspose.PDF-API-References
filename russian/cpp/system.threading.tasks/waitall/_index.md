---
title: "Метод System::Threading::Tasks::WaitAll"
linktitle: "WaitAll"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::Tasks::WaitAll. Ожидает завершения выполнения всех предоставленных объектов Task в C++."
type: docs
weight: 2000
url: /ru/cpp/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) method


Ожидает завершения выполнения всех предоставленных объектов [Task](../task/).

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | Массив экземпляров [Task](../task/), на которых следует ожидать. |

## См. также

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) method


Ожидает завершения выполнения всех предоставленных объектов [Task](../task/).

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | Массив экземпляров [Task](../task/), на которых следует ожидать. |
| cancellationToken | const CancellationToken\& | Токен [CancellationToken](../../system.threading/cancellationtoken/), наблюдаемый во время ожидания завершения задач. |

## См. также

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
