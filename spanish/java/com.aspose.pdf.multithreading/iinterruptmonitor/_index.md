---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa información sobre la interrupción."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Representa información sobre la interrupción.

## Métodos

| Método | Descripción |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Token de cancelación del monitor utilizado para la interrupción del proceso. Por defecto, cada IInterruptMonitor genera su propio cancellationSource. |
| [interrupt](#interrupt--) | Envía una solicitud para interrumpir operaciones. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Token de cancelación del monitor utilizado para la interrupción del proceso. Por defecto, cada IInterruptMonitor genera su propio cancellationSource.

**Returns:**
Instancia de CancellationTokenSource

### interrupt {#interrupt--}
```
void interrupt()
```

Envía una solicitud para interrumpir operaciones.
