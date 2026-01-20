---
title: System::Threading::CancellationTokenRegistration class
linktitle: CancellationTokenRegistration
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::CancellationTokenRegistration class. Represents a registration for a cancellation token callback in C++.'
type: docs
weight: 300
url: /cpp/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration class


Represents a registration for a cancellation token callback.

```cpp
class CancellationTokenRegistration
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() | Disposes the registration and removes the callback from the associated [CancellationTokenSource](../cancellationtokensource/). After calling this method, the registered callback will no longer be invoked when the associated [CancellationTokenSource](../cancellationtokensource/) is canceled. |
## Remarks


This class allows for the deregistration of a callback from a cancellation token. When disposed, it removes the callback from the associated [CancellationTokenSource](../cancellationtokensource/). 
This class should not be created directly - it is returned by [CancellationToken](../cancellationtoken/) registration methods. 

## See Also

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
