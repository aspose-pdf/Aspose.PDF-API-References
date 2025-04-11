---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.IInterruptMonitor-Schnittstelle. Stellt Informationen über Unterbrechungen dar
type: docs
weight: 6990
url: /de/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor-Schnittstelle

Stellt Informationen über Unterbrechungen dar.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Abbruchtoken des Monitors, das zur Unterbrechung von Prozessen verwendet wird. Standardmäßig erzeugt jede IInterruptMonitor ihre eigene cancellationSource |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Sendet eine Anfrage zur Unterbrechung von Operationen. |

### Siehe auch

* Namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* Assembly [Aspose.PDF](../../)