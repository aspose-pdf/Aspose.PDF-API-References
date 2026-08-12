---
title: "System::Timers::Timer-klass"
linktitle: "Timer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Timers::Timer-klass. Timer som anropar delegat i en slinga i C++."
type: docs
weight: 200
url: /sv/cpp/system.timers/timer/
---
## Timer class


[Timer](./) that calls delegate in a loop.

```cpp
class Timer : public System::ComponentModel::Component
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() | Stoppar timer, frigör allokerade resurser. |
| [Dispose](./dispose/)() | Stoppar timer, frigör allokerade resurser. |
| [get_AutoReset](./get_autoreset/)() const | Kontrollerar om timern är i autoåterställningsläge. |
| [get_Enabled](./get_enabled/)() const | Kontrollerar om timern är aktiv. |
| [get_Interval](./get_interval/)() const | Hämtar timerintervall. |
| [get_IsStopped](./get_isstopped/)() const | Kontrollerar om timern är stoppad. |
| [set_AutoReset](./set_autoreset/)(bool) | Ställer in timern i autoåterställningsläge eller ur det. |
| [set_Enabled](./set_enabled/)(bool) | Startar eller stoppar timern. Att starta timern återställer inte tidsräkningen om timern redan körs. |
| [set_Interval](./set_interval/)(double) | Ställer in timerintervall. |
| [Start](./start/)() | Startar timern. Återställer inte tidsräkningen om timern redan körs. |
| [Stop](./stop/)() | Stoppar timern. |
| [Timer](./timer/)() | RTTI-information. |
| [Timer](./timer/)(double) | Skapar en stoppad timer med angivet intervall. |
## Se även

* Class [Component](../../system.componentmodel/component/)
* Namespace [System::Timers](../)
* Library [Aspose.PDF for C++](../../)
