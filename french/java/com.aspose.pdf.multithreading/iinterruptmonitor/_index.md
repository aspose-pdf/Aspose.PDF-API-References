---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente des informations sur l'interruption."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Représente des informations sur l'interruption.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Jeton d'annulation du moniteur utilisé pour l'interruption du processus. Par défaut, chaque IInterruptMonitor génère sa propre cancellationSource. |
| [interrupt](#interrupt--) | Envoie une requête pour interrompre les opérations. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Jeton d'annulation du moniteur utilisé pour l'interruption du processus. Par défaut, chaque IInterruptMonitor génère sa propre cancellationSource.

**Returns:**
Instance de CancellationTokenSource

### interrupt {#interrupt--}
```
void interrupt()
```

Envoie une requête pour interrompre les opérations.
