---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Interfaz Aspose.Pdf.Multithreading.IInterruptMonitor. Representa información sobre interrupción
type: docs
weight: 6990
url: /es/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## Interfaz IInterruptMonitor

Representa información sobre interrupción.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Token de cancelación del monitor utilizado para la interrupción del proceso. Por defecto, cada IInterruptMonitor genera su propio cancellationSource |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Envía una solicitud para interrumpir operaciones. |

### Véase también

* espacio de nombres [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* ensamblado [Aspose.PDF](../../)