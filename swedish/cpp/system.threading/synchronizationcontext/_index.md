---
title: "System::Threading::SynchronizationContext klass"
linktitle: "SynchronizationContext"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::SynchronizationContext klass. Tillhandahåller grundläggande funktionalitet för att sprida ett synkroniseringssammanhang över olika synkroniseringsoperationer i C++."
type: docs
weight: 1100
url: /sv/cpp/system.threading/synchronizationcontext/
---
## SynchronizationContext class


Tillhandahåller grundläggande funktionalitet för att sprida ett synkroniseringssammanhang över olika synkroniseringsoperationer.

```cpp
class SynchronizationContext : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [get_Current](./get_current/)() | Hämtar synkroniseringssammanhanget för den aktuella tråden. |
| virtual [Post](./post/)(SendOrPostCallback, SharedPtr\<Object\>) | Kör återanropet asynkront. |
| virtual [Send](./send/)(SendOrPostCallback, SharedPtr\<Object\>) | Kör återanropet synkront. |
| static [SetSynchronizationContext](./setsynchronizationcontext/)(const SharedPtr\<SynchronizationContext\>\&) | Ställer in synkroniseringssammanhanget för den aktuella tråden. |
| [SynchronizationContext](./synchronizationcontext/)() | RTTI-information. |
## Anmärkningar


Denna klass möjliggör spridning av synkroniseringssammanhang mellan trådar och används för att vidarebefordra återanrop eller anrop till rätt tråd eller synkroniseringssammanhang.
Dummy-implementation.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
