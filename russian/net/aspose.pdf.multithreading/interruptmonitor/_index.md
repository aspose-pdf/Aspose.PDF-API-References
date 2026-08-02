---
title: "Класс InterruptMonitor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Multithreading.InterruptMonitor класс. Представляет информацию о прерывании"
type: docs
weight: 7140
url: /ru/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

Представляет информацию о прерывании.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый IInterruptMonitor генерирует собственный cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Получает или задает экземпляр IInterruptMonitor, который уникален для каждого потока. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Освобождает используемые ресурсы. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Отправляет запрос на прерывание операций. |

### См. также

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


