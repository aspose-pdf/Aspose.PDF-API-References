---
title: "Aspose::Pdf::Multithreading::IInterruptMonitor clase"
linktitle: "IInterruptMonitor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Multithreading::IInterruptMonitor clase. Representa información sobre interrupción en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor class


Representa información sobre interrupción.

```cpp
class IInterruptMonitor : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_CancellationToken](./get_cancellationtoken/)() | Token de cancelación del monitor utilizado para la interrupción del proceso. Por defecto, cada [IInterruptMonitor](./) genera su propio cancellationSource. |
| virtual [Interrupt](./interrupt/)() | Envía una solicitud para interrumpir operaciones. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Multithreading](../)
* Library [Aspose.PDF for C++](../../)
