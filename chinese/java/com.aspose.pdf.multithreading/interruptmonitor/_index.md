---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Aspose.PDF for Java API 参考"
description: "表示中断信息。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

表示中断信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | 初始化 {@link InterruptMonitor} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose](#dispose--) | 释放使用的资源。 |
| [getCancellationToken](#getCancellationToken--) | 用于进程中断的监视器取消令牌。默认情况下，每个 IInterruptMonitor 会生成其自己的 cancellationSource。 |
| [getThreadLocalInstance](#getThreadLocalInstance--) | 获取或设置对每个线程唯一的 IInterruptMonitor 实例。 |
| [interrupt](#interrupt--) | 发送请求以中断操作。 |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | 获取或设置对每个线程唯一的 IInterruptMonitor 实例。 |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

初始化 {@link InterruptMonitor} 类的新实例。

### dispose {#dispose--}
```
public final void dispose()
```

释放使用的资源。

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

用于进程中断的监视器取消令牌。默认情况下，每个 IInterruptMonitor 会生成其自己的 cancellationSource。

**Returns:**
CancellationTokenSource 实例

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

获取或设置对每个线程唯一的 IInterruptMonitor 实例。

**Returns:**
IInterruptMonitor 实例

### interrupt {#interrupt--}
```
public void interrupt()
```

发送请求以中断操作。

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
获取或设置对每个线程唯一的 IInterruptMonitor 实例。
