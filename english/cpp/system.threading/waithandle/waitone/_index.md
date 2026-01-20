---
title: System::Threading::WaitHandle::WaitOne method
linktitle: WaitOne
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::WaitHandle::WaitOne method. Waits for the handle to fire for unlimited period in C++.'
type: docs
weight: 600
url: /cpp/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() method


Waits for the handle to fire for unlimited period.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### ReturnValue

Always returns true as no timeout occurs.

## See Also

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(int) method


Waits for the handle to fire.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) to wait for, in milliseconds; -1 means infinite waiting, 0 means check-and-return, positive values are timeouts. |

### ReturnValue

True if handle fired, false if timeout exceeded.

## See Also

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(int, bool) method


Waits for the handle to fire.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) to wait for, in milliseconds; -1 means infinite waiting, 0 means check-and-return, positive values are timeouts. |
| exitContext | bool | If true, waiting should drop the lock on the handle before waiting for it. |

### ReturnValue

True if handle fired, false if timeout exceeded.

## See Also

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(TimeSpan) method


Waits for the handle to fire.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


| Parameter | Type | Description |
| --- | --- | --- |
| timeout | TimeSpan | A [System::TimeSpan](../../../system/timespan/) that represents the number of milliseconds to wait, or a [System::TimeSpan](../../../system/timespan/) that represents -1 milliseconds to wait indefinitely. |

### ReturnValue

True if handle fired, false if timeout exceeded.

## See Also

* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
