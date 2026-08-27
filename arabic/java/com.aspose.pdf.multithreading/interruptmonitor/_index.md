---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل معلومات حول الانقطاع."
type: docs
weight: 40
url: /ar/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

يمثل معلومات حول الانقطاع.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | ينشئ مثيلاً جديدًا للفئة {@link InterruptMonitor}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [dispose](#dispose--) | يقوم بتحرير الموارد المستخدمة. |
| [getCancellationToken](#getCancellationToken--) | رمز إلغاء المراقبة يُستخدم لإيقاف العملية. بشكل افتراضي، كل IInterruptMonitor يولد مصدر إلغاء خاص به. |
| [getThreadLocalInstance](#getThreadLocalInstance--) | يحصل أو يعيّن مثيل IInterruptMonitor الذي يكون فريدًا لكل خيط. |
| [interrupt](#interrupt--) | يرسل طلبًا لمقاطعة العمليات. |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | يحصل أو يعيّن مثيل IInterruptMonitor الذي يكون فريدًا لكل خيط. |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

ينشئ مثيلاً جديدًا للفئة {@link InterruptMonitor}.

### dispose {#dispose--}
```
public final void dispose()
```

يقوم بتحرير الموارد المستخدمة.

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

رمز إلغاء المراقبة يُستخدم لإيقاف العملية. بشكل افتراضي، كل IInterruptMonitor يولد مصدر إلغاء خاص به.

**Returns:**
مثيل CancellationTokenSource

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

يحصل أو يعيّن مثيل IInterruptMonitor الذي يكون فريدًا لكل خيط.

**Returns:**
مثيل IInterruptMonitor

### interrupt {#interrupt--}
```
public void interrupt()
```

يرسل طلبًا لمقاطعة العمليات.

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
يحصل أو يعيّن مثيل IInterruptMonitor الذي يكون فريدًا لكل خيط.
