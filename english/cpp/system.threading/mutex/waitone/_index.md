---
title: System::Threading::Mutex::WaitOne method
linktitle: WaitOne
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Mutex::WaitOne method. Locks mutex. Performs unlimited waiting if neccessary in C++.'
type: docs
weight: 500
url: /cpp/system.threading/mutex/waitone/
---
## Mutex::WaitOne() method


Locks mutex. Performs unlimited waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### ReturnValue

Always returns true as it does not return until mutex is locked.

## See Also

* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Mutex::WaitOne(int) method


Locks mutex. Performs waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Waiting timeout in milliseconds. |

### ReturnValue

Returns true if mutex was locked or false if timeout exceeded.

## See Also

* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Mutex::WaitOne(TimeSpan) method


Locks mutex. Performs waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| timeout | TimeSpan | A [System::TimeSpan](../../../system/timespan/) that represents the number of milliseconds to wait, or a [System::TimeSpan](../../../system/timespan/) that represents -1 milliseconds to wait indefinitely. |

### ReturnValue

Returns true if mutex was locked or false if timeout exceeded.

## See Also

* Class [TimeSpan](../../../system/timespan/)
* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
