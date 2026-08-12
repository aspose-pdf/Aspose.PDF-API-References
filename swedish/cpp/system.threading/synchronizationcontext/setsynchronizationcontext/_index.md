---
title: "System::Threading::SynchronizationContext::SetSynchronizationContext metod"
linktitle: "SetSynchronizationContext"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::SynchronizationContext::SetSynchronizationContext metod. Ställer in synkroniseringskontexten för den aktuella tråden i C++."
type: docs
weight: 500
url: /sv/cpp/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext method


Ställer in synkroniseringssammanhanget för den aktuella tråden.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| syncContext | const SharedPtr\<SynchronizationContext\>\& | Den synkroniseringskontext som ska ställas in för den aktuella tråden. |
## Anmärkningar



Att skicka nullptr kommer att rensa synkroniseringskontexten för den aktuella tråden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
