---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.IInterruptMonitor インターフェース。中断に関する情報を表します
type: docs
weight: 6990
url: /ja/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor インターフェース

中断に関する情報を表します。

```csharp
public interface IInterruptMonitor : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | プロセス中断に使用されるモニターのキャンセルトークン。デフォルトでは、各 IInterruptMonitor は独自の cancellationSource を生成します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | 操作を中断するリクエストを送信します。 |

### 参照

* 名前空間 [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* アセンブリ [Aspose.PDF](../../)