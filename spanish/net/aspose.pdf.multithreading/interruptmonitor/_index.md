---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Multithreading.InterruptMonitor. Representa información sobre la interrupción
type: docs
weight: 7000
url: /es/net/aspose.pdf.multithreading/interruptmonitor/
---
## Clase InterruptMonitor

Representa información sobre la interrupción.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Token de cancelación del monitor utilizado para la interrupción del proceso. Por defecto, cada IInterruptMonitor genera su propio cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Obtiene o establece la instancia de IInterruptMonitor que es única para cada hilo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Libera los recursos utilizados. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Envía una solicitud para interrumpir las operaciones. |

### Véase también

* interfaz [IInterruptMonitor](../iinterruptmonitor/)
* espacio de nombres [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* ensamblaje [Aspose.PDF](../../)