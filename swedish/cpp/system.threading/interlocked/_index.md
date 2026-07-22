---
title: "System::Threading::Interlocked klass"
linktitle: "Interlocked"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Interlocked-klass. Tillhandahåller API för trådsäkra operationer. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 600
url: /sv/cpp/system.threading/interlocked/
---
## Interlocked class


Tillhandahåller API för trådsäkra operationer. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Interlocked
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Add](./add/)(int32_t\&, int32_t) | Ökar värdet atomärt. |
| static [Add](./add/)(int64_t\&, int64_t) | Ökar värdet atomärt. |
| static [CompareExchange](./compareexchange/)(T\&, T, T) | Jämför-och-utbyter värde på variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade. |
| static [CompareExchange](./compareexchange/)(T\&, T, T) | Jämför-och-utbyter värde på variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade. Inte implementerad. |
| static [CompareExchange](./compareexchange/)(int32_t\&, int32_t, int32_t, bool\&) | Jämför-och-utbyter värde på variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade. |
| static [Decrement](./decrement/)(int32_t\&) | Minskar värdet atomärt. |
| static [Decrement](./decrement/)(int64_t\&) | Minskar värdet atomärt. |
| static [Exchange](./exchange/)(T\&, T) | Byter värde på variabel: lagrar det nya värdet och returnerar det värde variabeln hade omedelbart innan lagringen. |
| static [Exchange](./exchange/)(T\&, T) | Byter värde på variabel: lagrar det nya värdet och returnerar det värde variabeln hade omedelbart innan lagringen. Inte implementerad. |
| static [ExchangeAdd](./exchangeadd/)(int32_t\&, int32_t) | Ökar värdet atomärt via exchange-add‑procedur. |
| static [ExchangeAdd](./exchangeadd/)(int64_t\&, int64_t) | Ökar värdet atomärt via exchange-add‑procedur. |
| static [Increment](./increment/)(int32_t\&) | Ökar värdet atomärt. |
| static [Increment](./increment/)(int64_t\&) | Ökar värdet atomärt. |
| static [Read](./read/)(int64_t\&) | Returnerar ett 64‑bitars värde, laddat som en atomär operation. |
## Se även

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
