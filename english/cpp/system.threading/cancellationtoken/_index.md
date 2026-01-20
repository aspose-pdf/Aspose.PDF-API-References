---
title: System::Threading::CancellationToken class
linktitle: CancellationToken
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::CancellationToken class. Propagates notification that operations should be canceled. This class provides a mechanism for cooperative cancellation between threads, allowing one thread to notify others that an operation should be canceled in C++.'
type: docs
weight: 200
url: /cpp/system.threading/cancellationtoken/
---
## CancellationToken class


Propagates notification that operations should be canceled. This class provides a mechanism for cooperative cancellation between threads, allowing one thread to notify others that an operation should be canceled.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| [CancellationToken](./cancellationtoken/)() | Default constructor. |
| [get_CanBeCanceled](./get_canbecanceled/)() const | Gets whether this token is capable of being in the canceled state. |
| [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Gets whether cancellation has been requested for this token. |
| static [get_None](./get_none/)() | Returns an empty [System::Threading::CancellationToken](./) value. |
| [Register](./register/)(const Action<>\&) const | Registers a callback that will be invoked when cancellation is requested. |
| [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Throws a OperationCanceledException if cancellation has been requested. |
## Remarks



A [CancellationToken](./) can only be canceled through its associated [CancellationTokenSource](../cancellationtokensource/). 

## See Also

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
