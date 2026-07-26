---
title: "IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "中断に関する情報を表します。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor extends com.aspose.ms.System.IDisposable
```

中断に関する情報を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCancellationToken](#getCancellationToken--) | プロセス中断に使用されるモニターのキャンセルトークンです。デフォルトでは、各 IInterruptMonitor が独自の cancellationSource を生成します。 |
| [interrupt](#interrupt--) | 操作を中断するリクエストを送信します。 |

### getCancellationToken {#getCancellationToken--}
```
CancellationTokenSource getCancellationToken()
```

プロセス中断に使用されるモニターのキャンセルトークンです。デフォルトでは、各 IInterruptMonitor が独自の cancellationSource を生成します。

**Returns:**
CancellationTokenSource インスタンス

### interrupt {#interrupt--}
```
void interrupt()
```

操作を中断するリクエストを送信します。
