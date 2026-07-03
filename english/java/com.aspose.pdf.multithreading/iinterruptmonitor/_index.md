---
title: IInterruptMonitor
linktitle: IInterruptMonitor
second_title: Aspose.PDF for Java API Reference
description: Represents information about interruption.
type: docs
weight: 20
url: /java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Represents information about interruption.

## Methods

| Method | Description |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource |
| [interrupt](#interrupt--) | Sends a request to interrupt operations. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource

**Returns:**
CancellationTokenSource instance

### interrupt {#interrupt--}
```
void interrupt()
```

Sends a request to interrupt operations.
