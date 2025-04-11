---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Multithreading.InterruptMonitor. Mewakili informasi tentang interupsi
type: docs
weight: 7000
url: /id/net/aspose.pdf.multithreading/interruptmonitor/
---
## Kelas InterruptMonitor

Mewakili informasi tentang interupsi.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Token pembatalan monitor yang digunakan untuk interupsi proses. Secara default, setiap IInterruptMonitor menghasilkan cancellationSource-nya sendiri. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Mendapatkan atau menetapkan instance IInterruptMonitor yang unik untuk setiap thread. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Menghapus sumber daya yang digunakan. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Mengirim permintaan untuk menginterupsi operasi. |

### Lihat Juga

* antarmuka [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)