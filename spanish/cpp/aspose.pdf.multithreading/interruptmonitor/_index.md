---
title: "Aspose::Pdf::Multithreading::InterruptMonitor clase"
linktitle: "InterruptMonitor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Multithreading::InterruptMonitor clase. Representa información sobre interrupción en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class


Representa información sobre interrupción.

```cpp
class InterruptMonitor : public Aspose::Pdf::Multithreading::IInterruptMonitor
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Libera los recursos utilizados. |
| [get_CancellationToken](./get_cancellationtoken/)() override | Token de cancelación del monitor utilizado para la interrupción del proceso. Por defecto, cada [IInterruptMonitor](../iinterruptmonitor/) genera su propio cancellationSource. |
| static [get_ThreadLocalInstance](./get_threadlocalinstance/)() | Obtiene la instancia de [IInterruptMonitor](../iinterruptmonitor/) que es única para cada hilo. |
| [Interrupt](./interrupt/)() override | Envía una solicitud para interrumpir operaciones. |
| [InterruptMonitor](./interruptmonitor/)() | Inicializa una nueva instancia de la clase [InterruptMonitor](./). |
| static [set_ThreadLocalInstance](./set_threadlocalinstance/)(const System::SharedPtr\<IInterruptMonitor\>\&) | Establece la instancia de [IInterruptMonitor](../iinterruptmonitor/) que es única para cada hilo. |
## Ver también

* Class [IInterruptMonitor](../iinterruptmonitor/)
* Namespace [Aspose::Pdf::Multithreading](../)
* Library [Aspose.PDF for C++](../../)
