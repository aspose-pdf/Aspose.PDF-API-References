---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.IInterruptMonitor interface. Represents information about interruption
type: docs
weight: 5350
url: /net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor interface

Represents information about interruption.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource |

## Methods

| Name | Description |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Sends a request to interrupt operations. |

### See Also

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


