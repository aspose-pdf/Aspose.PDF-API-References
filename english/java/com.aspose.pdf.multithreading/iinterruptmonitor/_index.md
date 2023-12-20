---
title: IInterruptMonitor
second_title: Aspose.PDF for Java API Reference
description: Represents information about interruption.
type: docs
weight: 13
url: /java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IInterruptMonitor extends System.IDisposable
```

Represents information about interruption.
## Methods

| Method | Description |
| --- | --- |
| [getCancellationToken()](#getCancellationToken--) | Monitor's cancellation token used for process interruption. |
| [interrupt()](#interrupt--) | Sends a request to interrupt operations. |
### getCancellationToken() {#getCancellationToken--}
```
public abstract CancellationTokenSource getCancellationToken()
```


Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource

**Returns:**
[CancellationTokenSource](../../com.aspose.pdf.multithreading/cancellationtokensource) - CancellationTokenSource instance
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Sends a request to interrupt operations.

