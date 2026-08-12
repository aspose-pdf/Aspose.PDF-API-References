---
title: "System::Threading::ThreadPoolImpl-klass"
linktitle: "ThreadPoolImpl"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::ThreadPoolImpl-klass. Trådpools interna data. Detta är en singleton-typ med minneshantering utförd av åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt i C++."
type: docs
weight: 1400
url: /sv/cpp/system.threading/threadpoolimpl/
---
## ThreadPoolImpl class


[Thread](../thread/) pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class ThreadPoolImpl
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Hämtar antalet tillgängliga trådar. |
| static [GetInitialized](./getinitialized/)() | Hämtar initieringsstatus‑singleton. |
| [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Hämtar maximalt antal samtidiga trådar. |
| [GetMinThreads](./getminthreads/)(int\&, int\&) | Hämtar minimalt antal trådar som skapas av poolen. |
| [JoinAll](./joinall/)() | Joinar alla ägda trådar. Väntar oändligt. |
| [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | Lägger till arbetsobjekt i kön. |
| [SetMaxThreads](./setmaxthreads/)(int, int) | Ställer in antalet trådar som ägs av poolen. |
| [SetMinThreads](./setminthreads/)(int, int) | Ställer in minimalt antal trådar som ägs av poolen. |
| [ThreadPoolImpl](./threadpoolimpl/)() | Konstruktor. |
| [~ThreadPoolImpl](./~threadpoolimpl/)() | Destruktor. Joinar alla trådar om de ännu inte har terminerats. |
## Se även

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
