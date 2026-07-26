---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Informationen über Unterbrechungen dar."
type: docs
weight: 40
url: /de/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Stellt Informationen über Unterbrechungen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Initialisiert eine neue Instanz der {@link InterruptMonitor} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [dispose](#dispose--) | Gibt verwendete Ressourcen frei. |
| [getCancellationToken](#getCancellationToken--) | Das Abbruch-Token des Monitors wird für die Prozessunterbrechung verwendet. Standardmäßig erzeugt jeder IInterruptMonitor seine eigene cancellationSource. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Liest oder setzt die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist. |
| [interrupt](#interrupt--) | Sendet eine Anforderung, um Vorgänge zu unterbrechen. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Liest oder setzt die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Initialisiert eine neue Instanz der {@link InterruptMonitor} Klasse.

### dispose {#dispose--}
```
public final void dispose()
```

Gibt verwendete Ressourcen frei.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Das Abbruch-Token des Monitors wird für die Prozessunterbrechung verwendet. Standardmäßig erzeugt jeder IInterruptMonitor seine eigene cancellationSource.

**Returns:**
CancellationTokenSource-Instanz

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Liest oder setzt die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist.

**Returns:**
IInterruptMonitor-Instanz

### interrupt {#interrupt--}
```
public void interrupt()
```

Sendet eine Anforderung, um Vorgänge zu unterbrechen.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Liest oder setzt die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist.
