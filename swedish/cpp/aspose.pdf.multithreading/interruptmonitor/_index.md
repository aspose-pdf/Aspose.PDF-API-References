---
title: "Aspose::Pdf::Multithreading::InterruptMonitor klass"
linktitle: "InterruptMonitor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Multithreading::InterruptMonitor klass. Representerar information om avbrott i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class


Representerar information om avbrott.

```cpp
class InterruptMonitor : public Aspose::Pdf::Multithreading::IInterruptMonitor
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() override | Rensar använda resurser. |
| [get_CancellationToken](./get_cancellationtoken/)() override | Monitorns avbokningstoken används för processavbrott. Som standard genererar varje [IInterruptMonitor](../iinterruptmonitor/) sin egen cancellationSource. |
| static [get_ThreadLocalInstance](./get_threadlocalinstance/)() | Hämtar [IInterruptMonitor](../iinterruptmonitor/) instansen som är unik för varje tråd. |
| [Interrupt](./interrupt/)() override | Skickar en begäran om att avbryta operationer. |
| [InterruptMonitor](./interruptmonitor/)() | Initierar en ny instans av [InterruptMonitor](./) klass. |
| static [set_ThreadLocalInstance](./set_threadlocalinstance/)(const System::SharedPtr\<IInterruptMonitor\>\&) | Ställer in [IInterruptMonitor](../iinterruptmonitor/) instansen som är unik för varje tråd. |
## Se även

* Class [IInterruptMonitor](../iinterruptmonitor/)
* Namespace [Aspose::Pdf::Multithreading](../)
* Library [Aspose.PDF for C++](../../)
