---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Multithreading.InterruptMonitor. Rappresenta informazioni sull'interruzione
type: docs
weight: 7000
url: /it/net/aspose.pdf.multithreading/interruptmonitor/
---
## Classe InterruptMonitor

Rappresenta informazioni sull'interruzione.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Token di cancellazione del monitor utilizzato per l'interruzione del processo. Per impostazione predefinita, ogni IInterruptMonitor genera il proprio cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Ottiene o imposta l'istanza di IInterruptMonitor che è unica per ogni thread. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Dispone delle risorse utilizzate. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Invia una richiesta per interrompere le operazioni. |

### Vedi Anche

* interfaccia [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)