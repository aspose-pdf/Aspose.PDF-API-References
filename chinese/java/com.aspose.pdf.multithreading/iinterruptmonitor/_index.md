---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Aspose.PDF for Java API 参考"
description: "表示中断信息。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

表示中断信息。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | 用于进程中断的监视器取消令牌。默认情况下，每个 IInterruptMonitor 会生成其自己的 cancellationSource。 |
| [interrupt](#interrupt--) | 发送请求以中断操作。 |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

用于进程中断的监视器取消令牌。默认情况下，每个 IInterruptMonitor 会生成其自己的 cancellationSource。

**Returns:**
CancellationTokenSource 实例

### interrupt {#interrupt--}
```
void interrupt()
```

发送请求以中断操作。
