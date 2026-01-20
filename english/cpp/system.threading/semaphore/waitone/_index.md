---
title: System::Threading::Semaphore::WaitOne method
linktitle: WaitOne
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Semaphore::WaitOne method. Locks semaphore. Performs unlimited waiting if neccessary in C++.'
type: docs
weight: 500
url: /cpp/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() method


Locks semaphore. Performs unlimited waiting if neccessary.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### ReturnValue

Always returns true as it does not return until semaphore is locked.

## See Also

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Semaphore::WaitOne(int) method


Locks semaphore. Performs waiting if neccessary.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Waiting timeout in milliseconds. |

### ReturnValue

Returns true if semaphore was locked or false if timeout exceeded.

## See Also

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
