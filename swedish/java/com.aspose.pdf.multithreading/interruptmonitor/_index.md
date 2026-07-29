---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar information om avbrott."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Representerar information om avbrott.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Initierar en ny instans av {@link InterruptMonitor}-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [dispose](#dispose--) | Frigir använda resurser. |
| [getCancellationToken](#getCancellationToken--) | Monitorns avbokningstoken som används för processavbrott. Som standard genererar varje IInterruptMonitor sin egen cancellationSource. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Hämtar eller anger IInterruptMonitor‑instansen som är unik för varje tråd. |
| [interrupt](#interrupt--) | Skickar en begäran om att avbryta operationer. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Hämtar eller anger IInterruptMonitor‑instansen som är unik för varje tråd. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Initierar en ny instans av {@link InterruptMonitor}-klassen.

### dispose {#dispose--}
```
public final void dispose()
```

Frigir använda resurser.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Monitorns avbokningstoken som används för processavbrott. Som standard genererar varje IInterruptMonitor sin egen cancellationSource.

**Returns:**
CancellationTokenSource‑instans

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Hämtar eller anger IInterruptMonitor‑instansen som är unik för varje tråd.

**Returns:**
IInterruptMonitor‑instans

### interrupt {#interrupt--}
```
public void interrupt()
```

Skickar en begäran om att avbryta operationer.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Hämtar eller anger IInterruptMonitor‑instansen som är unik för varje tråd.
