---
title: System::Threading::CancellationToken::Register method
linktitle: Register
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::CancellationToken::Register method. Registers a callback that will be invoked when cancellation is requested in C++.'
type: docs
weight: 400
url: /cpp/system.threading/cancellationtoken/register/
---
## CancellationToken::Register method


Registers a callback that will be invoked when cancellation is requested.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | const Action<>\& | The [Action<>](../../../system/action/) to execute when cancellation is requested. |

### ReturnValue

A [CancellationTokenRegistration](../../cancellationtokenregistration/) object that can be used to deregister the callback.
## Remarks



If cancellation has already been requested, the callback will be invoked immediately. 

## See Also

* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Typedef [Action](../../../system/action/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
