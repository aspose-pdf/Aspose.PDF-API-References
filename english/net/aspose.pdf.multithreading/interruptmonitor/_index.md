---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.InterruptMonitor class. Represents information about interruption
type: docs
weight: 5360
url: /net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

Represents information about interruption.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructors

| Name | Description |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Gets or sets the IInterruptMonitor instance which is unique for each thread. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Disposes used resources. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Sends a request to interrupt operations. |

### See Also

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


