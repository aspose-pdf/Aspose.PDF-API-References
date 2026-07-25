---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente des informations sur l'interruption."
type: docs
weight: 40
url: /fr/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Représente des informations sur l'interruption.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Initialise une nouvelle instance de la classe {@link InterruptMonitor}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [dispose](#dispose--) | Libère les ressources utilisées. |
| [getCancellationToken](#getCancellationToken--) | Jeton d'annulation du moniteur utilisé pour l'interruption du processus. Par défaut, chaque IInterruptMonitor génère son propre cancellationSource. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Obtient ou définit l'instance IInterruptMonitor qui est unique pour chaque thread. |
| [interrupt](#interrupt--) | Envoie une requête pour interrompre les opérations. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Obtient ou définit l'instance IInterruptMonitor qui est unique pour chaque thread. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Initialise une nouvelle instance de la classe {@link InterruptMonitor}.

### dispose {#dispose--}
```
public final void dispose()
```

Libère les ressources utilisées.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Jeton d'annulation du moniteur utilisé pour l'interruption du processus. Par défaut, chaque IInterruptMonitor génère son propre cancellationSource.

**Returns:**
Instance de CancellationTokenSource

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Obtient ou définit l'instance IInterruptMonitor qui est unique pour chaque thread.

**Returns:**
Instance IInterruptMonitor

### interrupt {#interrupt--}
```
public void interrupt()
```

Envoie une requête pour interrompre les opérations.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Obtient ou définit l'instance IInterruptMonitor qui est unique pour chaque thread.
