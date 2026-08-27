---
title: "インターフェイス IInterruptMonitor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Multithreading.IInterruptMonitor インターフェイス。割り込みに関する情報を表します。"
type: docs
weight: 7130
url: /ja/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor interface

中断に関する情報を表します。

```csharp
public interface IInterruptMonitor : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | プロセスの割り込みに使用されるモニターのキャンセルトークン。デフォルトでは各 IInterruptMonitor が独自の cancellationSource を生成します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | 操作を中断するリクエストを送信します。 |

### 関連項目

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


