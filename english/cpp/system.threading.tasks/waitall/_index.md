---
title: System::Threading::Tasks::WaitAll method
linktitle: WaitAll
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::WaitAll method. Waits for all of the provided Task objects to complete execution in C++.'
type: docs
weight: 2000
url: /cpp/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) method


Waits for all of the provided [Task](../task/) objects to complete execution.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | An array of [Task](../task/) instances on which to wait. |

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) method


Waits for all of the provided [Task](../task/) objects to complete execution.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | An array of [Task](../task/) instances on which to wait. |
| cancellationToken | const CancellationToken\& | A [CancellationToken](../../system.threading/cancellationtoken/) to observe while waiting for the tasks to complete. |

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
