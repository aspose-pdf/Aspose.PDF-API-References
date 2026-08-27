---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar information om avbrott."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Representerar information om avbrott.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Monitorns avbokningstoken som används för processavbrott. Som standard genererar varje IInterruptMonitor sin egen cancellationSource |
| [interrupt](#interrupt--) | Skickar en begäran om att avbryta operationer. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Monitorns avbokningstoken som används för processavbrott. Som standard genererar varje IInterruptMonitor sin egen cancellationSource

**Returns:**
CancellationTokenSource‑instans

### interrupt {#interrupt--}
```
void interrupt()
```

Skickar en begäran om att avbryta operationer.
