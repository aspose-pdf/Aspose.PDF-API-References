---
title: "InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "中断に関する情報を表します。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.multithreading.InterruptMonitor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IInterruptMonitor

```
public class InterruptMonitor extends Object implements IInterruptMonitor
```

中断に関する情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [InterruptMonitor](#InterruptMonitor--) | {@link InterruptMonitor} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [dispose](#dispose--) | 使用されたリソースを解放します。 |
| [getCancellationToken](#getCancellationToken--) | プロセスの中断に使用されるモニターのキャンセルトークンです。デフォルトでは各 IInterruptMonitor が独自の cancellationSource を生成します。 |
| [getThreadLocalInstance](#getThreadLocalInstance--) | 各スレッドごとに固有の IInterruptMonitor インスタンスを取得または設定します。 |
| [interrupt](#interrupt--) | 操作を中断するリクエストを送信します。 |
| [setThreadLocalInstance](#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-) | 各スレッドごとに固有の IInterruptMonitor インスタンスを取得または設定します。 |

### InterruptMonitor {#InterruptMonitor--}
```
public InterruptMonitor()
```

{@link InterruptMonitor} クラスの新しいインスタンスを初期化します。

### dispose {#dispose--}
```
public final void dispose()
```

使用されたリソースを解放します。

### getCancellationToken {#getCancellationToken--}
```
public final CancellationTokenSource getCancellationToken()
```

プロセスの中断に使用されるモニターのキャンセルトークンです。デフォルトでは各 IInterruptMonitor が独自の cancellationSource を生成します。

**Returns:**
CancellationTokenSource インスタンス

### getThreadLocalInstance {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```

各スレッドごとに固有の IInterruptMonitor インスタンスを取得または設定します。

**Returns:**
IInterruptMonitor インスタンス

### interrupt {#interrupt--}
```
public void interrupt()
```

操作を中断するリクエストを送信します。

### setThreadLocalInstance {#setThreadLocalInstance-com.aspose.pdf.multithreading.IInterruptMonitor-}
各スレッドごとに固有の IInterruptMonitor インスタンスを取得または設定します。
