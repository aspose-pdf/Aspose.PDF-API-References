---
title: InterruptMonitor
second_title: Aspose.PDF for Java API Reference
description: Represents information about interruption.
type: docs
weight: 12
url: /java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.multithreading.IInterruptMonitor](../../com.aspose.pdf.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Represents information about interruption.
## Constructors

| Constructor | Description |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initializes a new instance of the [InterruptMonitor](../../com.aspose.pdf.multithreading/interruptmonitor) class. |
## Methods

| Method | Description |
| --- | --- |
| [getCancellationToken()](#getCancellationToken--) | Monitor's cancellation token used for process interruption. |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Gets or sets the IInterruptMonitor instance which is unique for each thread. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Gets or sets the IInterruptMonitor instance which is unique for each thread. |
| [interrupt()](#interrupt--) | Sends a request to interrupt operations. |
| [dispose()](#dispose--) | Disposes used resources. |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initializes a new instance of the [InterruptMonitor](../../com.aspose.pdf.multithreading/interruptmonitor) class.

### getCancellationToken() {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```


Monitor's cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource.

**Returns:**
[CancellationTokenSource](../../com.aspose.pdf.multithreading/cancellationtokensource)
### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Gets or sets the IInterruptMonitor instance which is unique for each thread.

**Returns:**
[IInterruptMonitor](../../com.aspose.pdf.multithreading/iinterruptmonitor) - IInterruptMonitor instance
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Gets or sets the IInterruptMonitor instance which is unique for each thread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.pdf.multithreading/iinterruptmonitor) | IInterruptMonitor instance |

### interrupt() {#interrupt--}
```
public void interrupt()
```


Sends a request to interrupt operations.

### dispose() {#dispose--}
```
public final void dispose()
```


Disposes used resources.

