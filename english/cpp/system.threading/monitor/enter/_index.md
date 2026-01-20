---
title: System::Threading::Monitor::Enter method
linktitle: Enter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Monitor::Enter method. Acquires an exclusive lock on a specified object in C++.'
type: docs
weight: 100
url: /cpp/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) method


Acquires an exclusive lock on a specified object.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SharedPtr\<Object\>\& | The object on which to acquire the monitor lock. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) method


Acquires an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
