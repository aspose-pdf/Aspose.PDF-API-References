---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Aspose.PDF for Java API Referansı"
description: "Kesinti hakkında bilgi temsil eder."
type: docs
weight: 20
url: /tr/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

Kesinti hakkında bilgi temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | İşlem kesintisi için kullanılan monitörün iptal belirteci. Varsayılan olarak her IInterruptMonitor kendi cancellationSource'ını oluşturur. |
| [interrupt](#interrupt--) | İşlemleri kesmek için bir istek gönderir. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

İşlem kesintisi için kullanılan monitörün iptal belirteci. Varsayılan olarak her IInterruptMonitor kendi cancellationSource'ını oluşturur.

**Returns:**
CancellationTokenSource örneği

### interrupt {#interrupt--}
```
void interrupt()
```

İşlemleri kesmek için bir istek gönderir.
