---
title: "クラス InterruptMonitor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Multithreading.InterruptMonitor クラス。割り込みに関する情報を表します。"
type: docs
weight: 7140
url: /ja/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

中断に関する情報を表します。

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | プロセスの中断に使用されるモニターのキャンセルトークンです。デフォルトでは、各 IInterruptMonitor が独自の cancellationSource を生成します。 |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | 各スレッドに対して一意の IInterruptMonitor インスタンスを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | 使用されたリソースを破棄します。 |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | 操作を中断するリクエストを送信します。 |

### 関連項目

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


