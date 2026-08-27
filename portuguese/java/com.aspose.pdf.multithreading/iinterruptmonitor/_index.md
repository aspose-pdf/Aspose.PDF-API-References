---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa informações sobre interrupção."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Representa informações sobre interrupção.

## Métodos

| Método | Descrição |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Token de cancelamento do monitor usado para interrupção do processo. Por padrão, cada IInterruptMonitor gera sua própria cancellationSource. |
| [interrupt](#interrupt--) | Envia uma solicitação para interromper operações. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Token de cancelamento do monitor usado para interrupção do processo. Por padrão, cada IInterruptMonitor gera sua própria cancellationSource.

**Returns:**
Instância de CancellationTokenSource

### interrupt {#interrupt--}
```
void interrupt()
```

Envia uma solicitação para interromper operações.
