---
title: System::Threading::CancellationTokenSource class
linktitle: CancellationTokenSource
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::CancellationTokenSource class. A cancellation token source that can be used to trigger cancellation notifications in C++.'
type: docs
weight: 400
url: /cpp/system.threading/cancellationtokensource/
---
## CancellationTokenSource class


A cancellation token source that can be used to trigger cancellation notifications.

```cpp
class CancellationTokenSource : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Cancel](./cancel/)() | Communicates a request for cancellation. |
| [CancellationTokenSource](./cancellationtokensource/)() | Constructs a new [CancellationTokenSource](./). |
| static [CreateLinkedTokenSource](./createlinkedtokensource/)(const CancellationToken\&, const CancellationToken\&) | Creates a linked token source that cancels when any of the provided tokens cancel. |
| [Dispose](./dispose/)() override | Releases all resources used by the [CancellationTokenSource](./). |
| [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Gets whether cancellation has been requested. |
| [get_Token](./get_token/)() const | Gets the cancellation token associated with this source. |
## Remarks


Provides mechanisms to create and control cancellation tokens for cooperative cancellation of operations. 
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
