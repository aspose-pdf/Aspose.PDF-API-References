---
title: System::Threading::Tasks::Task::ContinueWith method
linktitle: ContinueWith
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Task::ContinueWith method. Creates a continuation that executes when the task completes in C++.'
type: docs
weight: 700
url: /cpp/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith method


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
