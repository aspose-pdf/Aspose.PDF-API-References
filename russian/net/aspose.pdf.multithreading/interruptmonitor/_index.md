---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Multithreading.InterruptMonitor. Представляет информацию об прерывании
type: docs
weight: 7000
url: /ru/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

Представляет информацию об прерывании.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructors

| Name | Description |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Конструктор по умолчанию. |

## Properties

| Name | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый IInterruptMonitor генерирует свой собственный cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Получает или задает экземпляр IInterruptMonitor, который уникален для каждого потока. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Освобождает используемые ресурсы. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Отправляет запрос на прерывание операций. |

### See Also

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)