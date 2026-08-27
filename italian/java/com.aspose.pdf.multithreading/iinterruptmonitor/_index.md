---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta informazioni sull'interruzione."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Rappresenta informazioni sull'interruzione.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Token di cancellazione del monitor utilizzato per l'interruzione del processo. Per impostazione predefinita ogni IInterruptMonitor genera la propria cancellationSource. |
| [interrupt](#interrupt--) | Invia una richiesta per interrompere le operazioni. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Token di cancellazione del monitor utilizzato per l'interruzione del processo. Per impostazione predefinita ogni IInterruptMonitor genera la propria cancellationSource.

**Returns:**
Istanza di CancellationTokenSource

### interrupt {#interrupt--}
```
void interrupt()
```

Invia una richiesta per interrompere le operazioni.
