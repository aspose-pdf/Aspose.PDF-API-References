---
title: "类 InterruptMonitor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Multithreading.InterruptMonitor 类。表示中断信息"
type: docs
weight: 7140
url: /zh/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

表示中断信息。

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | 用于进程中断的监视器取消令牌。默认情况下，每个 IInterruptMonitor 会生成其自己的 cancellationSource。 |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | 获取或设置每个线程唯一的 IInterruptMonitor 实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | 释放使用的资源。 |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | 发送请求以中断操作。 |

### 另请参见

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


