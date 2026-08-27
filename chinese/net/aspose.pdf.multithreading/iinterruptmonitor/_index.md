---
title: "接口 IInterruptMonitor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Multithreading.IInterruptMonitor 接口。表示中断信息"
type: docs
weight: 7130
url: /zh/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor interface

表示中断信息。

```csharp
public interface IInterruptMonitor : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | 监视器的取消令牌用于过程中的中断。默认情况下，每个 IInterruptMonitor 会生成其自己的 cancellationSource |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | 发送请求以中断操作。 |

### 另请参见

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


