---
title: System::Threading::Tasks::FromException method
linktitle: FromException
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::FromException method. Creates a task that has completed with a specified exception in C++.'
type: docs
weight: 1300
url: /cpp/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) method


Creates a task that has completed with a specified exception.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


| Parameter | Type | Description |
| --- | --- | --- |
| exception | const Exception\& | The exception with which to complete the task. |

### ReturnValue

A faulted task.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::FromException(const Exception\&) method


Creates a task that has completed with a specified exception and result type.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


| Parameter | Description |
| --- | --- |
| TResult | The type of the task's result. |

| Parameter | Type | Description |
| --- | --- | --- |
| exception | const Exception\& | The exception with which to complete the task. |

### ReturnValue

A faulted task with the specified result type.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [Exception](../../system/exception/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
