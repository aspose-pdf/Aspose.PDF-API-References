---
title: "System::DoTryFinally‑metod"
linktitle: "DoTryFinally"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DoTryFinally‑metod. Den enda funktionen som efterliknar beteendet hos C#''s try[-catch]-finally‑sats. Vid översättning av C#''s try[-catch]-finally‑sats med översättarens alternativ finally_statement_as_lambda satt till true, översätts satsen till ett anrop av denna metod i C++."
type: docs
weight: 17000
url: /sv/cpp/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) method


Den enda funktionen som efterliknar beteendet hos C#'s try[-catch]-finally‑sats. Vid översättning av C#'s try[-catch]-finally‑sats med översättarens alternativ finally_statement_as_lambda satt till true, översätts satsen till ett anrop av denna metod.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjektet som implementerar try[-catch]-delen av den try[-catch]-finally‑sats som emuleras |
| F | Typen av funktionsobjektet som implementerar finally‑delen av den try[-catch]-finally‑sats som emuleras |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryBlock | T\&& | Funktionsobjektet vars kropp innehåller implementeringen av try[-catch]-delen av den try[-catch]-finally‑stamet som emuleras |
| finallyBlock | F\\&& | Funktionsobjektet vars kropp innehåller implementeringen av finally-delen av try[-catch]-finally‑satsen som emuleras |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DoTryFinally(T\&&, F\&&) method


Den enda funktionen som emulerar beteendet hos C#'s try[-catch]-finally‑sats. Vid översättning av C#'s try[-catch]-finally‑sats med översättarens alternativ finally_statement_as_lambda satt till true, översätts satsen till ett anrop av denna metod. Detta överlagrade alternativ hanterar fallet där returvärdet för funktionsobjektet som implementerar try[-catch]-delen av try[-catch]-finally‑satsen är bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjektet som implementerar try[-catch]-delen av den try[-catch]-finally‑sats som emuleras |
| F | Typen av funktionsobjektet som implementerar finally‑delen av den try[-catch]-finally‑sats som emuleras |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryBlock | T\&& | Funktionsobjektet vars kropp innehåller implementeringen av try[-catch]-delen av den try[-catch]-finally‑stamet som emuleras |
| finallyBlock | F\\&& | Funktionsobjektet vars kropp innehåller implementeringen av finally-delen av try[-catch]-finally‑satsen som emuleras |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DoTryFinally(T\&&, F\&&) method


Den enda funktionen som emulerar beteendet hos C#'s try[-catch]-finally‑sats. Vid översättning av C#'s try[-catch]-finally‑sats med översättarens alternativ finally_statement_as_lambda satt till true, översätts satsen till ett anrop av denna metod. Detta överlagrade alternativ hanterar fallet där returvärdet för funktionsobjektet som implementerar try[-catch]-delen av try[-catch]-finally‑satsen är bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjektet som implementerar try[-catch]-delen av den try[-catch]-finally‑sats som emuleras |
| F | Typen av funktionsobjektet som implementerar finally‑delen av den try[-catch]-finally‑sats som emuleras |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryBlock | T\&& | Funktionsobjektet vars kropp innehåller implementeringen av try[-catch]-delen av den try[-catch]-finally‑stamet som emuleras |
| finallyBlock | F\\&& | Funktionsobjektet vars kropp innehåller implementeringen av finally-delen av try[-catch]-finally‑satsen som emuleras |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
