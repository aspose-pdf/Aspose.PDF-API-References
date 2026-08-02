---
title: "Интерфейс IInterruptMonitor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Multithreading.IInterruptMonitor интерфейс. Представляет информацию о прерывании"
type: docs
weight: 7130
url: /ru/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor interface

Представляет информацию о прерывании.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый IInterruptMonitor генерирует собственный cancellationSource |

## Методы

| Имя | Описание |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Отправляет запрос на прерывание операций. |

### См. также

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


