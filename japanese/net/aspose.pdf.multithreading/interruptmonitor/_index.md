---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.InterruptMonitor クラス。中断に関する情報を表します。
type: docs
weight: 7000
url: /ja/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor クラス

中断に関する情報を表します。

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | デフォルトコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | プロセス中断に使用されるモニターのキャンセルトークン。デフォルトでは、各 IInterruptMonitor は独自の cancellationSource を生成します。 |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | 各スレッドに対してユニークな IInterruptMonitor インスタンスを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | 使用されたリソースを破棄します。 |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | 操作を中断するリクエストを送信します。 |

### 参照

* インターフェース [IInterruptMonitor](../iinterruptmonitor/)
* 名前空間 [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* アセンブリ [Aspose.PDF](../../)