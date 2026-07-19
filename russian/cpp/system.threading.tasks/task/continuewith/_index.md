---
title: "System::Threading::Tasks::Task::ContinueWith метод"
linktitle: "ContinueWith"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::Task::ContinueWith метод. Создаёт продолжение, которое выполняется после завершения задачи в C++."
type: docs
weight: 800
url: /ru/cpp/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) method


Создаёт продолжение, которое выполняется при завершении задачи.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| continuationAction | const Action\<TaskPtr\>\& | [Action](../../../system/action/) для выполнения, когда эта задача завершается |

### ReturnValue

[TaskPtr](../../../system/taskptr/) A new task representing the continuation

## См. также

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


Создаёт продолжение, которое выполняется при завершении задачи.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


| Параметр | Описание |
| --- | --- |
| TResult | Тип результата задачи |

| Параметр | Тип | Описание |
| --- | --- | --- |
| continuationFunction | const Func\<TaskPtr, TResult\>\& | Функция для получения результата, когда эта задача завершается |

### ReturnValue

[RTaskPtr](../../../system/rtaskptr/) A new task representing the continuation

## См. также

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Func](../../../system/func/)
* Typedef [TaskPtr](../../../system/taskptr/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
