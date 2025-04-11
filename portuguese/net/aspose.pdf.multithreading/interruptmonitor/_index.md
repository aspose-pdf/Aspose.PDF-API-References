---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Multithreading.InterruptMonitor. Representa informações sobre interrupção
type: docs
weight: 7000
url: /pt/net/aspose.pdf.multithreading/interruptmonitor/
---
## Classe InterruptMonitor

Representa informações sobre interrupção.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Token de cancelamento do monitor usado para interrupção de processo. Por padrão, cada IInterruptMonitor gera seu próprio cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Obtém ou define a instância de IInterruptMonitor que é única para cada thread. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Descarte os recursos utilizados. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Envia um pedido para interromper operações. |

### Veja Também

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)