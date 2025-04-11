---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.IInterruptMonitor arayüzü. Kesinti hakkında bilgi temsil eder
type: docs
weight: 6990
url: /tr/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor arayüzü

Kesinti hakkında bilgi temsil eder.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | İşlem kesintisi için kullanılan izleyici iptal belirteci. Varsayılan olarak her IInterruptMonitor kendi cancellationSource'unu oluşturur |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | İşlemleri kesmek için bir istek gönderir. |

### Ayrıca Bakınız

* ad alanı [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* derleme [Aspose.PDF](../../)