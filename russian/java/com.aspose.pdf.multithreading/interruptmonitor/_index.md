---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет информацию об прерывании."
type: docs
weight: 40
url: /ru/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Представляет информацию об прерывании.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Инициализирует новый экземпляр класса {@link InterruptMonitor}. |

## Методы

| Метод | Описание |
| --- | --- |
| [dispose](#dispose--) | Освобождает используемые ресурсы. |
| [getCancellationToken](#getCancellationToken--) | Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый IInterruptMonitor генерирует свой собственный cancellationSource. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Получает или задает экземпляр IInterruptMonitor, уникальный для каждого потока. |
| [interrupt](#interrupt--) | Отправляет запрос на прерывание операций. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Получает или задает экземпляр IInterruptMonitor, уникальный для каждого потока. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Инициализирует новый экземпляр класса {@link InterruptMonitor}.

### dispose {#dispose--}
```
public final void dispose()
```

Освобождает используемые ресурсы.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый IInterruptMonitor генерирует свой собственный cancellationSource.

**Returns:**
Экземпляр CancellationTokenSource

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Получает или задает экземпляр IInterruptMonitor, уникальный для каждого потока.

**Returns:**
Экземпляр IInterruptMonitor

### interrupt {#interrupt--}
```
public void interrupt()
```

Отправляет запрос на прерывание операций.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Получает или задает экземпляр IInterruptMonitor, уникальный для каждого потока.
