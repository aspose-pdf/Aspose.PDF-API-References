---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Aspose.PDF for Java API Referansı"
description: "Kesinti hakkında bilgi temsil eder."
type: docs
weight: 40
url: /tr/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

Kesinti hakkında bilgi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | Yeni bir {@link InterruptMonitor} sınıfı örneği oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [dispose](#dispose--) | Kullanılan kaynakları serbest bırakır. |
| [getCancellationToken](#getCancellationToken--) | İşlem kesintisi için kullanılan monitörün iptal belirteci. Varsayılan olarak her IInterruptMonitor kendi cancellationSource'ını oluşturur. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır veya ayarlar. |
| [interrupt](#interrupt--) | İşlemleri kesmek için bir istek gönderir. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır veya ayarlar. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

Yeni bir {@link InterruptMonitor} sınıfı örneği oluşturur.

### dispose {#dispose--}
```
public final void dispose()
```

Kullanılan kaynakları serbest bırakır.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

İşlem kesintisi için kullanılan monitörün iptal belirteci. Varsayılan olarak her IInterruptMonitor kendi cancellationSource'ını oluşturur.

**Returns:**
CancellationTokenSource örneği

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır veya ayarlar.

**Returns:**
IInterruptMonitor örneği

### interrupt {#interrupt--}
```
public void interrupt()
```

İşlemleri kesmek için bir istek gönderir.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır veya ayarlar.
