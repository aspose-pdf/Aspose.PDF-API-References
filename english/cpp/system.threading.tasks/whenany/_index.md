---
title: System::Threading::Tasks::WhenAny method
linktitle: WhenAny
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::WhenAny method. Creates a task that will complete when any of the supplied tasks have completed in C++.'
type: docs
weight: 2800
url: /cpp/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) method


Creates a task that will complete when any of the supplied tasks have completed.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


| Parameter | Description |
| --- | --- |
| TResult | The type of the completed task's result. |

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const ArrayPtr\<RTaskPtr\<TResult\>\>\& | The tasks to wait on for completion. |

### ReturnValue

A task that returns the first completed task when any task completes.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) method


Creates a task that will complete when any of the supplied tasks have completed.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | The tasks to wait on for completion. |

### ReturnValue

A task that represents the completion of one of the supplied tasks.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) method


Creates a task that will complete when any of the supplied tasks have completed.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


| Parameter | Description |
| --- | --- |
| TResult | The type of the completed task's result. |

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\& | The tasks to wait on for completion. |

### ReturnValue

A task that returns the first completed task when any task completes.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) method


Creates a task that will complete when any of the supplied tasks have completed.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\& | The tasks to wait on for completion. |

### ReturnValue

A task that represents the completion of one of the supplied tasks.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
