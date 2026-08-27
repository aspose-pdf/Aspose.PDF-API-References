---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili informasi tentang interupsi."
type: docs
weight: 20
url: /id/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Mewakili informasi tentang interupsi.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | Token pembatalan monitor yang digunakan untuk interupsi proses. Secara default setiap IInterruptMonitor menghasilkan cancellationSource miliknya sendiri. |
| [interrupt](#interrupt--) | Mengirim permintaan untuk menghentikan operasi. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

Token pembatalan monitor yang digunakan untuk interupsi proses. Secara default setiap IInterruptMonitor menghasilkan cancellationSource miliknya sendiri.

**Returns:**
Instansi CancellationTokenSource

### interrupt {#interrupt--}
```
void interrupt()
```

Mengirim permintaan untuk menghentikan operasi.
