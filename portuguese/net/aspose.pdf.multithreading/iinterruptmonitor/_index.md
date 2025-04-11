---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.Multithreading.IInterruptMonitor. Representa informações sobre interrupção
type: docs
weight: 6990
url: /pt/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## Interface IInterruptMonitor

Representa informações sobre interrupção.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Token de cancelamento do monitor usado para interrupção de processo. Por padrão, cada IInterruptMonitor gera seu próprio cancellationSource |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Envia uma solicitação para interromper operações. |

### Veja Também

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)