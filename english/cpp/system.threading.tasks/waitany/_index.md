---
title: System::Threading::Tasks::WaitAny method
linktitle: WaitAny
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::WaitAny method. Waits for any of the provided Task objects to complete execution in C++.'
type: docs
weight: 2200
url: /cpp/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) method


Waits for any of the provided [Task](../task/) objects to complete execution.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | An array of [Task](../task/) instances on which to wait. |

### ReturnValue

The index of the completed task in the tasks array.

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) method


Waits for any of the provided [Task](../task/) objects to complete execution.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | An array of [Task](../task/) instances on which to wait. |
| cancellationToken | const CancellationToken\& | A [CancellationToken](../../system.threading/cancellationtoken/) to observe while waiting for the tasks to complete. |

### ReturnValue

The index of the completed task in the tasks array.

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
