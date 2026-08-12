---
title: "System::MakeScopeGuard-metoden"
linktitle: "MakeScopeGuard"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::MakeScopeGuard-metoden. En fabrikfunktion som skapar instanser av ScopedGuard-klassen i C++."
type: docs
weight: 25500
url: /sv/cpp/system/makescopeguard/
---
## System::MakeScopeGuard method


En fabrikfunktion som skapar instanser av ScopedGuard-klassen.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


| Parameter | Beskrivning |
| --- | --- |
| Den | typ av funktionsobjekt som ska anropas av det konstruerade ScopedGuard-objektet |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | F | Funktionsobjektet som ska skickas till ScopedGuard-klassens konstruktor. |

### ReturnValue

En ny instans av ScopedGuard-klassen

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
