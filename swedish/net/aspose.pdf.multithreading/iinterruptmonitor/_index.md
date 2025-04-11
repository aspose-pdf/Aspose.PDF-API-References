---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.IInterruptMonitor-gränssnitt. Representerar information om avbrott
type: docs
weight: 6990
url: /sv/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor-gränssnitt

Representerar information om avbrott.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Övervakningens avbokningstoken som används för processavbrott. Som standard genererar varje IInterruptMonitor sin egen cancellationSource |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Skickar en begäran om att avbryta operationer. |

### Se Även

* namnrymd [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* sammansättning [Aspose.PDF](../../)