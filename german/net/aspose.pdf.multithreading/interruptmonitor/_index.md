---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.InterruptMonitor-Klasse. Stellt Informationen über Unterbrechungen dar
type: docs
weight: 7000
url: /de/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor-Klasse

Stellt Informationen über Unterbrechungen dar.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Der Abbruchtoken des Monitors, der für die Unterbrechung des Prozesses verwendet wird. Standardmäßig erzeugt jeder IInterruptMonitor seine eigene cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Ruft die IInterruptMonitor-Instanz ab oder setzt sie, die für jeden Thread einzigartig ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Gibt verwendete Ressourcen frei. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Sendet eine Anfrage zur Unterbrechung von Operationen. |

### Siehe auch

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)