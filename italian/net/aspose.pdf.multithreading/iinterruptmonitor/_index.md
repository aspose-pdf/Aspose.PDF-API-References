---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Interfaccia Aspose.Pdf.Multithreading.IInterruptMonitor. Rappresenta informazioni sull'interruzione
type: docs
weight: 6990
url: /it/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## Interfaccia IInterruptMonitor

Rappresenta informazioni sull'interruzione.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Token di cancellazione del monitor utilizzato per l'interruzione del processo. Per impostazione predefinita, ogni IInterruptMonitor genera il proprio cancellationSource |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Invia una richiesta per interrompere le operazioni. |

### Vedi Anche

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)