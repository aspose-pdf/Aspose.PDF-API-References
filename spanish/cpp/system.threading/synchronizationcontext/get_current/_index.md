---
title: "System::Threading::SynchronizationContext::get_Current método"
linktitle: "get_Current"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::SynchronizationContext::get_Current método. Obtiene el contexto de sincronización para el subproceso actual en C++."
type: docs
weight: 400
url: /es/cpp/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current method


Obtiene el contexto de sincronización para el hilo actual.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### ReturnValue

[SharedPtr<SynchronizationContext>](../../../system/sharedptr/) A shared pointer to the current thread's synchronization context.
## Observaciones



Devuelve null si no se ha establecido ningún contexto de sincronización para el subproceso actual.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
