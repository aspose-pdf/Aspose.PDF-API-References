---
title: InterruptMonitor
linktitle: InterruptMonitor
second_title: Aspose.PDF for Java API Reference
description: Represents information about interruption.
type: docs
weight: 40
url: /java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Represents information about interruption.

## Constructors

| Constructor | Description |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Initializes a new instance of the {@link InterruptMonitor} class. |

## Methods

| Method | Description |
| --- | --- |
| [dispose](#dispose--) | Disposes used resources. |
| [getCancellationToken](#getCancellationToken--) | Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Gets or sets the IInterruptMonitor instance which is unique for each thread. |
| [interrupt](#interrupt--) | Sends a request to interrupt operations. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Gets or sets the IInterruptMonitor instance which is unique for each thread. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Initializes a new instance of the {@link InterruptMonitor} class.

### dispose {#dispose--}
```
public final void dispose()
```

Disposes used resources.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource.

**Returns:**
CancellationTokenSource instance

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Gets or sets the IInterruptMonitor instance which is unique for each thread.

**Returns:**
IInterruptMonitor instance

### interrupt {#interrupt--}
```
public void interrupt()
```

Sends a request to interrupt operations.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Gets or sets the IInterruptMonitor instance which is unique for each thread.
