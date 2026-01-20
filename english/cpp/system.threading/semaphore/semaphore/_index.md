---
title: System::Threading::Semaphore::Semaphore constructor
linktitle: Semaphore
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Semaphore::Semaphore constructor. RTTI information in C++.'
type: docs
weight: 100
url: /cpp/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) constructor


RTTI information.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


| Parameter | Type | Description |
| --- | --- | --- |
| initialCount | int | Initial count of active entries. |
| maximumCount | int | Maximum allwed entries count. |
## Remarks


Creates unnamed semaphore. 
## See Also

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Semaphore::Semaphore(int, int, const String\&) constructor


Creates named semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| initialCount | int | Initial count of active entries. |
| maximumCount | int | Maximum allwed entries count. |
| name | const String\& | [Semaphore](../) name. |

## See Also

* Class [String](../../../system/string/)
* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Semaphore::Semaphore(int, int, const String\&, bool\&) constructor


Creates named semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


| Parameter | Type | Description |
| --- | --- | --- |
| initialCount | int | Initial count of active entries. |
| maximumCount | int | Maximum allwed entries count. |
| name | const String\& | [Semaphore](../) name. |
| createdNew | bool\& | Reference to variable which is set to true if semaphore was created and to false if existing one with same name was reused |

## See Also

* Class [String](../../../system/string/)
* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
