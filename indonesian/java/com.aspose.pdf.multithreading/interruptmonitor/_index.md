---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili informasi tentang interupsi."
type: docs
weight: 40
url: /id/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Mewakili informasi tentang interupsi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Menginisialisasi sebuah instance baru dari kelas {@link InterruptMonitor}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [dispose](#dispose--) | Membuang sumber daya yang digunakan. |
| [getCancellationToken](#getCancellationToken--) | Token pembatalan monitor yang digunakan untuk interupsi proses. Secara default setiap IInterruptMonitor menghasilkan cancellationSource miliknya sendiri. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Mendapatkan atau mengatur instance IInterruptMonitor yang unik untuk setiap thread. |
| [interrupt](#interrupt--) | Mengirim permintaan untuk menghentikan operasi. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Mendapatkan atau mengatur instance IInterruptMonitor yang unik untuk setiap thread. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Menginisialisasi sebuah instance baru dari kelas {@link InterruptMonitor}.

### dispose {#dispose--}
```
public final void dispose()
```

Membuang sumber daya yang digunakan.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

Token pembatalan monitor yang digunakan untuk interupsi proses. Secara default setiap IInterruptMonitor menghasilkan cancellationSource miliknya sendiri.

**Returns:**
Instansi CancellationTokenSource

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Mendapatkan atau mengatur instance IInterruptMonitor yang unik untuk setiap thread.

**Returns:**
IInterruptMonitor instance

### interrupt {#interrupt--}
```
public void interrupt()
```

Mengirim permintaan untuk menghentikan operasi.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Mendapatkan atau mengatur instance IInterruptMonitor yang unik untuk setiap thread.
