---
title: System::Threading::Tasks::ResultTask::ContinueWith method
linktitle: ContinueWith
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultTask::ContinueWith method. Creates a continuation that executes when the result task completes in C++.'
type: docs
weight: 400
url: /cpp/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method


Creates a continuation that executes when the result task completes.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const Action\<RTaskPtr\<T\>\>\& | [Action](../../../system/action/) to execute when this task completes, receiving this result task |

### ReturnValue

[TaskPtr](../../../system/taskptr/) A new task representing the continuation
## Remarks



The continuation action receives this [ResultTask](../) to access the result value 

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method


Creates a continuation that executes when the task completes.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const Action\<TaskPtr\>\& | [Action](../../../system/action/) to execute when this task completes |

### ReturnValue

[TaskPtr](../../../system/taskptr/) A new task representing the continuation

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method


Creates a continuation that executes when the result task completes.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


| Parameter | Description |
| --- | --- |
| TNewResult | Result type of task continuation |

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const Func\<RTaskPtr\<T\>, TNewResult\>\& | Function to get continuation result when this task completes, receiving this result task |

### ReturnValue

[RTaskPtr](../../../system/rtaskptr/) A new task representing the continuation
## Remarks



The continuation function receives this [ResultTask](../) to access the result value 

## See Also

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


Creates a continuation that executes when the task completes.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


| Parameter | Description |
| --- | --- |
| TResult | A type of task result |

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const Func\<TaskPtr, TResult\>\& | Function to get result when this task completes |

### ReturnValue

[RTaskPtr](../../../system/rtaskptr/) A new task representing the continuation

## See Also

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Func](../../../system/func/)
* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
