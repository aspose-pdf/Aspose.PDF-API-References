---
title: System::Threading::Tasks::WhenAll method
linktitle: WhenAll
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::WhenAll method. Creates a task that will complete when all of the supplied tasks have completed in C++.'
type: docs
weight: 2400
url: /cpp/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) method


Creates a task that will complete when all of the supplied tasks have completed.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


| Parameter | Description |
| --- | --- |
| TResult | The type of the completed tasks' results. |

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const ArrayPtr\<RTaskPtr\<TResult\>\>\& | The tasks to wait on for completion. |

### ReturnValue

A task that returns an array of all the results when all tasks complete.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) method


Creates a task that will complete when all of the supplied tasks have completed.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | The tasks to wait on for completion. |

### ReturnValue

A task that represents the completion of all of the supplied tasks.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) method


Creates a task that will complete when all of the supplied tasks have completed.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


| Parameter | Description |
| --- | --- |
| TResult | The type of the completed tasks' results. |

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\& | The tasks to wait on for completion. |

### ReturnValue

A task that returns an array of all the results when all tasks complete.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) method


Creates a task that will complete when all of the supplied tasks have completed.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\& | The tasks to wait on for completion. |

### ReturnValue

A task that represents the completion of all of the supplied tasks.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
