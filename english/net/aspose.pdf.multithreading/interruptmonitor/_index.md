---
title: "InterruptMonitor Class"
linktitle: "InterruptMonitor"
articleTitle: "InterruptMonitor"
second_title: "Aspose.PDF for .NET"
description: "Represents information about interruption."
type: docs
weight: 30
url: "/net/aspose.pdf.multithreading/interruptmonitor/"
keywords: "InterruptMonitor, Aspose.Pdf.Multithreading, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## InterruptMonitor class

Represents information about interruption.

```csharp
public class InterruptMonitor : IInterruptMonitor, IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [InterruptMonitor](./interruptmonitor/#constructor) | Initializes a new instance of the InterruptMonitor class. |

## Properties

| Name | Description |
| --- | --- |
| [CancellationToken](./cancellationtoken/) { get; } | Monitor's cancellation token used for process interruption. |
| [ThreadLocalInstance](./threadlocalinstance/) { get; set; } | Gets or sets the IInterruptMonitor instance which is unique for each thread. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](./dispose/) | Disposes used resources. |
| [Interrupt](./interrupt/) | Sends a request to interrupt operations. |

### See Also

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)

