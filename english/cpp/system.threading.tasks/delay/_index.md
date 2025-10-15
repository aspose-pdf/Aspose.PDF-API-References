---
title: System::Threading::Tasks::Delay method
linktitle: Delay
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Delay method. Creates a task that completes after a time delay in C++.'
type: docs
weight: 700
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




```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
