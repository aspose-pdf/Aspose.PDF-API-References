---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.InterruptMonitor 类。表示有关中断的信息
type: docs
weight: 7000
url: /zh/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

表示有关中断的信息。

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructors

| Name | Description |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | 监视器的取消令牌，用于进程中断。默认情况下，每个 IInterruptMonitor 生成自己的 cancellationSource。 |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | 获取或设置每个线程唯一的 IInterruptMonitor 实例。 |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | 释放使用的资源。 |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | 发送中断操作的请求。 |

### See Also

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)