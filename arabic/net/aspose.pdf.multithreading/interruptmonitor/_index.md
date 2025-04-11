---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Multithreading.InterruptMonitor. تمثل معلومات حول الانقطاع
type: docs
weight: 7000
url: /ar/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

تمثل معلومات حول الانقطاع.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructors

| Name | Description |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | رمز إلغاء المراقب المستخدم لقطع العملية. بشكل افتراضي، يقوم كل IInterruptMonitor بإنشاء cancellationSource خاص به. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | يحصل أو يحدد مثيل IInterruptMonitor الفريد لكل خيط. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | يتخلص من الموارد المستخدمة. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | يرسل طلبًا لقطع العمليات. |

### See Also

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)