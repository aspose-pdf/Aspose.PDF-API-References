---
title: System::Threading::Tasks::Task::ContinueWith method
linktitle: ContinueWith
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Task::ContinueWith method. Creates a continuation that executes when the task completes in C++.'
type: docs
weight: 800
url: /cpp/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) method


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
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


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
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
