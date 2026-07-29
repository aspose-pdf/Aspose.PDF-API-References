---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Informationen über Unterbrechungen dar."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Stellt Informationen über Unterbrechungen dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Der Abbruch-Token des Monitors, der für die Prozessunterbrechung verwendet wird. Standardmäßig erzeugt jeder IInterruptMonitor seine eigene CancellationSource. |
| [interrupt](#interrupt--) | Sendet eine Anforderung, um Vorgänge zu unterbrechen. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Der Abbruch-Token des Monitors, der für die Prozessunterbrechung verwendet wird. Standardmäßig erzeugt jeder IInterruptMonitor seine eigene CancellationSource.

**Returns:**
CancellationTokenSource-Instanz

### interrupt {#interrupt--}
```
void interrupt()
```

Sendet eine Anforderung, um Vorgänge zu unterbrechen.
