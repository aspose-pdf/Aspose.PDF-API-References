---
title: "Klass InterruptMonitor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Multithreading.InterruptMonitor-klass. Representerar information om avbrott."
type: docs
weight: 7140
url: /sv/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

Representerar information om avbrott.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Monitorens avbokningstoken som används för processavbrott. Som standard genererar varje IInterruptMonitor sin egen cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Hämtar eller anger IInterruptMonitor-instansen som är unik för varje tråd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Rensar använda resurser. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Skickar en begäran om att avbryta operationer. |

### Se även

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


