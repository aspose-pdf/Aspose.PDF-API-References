---
title: System::Timers::Timer class
linktitle: Timer
second_title: Aspose.PDF for C++ API Reference
description: 'System::Timers::Timer class. Timer that calls delegate in a loop in C++.'
type: docs
weight: 200
url: /cpp/system.timers/timer/
---
## Timer class


[Timer](./) that calls delegate in a loop.

```cpp
class Timer : public System::ComponentModel::Component
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() | Stops timer, frees allocated resources. |
| [Dispose](./dispose/)() | Stops timer, frees allocated resources. |
| [get_AutoReset](./get_autoreset/)() const | Checks if timer is in auto-reset mode. |
| [get_Enabled](./get_enabled/)() const | Checks if timer is active. |
| [get_Interval](./get_interval/)() const | Gets timer interval. |
| [get_IsStopped](./get_isstopped/)() const | Checks if timer is stopped. |
| [set_AutoReset](./set_autoreset/)(bool) | Sets timer into auto-reset mode or out of it. |
| [set_Enabled](./set_enabled/)(bool) | Starts or stops timer. Starting timer doesn't restart time counting if timer is already executing. |
| [set_Interval](./set_interval/)(double) | Sets timer interval. |
| [Start](./start/)() | Starts timer. Doesn't restart time counting if timer is already executing. |
| [Stop](./stop/)() | Stops timer. |
| [Timer](./timer/)() | RTTI information. |
| [Timer](./timer/)(double) | Constructs stopped timer with specified interval. |
## See Also

* Class [Component](../../system.componentmodel/component/)
* Namespace [System::Timers](../)
* Library [Aspose.PDF for C++](../../)
