---
title: "Método SetSynchronizationContext de System::Threading::SynchronizationContext"
linktitle: "SetSynchronizationContext"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método SetSynchronizationContext de System::Threading::SynchronizationContext. Establece el contexto de sincronización para el hilo actual en C++."
type: docs
weight: 500
url: /es/cpp/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext method


Establece el contexto de sincronización para el hilo actual.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| syncContext | const SharedPtr\<SynchronizationContext\>\& | El contexto de sincronización que se establecerá para el subproceso actual. |
## Observaciones



Pasar nullptr borrará el contexto de sincronización para el subproceso actual.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
