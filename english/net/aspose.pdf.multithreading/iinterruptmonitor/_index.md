---
title: "IInterruptMonitor Interface"
linktitle: "IInterruptMonitor"
articleTitle: "IInterruptMonitor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Multithreading.IInterruptMonitor interface. Represents information about interruption."
type: docs
weight: 20
url: "/net/aspose.pdf.multithreading/iinterruptmonitor/"
product_version: "26.9.0"
---
## IInterruptMonitor interface

Represents information about interruption.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [CancellationToken](./cancellationtoken/) { get; } | Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource |

## Methods

| Name | Description |
| --- | --- |
| [Interrupt](./interrupt/)() | Sends a request to interrupt operations. |

### See Also

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)

