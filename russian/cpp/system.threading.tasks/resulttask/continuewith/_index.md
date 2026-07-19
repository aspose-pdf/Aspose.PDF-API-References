---
title: "System::Threading::Tasks::ResultTask::ContinueWith метод"
linktitle: "ContinueWith"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::ResultTask::ContinueWith метод. Создаёт продолжение, которое выполняется, когда задача результата завершается в C++."
type: docs
weight: 400
url: /ru/cpp/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method


Создаёт продолжение, которое выполняется при завершении задачи результата.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| continuationAction | const Action\<RTaskPtr\<T\>\>\& | [Action](../../../system/action/) для выполнения, когда эта задача завершается, получая эту задачу результата. |

### ReturnValue

[TaskPtr](../../../system/taskptr/) A new task representing the continuation
## Примечания



Продолжение action получает этот [ResultTask](../) для доступа к значению результата.

## См. также

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method


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
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method


Создаёт продолжение, которое выполняется при завершении задачи результата.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


| Параметр | Описание |
| --- | --- |
| TNewResult | Тип результата продолжения задачи |

| Параметр | Тип | Описание |
| --- | --- | --- |
| continuationFunction | const Func\<RTaskPtr\<T\>, TNewResult\>\& | Функция для получения результата продолжения, когда эта задача завершается, получающая эту задачу результата |

### ReturnValue

[RTaskPtr](../../../system/rtaskptr/) A new task representing the continuation
## Примечания



Функция продолжения получает этот [ResultTask](../) для доступа к значению результата

## См. также

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


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
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
