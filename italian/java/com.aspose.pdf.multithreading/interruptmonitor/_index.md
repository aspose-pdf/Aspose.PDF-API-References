---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta informazioni sull'interruzione."
type: docs
weight: 40
url: /it/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Rappresenta informazioni sull'interruzione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Inizializza una nuova istanza della classe {@link InterruptMonitor}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [dispose](#dispose--) | Rilascia le risorse utilizzate. |
| [getCancellationToken](#getCancellationToken--) | Token di cancellazione del monitor utilizzato per l'interruzione del processo. Per impostazione predefinita ogni IInterruptMonitor genera la propria cancellationSource. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Ottiene o imposta l'istanza IInterruptMonitor, che è unica per ogni thread. |
| [interrupt](#interrupt--) | Invia una richiesta per interrompere le operazioni. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Ottiene o imposta l'istanza IInterruptMonitor, che è unica per ogni thread. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Inizializza una nuova istanza della classe {@link InterruptMonitor}.

### dispose {#dispose--}
```
public final void dispose()
```

Rilascia le risorse utilizzate.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Token di cancellazione del monitor utilizzato per l'interruzione del processo. Per impostazione predefinita ogni IInterruptMonitor genera la propria cancellationSource.

**Returns:**
Istanza di CancellationTokenSource

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Ottiene o imposta l'istanza IInterruptMonitor, che è unica per ogni thread.

**Returns:**
Istanza IInterruptMonitor

### interrupt {#interrupt--}
```
public void interrupt()
```

Invia una richiesta per interrompere le operazioni.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Ottiene o imposta l'istanza IInterruptMonitor, che è unica per ogni thread.
