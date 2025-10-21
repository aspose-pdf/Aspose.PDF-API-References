---
title: System::Threading::SynchronizationContext::SetSynchronizationContext method
linktitle: SetSynchronizationContext
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::SynchronizationContext::SetSynchronizationContext method. Sets the synchronization context for the current thread in C++.'
type: docs
weight: 300
url: /cpp/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext method


Sets the synchronization context for the current thread.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


| Parameter | Type | Description |
| --- | --- | --- |
| syncContext | const SharedPtr\<SynchronizationContext\>\& | The synchronization context to set for the current thread. |
## Remarks



Passing nullptr will clear the synchronization context for the current thread. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
