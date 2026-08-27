---
title: "الفئة InterruptMonitor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Multithreading.InterruptMonitor. تمثل معلومات حول الانقطاع"
type: docs
weight: 7140
url: /ar/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

يمثل معلومات حول الانقطاع.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | رمز الإلغاء cancellation token للمراقب يُستخدم لوقف العملية. بشكل افتراضي كل IInterruptMonitor يولد cancellationSource الخاص به. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | يحصل أو يعيّن مثيل IInterruptMonitor الذي يكون فريداً لكل خيط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | يحرّر الموارد المستخدمة. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | يرسل طلباً لوقف العمليات. |

### انظر أيضًا

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


