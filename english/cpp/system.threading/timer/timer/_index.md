---
title: System::Threading::Timer::Timer constructor
linktitle: Timer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Timer::Timer constructor. Constructor in C++.'
type: docs
weight: 100
url: /cpp/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | TimerCallback | Function to be called by the timer. |

## See Also

* Typedef [TimerCallback](../../timercallback/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | TimerCallback | Function to be called by the timer. |
| state | const System::SharedPtr\<System::Object\>\& | Callback function argument. |
| dueTime | int64_t | [Timeout](../../timeout/) before first invocation of callback function, in milliseconds; negative values doesn't schedule timer after creation so it can be re-scheduled later. |
| period | int64_t | [Timeout](../../timeout/) between consequental invocations of callback function, in milliseconds; non-positive values mean that timer should only be executed once. |

## See Also

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | TimerCallback | Function to be called by the timer. |
| state | const System::SharedPtr\<System::Object\>\& | Callback function argument. |
| dueTime | System::TimeSpan | [Timeout](../../timeout/) before first invocation of callback function; negative values doesn't schedule timer after creation so it can be re-scheduled later. |
| period | System::TimeSpan | [Timeout](../../timeout/) between consequental invocations of callback function; non-positive values mean that timer should only be executed once. |

## See Also

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
