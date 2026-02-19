---
title: System::Threading::Tasks::FromCanceled method
linktitle: FromCanceled
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::FromCanceled method. Creates a task that has completed due to cancellation with the specified token in C++.'
type: docs
weight: 1200
url: /cpp/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled method


Creates a task that has completed due to cancellation with the specified token.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```


| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | const CancellationToken\& | The cancellation token that caused the task to be cancelled. |

### ReturnValue

A cancelled task.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
