---
title: System::Threading::Tasks::Run method
linktitle: Run
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Run method. Queues the specified work to run on the thread pool and returns a Task handle for that work in C++.'
type: docs
weight: 1600
url: /cpp/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) method


Queues the specified work to run on the thread pool and returns a [Task](../task/) handle for that work.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


| Parameter | Type | Description |
| --- | --- | --- |
| action | const Action<>\& | The work to execute asynchronously. |

### ReturnValue

A [Task](../task/) that represents the work queued to execute in the thread pool.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) method


Queues the specified work to run on the thread pool and returns a [Task](../task/) handle for that work.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


| Parameter | Type | Description |
| --- | --- | --- |
| action | const Action<>\& | The work to execute asynchronously. |
| cancellationToken | const CancellationToken\& | A cancellation token that can be used to cancel the work if it has not yet started. |

### ReturnValue

A [Task](../task/) that represents the work queued to execute in the thread pool.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) method


Queues the specified work to run on the thread pool and returns a proxy for the [Task](../task/) returned by the function.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


| Parameter | Type | Description |
| --- | --- | --- |
| function | const Func\<TaskPtr\>\& | The work to execute asynchronously, which returns a [Task](../task/). |

### ReturnValue

A [Task](../task/) that represents a proxy for the [Task](../task/) returned by the function.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Func\<TResult\>\&) method


Queues the specified work to run on the thread pool and returns a [Task<TResult>](../task/) handle for that work.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


| Parameter | Description |
| --- | --- |
| TResult | The type of the result returned by the task. |

| Parameter | Type | Description |
| --- | --- | --- |
| function | const Func\<TResult\>\& | The work to execute asynchronously. |

### ReturnValue

A [Task<TResult>](../task/) that represents the work queued to execute in the thread pool.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
