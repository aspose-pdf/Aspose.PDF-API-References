---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa informações sobre interrupção."
type: docs
weight: 40
url: /pt/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Representa informações sobre interrupção.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Inicializa uma nova instância da classe {@link InterruptMonitor}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [dispose](#dispose--) | Libera os recursos usados. |
| [getCancellationToken](#getCancellationToken--) | Token de cancelamento do monitor usado para interrupção do processo. Por padrão, cada IInterruptMonitor gera sua própria cancellationSource. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Obtém ou define a instância IInterruptMonitor que é única para cada thread. |
| [interrupt](#interrupt--) | Envia uma solicitação para interromper operações. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Obtém ou define a instância IInterruptMonitor que é única para cada thread. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Inicializa uma nova instância da classe {@link InterruptMonitor}.

### dispose {#dispose--}
```
public final void dispose()
```

Libera os recursos usados.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Token de cancelamento do monitor usado para interrupção do processo. Por padrão, cada IInterruptMonitor gera sua própria cancellationSource.

**Returns:**
Instância de CancellationTokenSource

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Obtém ou define a instância IInterruptMonitor que é única para cada thread.

**Returns:**
Instância IInterruptMonitor

### interrupt {#interrupt--}
```
public void interrupt()
```

Envia uma solicitação para interromper operações.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Obtém ou define a instância IInterruptMonitor que é única para cada thread.
