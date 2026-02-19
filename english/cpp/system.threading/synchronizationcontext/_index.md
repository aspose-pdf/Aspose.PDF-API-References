---
title: System::Threading::SynchronizationContext class
linktitle: SynchronizationContext
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::SynchronizationContext class. Provides the basic functionality for propagating a synchronization context across various synchronization operations in C++.'
type: docs
weight: 1100
url: /cpp/system.threading/synchronizationcontext/
---
## SynchronizationContext class


Provides the basic functionality for propagating a synchronization context across various synchronization operations.

```cpp
class SynchronizationContext : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [get_Current](./get_current/)() | Gets the synchronization context for the current thread. |
| virtual [Post](./post/)(SendOrPostCallback, SharedPtr\<Object\>) | Runs callback asynchronously. |
| virtual [Send](./send/)(SendOrPostCallback, SharedPtr\<Object\>) | Runs callback synchronously. |
| static [SetSynchronizationContext](./setsynchronizationcontext/)(const SharedPtr\<SynchronizationContext\>\&) | Sets the synchronization context for the current thread. |
| [SynchronizationContext](./synchronizationcontext/)() | RTTI information. |
## Remarks


This class enables the propagation of synchronization context between threads and is used to marshal callbacks or invocations to the appropriate thread or synchronization context. 
Dummy implementation. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
