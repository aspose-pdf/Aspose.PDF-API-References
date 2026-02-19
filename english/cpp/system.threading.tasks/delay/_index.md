---
title: System::Threading::Tasks::Delay method
linktitle: Delay
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Delay method. Creates a task that completes after a time delay in C++.'
type: docs
weight: 1000
url: /cpp/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) method


Creates a task that completes after a time delay.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | int32_t | The number of milliseconds to wait before completing the returned task, or -1 to wait indefinitely. |

### ReturnValue

A task that represents the time delay.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) method


Creates a task that completes after a time delay and can be cancelled.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | int32_t | The number of milliseconds to wait before completing the returned task, or -1 to wait indefinitely. |
| cancellationToken | const CancellationToken\& | The cancellation token that can be used to cancel the delay. |

### ReturnValue

A task that represents the time delay.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
