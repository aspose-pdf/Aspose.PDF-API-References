---
title: System::Threading::Timer::Change method
linktitle: Change
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Timer::Change method. Re-schedules or cancels timer in C++.'
type: docs
weight: 200
url: /cpp/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) method


Re-schedules or cancels timer.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


| Parameter | Type | Description |
| --- | --- | --- |
| dueTime | int64_t | [Timeout](../../timeout/) before next invocation of callback function, in milliseconds; negative values cancel timer even if it was scheduled. |
| period | int64_t | [Timeout](../../timeout/) between consequental invocations of callback function, in milliseconds; non-positive values mean that timer should only be executed once. |

## See Also

* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Change(System::TimeSpan, System::TimeSpan) method


Re-schedules or cancels timer.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


| Parameter | Type | Description |
| --- | --- | --- |
| dueTime | System::TimeSpan | [Timeout](../../timeout/) before next invocation of callback function; negative values cancel timer even if it was scheduled. |
| period | System::TimeSpan | [Timeout](../../timeout/) between consequental invocations of callback function; non-positive values mean that timer should only be executed once. |

## See Also

* Class [TimeSpan](../../../system/timespan/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
