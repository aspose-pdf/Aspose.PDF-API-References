---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.IInterruptMonitor 接口。表示有关中断的信息
type: docs
weight: 6990
url: /zh/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor 接口

表示有关中断的信息。

```csharp
public interface IInterruptMonitor : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | 用于进程中断的监视器取消令牌。默认情况下，每个 IInterruptMonitor 生成自己的 cancellationSource |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | 发送中断操作的请求。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* 程序集 [Aspose.PDF](../../)