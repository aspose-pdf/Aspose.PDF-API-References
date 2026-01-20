---
title: System::Threading::Tasks::ResultTask::ContinueWith method
linktitle: ContinueWith
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultTask::ContinueWith method. Creates a continuation that executes when the result task completes in C++.'
type: docs
weight: 300
url: /cpp/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith method


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
