---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.InterruptMonitor klass. Representerar information om avbrott
type: docs
weight: 7000
url: /sv/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor klass

Representerar information om avbrott.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Övervakningens avbokningstoken som används för processavbrott. Som standard genererar varje IInterruptMonitor sin egen cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Hämtar eller ställer in IInterruptMonitor-instansen som är unik för varje tråd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Avsätter använda resurser. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Skickar en begäran om att avbryta operationer. |

### Se Även

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)