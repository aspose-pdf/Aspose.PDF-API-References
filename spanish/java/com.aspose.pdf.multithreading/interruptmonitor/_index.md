---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa información sobre la interrupción."
type: docs
weight: 40
url: /es/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Representa información sobre la interrupción.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Inicializa una nueva instancia de la clase {@link InterruptMonitor}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [dispose](#dispose--) | Libera los recursos utilizados. |
| [getCancellationToken](#getCancellationToken--) | Token de cancelación del monitor utilizado para la interrupción del proceso. Por defecto, cada IInterruptMonitor genera su propio cancellationSource. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Obtiene o establece la instancia IInterruptMonitor que es única para cada hilo. |
| [interrupt](#interrupt--) | Envía una solicitud para interrumpir operaciones. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Obtiene o establece la instancia IInterruptMonitor que es única para cada hilo. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Inicializa una nueva instancia de la clase {@link InterruptMonitor}.

### dispose {#dispose--}
```
public final void dispose()
```

Libera los recursos utilizados.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Token de cancelación del monitor utilizado para la interrupción del proceso. Por defecto, cada IInterruptMonitor genera su propio cancellationSource.

**Returns:**
Instancia de CancellationTokenSource

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Obtiene o establece la instancia IInterruptMonitor que es única para cada hilo.

**Returns:**
Instancia IInterruptMonitor

### interrupt {#interrupt--}
```
public void interrupt()
```

Envía una solicitud para interrumpir operaciones.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Obtiene o establece la instancia IInterruptMonitor que es única para cada hilo.
