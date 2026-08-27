---
title: "Classe InterruptMonitor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Multithreading.InterruptMonitor. Rappresenta le informazioni sull'interruzione."
type: docs
weight: 7140
url: /it/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

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
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Token di cancellazione del monitor utilizzato per l'interruzione del processo. Per impostazione predefinita ogni IInterruptMonitor genera la propria cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Ottiene o imposta l'istanza IInterruptMonitor che è unica per ogni thread. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Rilascia le risorse utilizzate. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Invia una richiesta per interrompere le operazioni. |

### Vedi anche

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


