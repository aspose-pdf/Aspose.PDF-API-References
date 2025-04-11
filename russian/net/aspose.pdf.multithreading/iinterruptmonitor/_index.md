---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Интерфейс Aspose.Pdf.Multithreading.IInterruptMonitor. Представляет информацию об прерывании
type: docs
weight: 6990
url: /ru/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## Интерфейс IInterruptMonitor

Представляет информацию об прерывании.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый IInterruptMonitor генерирует свой собственный cancellationSource |

## Методы

| Имя | Описание |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Отправляет запрос на прерывание операций. |

### См. также

* пространство имен [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* сборка [Aspose.PDF](../../)