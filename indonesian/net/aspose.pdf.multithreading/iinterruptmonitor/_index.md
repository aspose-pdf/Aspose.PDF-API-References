---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Antarmuka Aspose.Pdf.Multithreading.IInterruptMonitor. Mewakili informasi tentang interupsi
type: docs
weight: 6990
url: /id/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## Antarmuka IInterruptMonitor

Mewakili informasi tentang interupsi.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Token pembatalan monitor yang digunakan untuk interupsi proses. Secara default, setiap IInterruptMonitor menghasilkan cancellationSource-nya sendiri |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Mengirim permintaan untuk menginterupsi operasi. |

### Lihat Juga

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)