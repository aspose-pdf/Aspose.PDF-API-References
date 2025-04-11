---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.InterruptMonitor sınıfı. Kesinti hakkında bilgi temsil eder
type: docs
weight: 7000
url: /tr/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor sınıfı

Kesinti hakkında bilgi temsil eder.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | İşlem kesintisi için kullanılan izleyici iptal belirteci. Varsayılan olarak her IInterruptMonitor kendi cancellationSource'unu oluşturur. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Her bir iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Kullanılan kaynakları serbest bırakır. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | İşlemleri kesmek için bir istek gönderir. |

### Ayrıca Bakınız

* arayüz [IInterruptMonitor](../iinterruptmonitor/)
* ad alanı [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* derleme [Aspose.PDF](../../)