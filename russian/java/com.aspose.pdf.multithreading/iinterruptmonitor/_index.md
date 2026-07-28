---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет информацию об прерывании."
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Представляет информацию об прерывании.

## Методы

| Метод | Описание |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый IInterruptMonitor генерирует свой собственный cancellationSource |
| [interrupt](#interrupt--) | Отправляет запрос на прерывание операций. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый IInterruptMonitor генерирует свой собственный cancellationSource

**Returns:**
Экземпляр CancellationTokenSource

### interrupt {#interrupt--}
```
void interrupt()
```

Отправляет запрос на прерывание операций.
