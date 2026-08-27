---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل معلومات حول الانقطاع."
type: docs
weight: 20
url: /ar/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

يمثل معلومات حول الانقطاع.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | رمز الإلغاء الخاص بالمراقب يُستخدم لمقاطعة العملية. بشكل افتراضي، كل IInterruptMonitor يُنشئ مصدر إلغاء خاص به. |
| [interrupt](#interrupt--) | يرسل طلبًا لمقاطعة العمليات. |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

رمز الإلغاء الخاص بالمراقب يُستخدم لمقاطعة العملية. بشكل افتراضي، كل IInterruptMonitor يُنشئ مصدر إلغاء خاص به.

**Returns:**
مثيل CancellationTokenSource

### interrupt {#interrupt--}
```
void interrupt()
```

يرسل طلبًا لمقاطعة العمليات.
