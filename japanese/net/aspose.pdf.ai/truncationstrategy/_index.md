---
title: "クラス TruncationStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.TruncationStrategy クラス。実行前にスレッドがどのように切り詰められるかを制御する切り詰め戦略を表します"
type: docs
weight: 1330
url: /ja/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

実行前にスレッドがどのように切り詰められるかを制御するトランケーション戦略を表します。

```csharp
public class TruncationStrategy
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | 実行のコンテキストを構築する際に、スレッドから取得する最新メッセージの数を取得または設定します。 |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | スレッドに使用する切り詰め戦略を取得または設定します。デフォルトは auto です。last_messages に設定すると、スレッドは最新の n 件のメッセージに切り詰められます。auto に設定した場合、モデルのコンテキスト長（max_prompt_tokens）に合わせるため、スレッドの途中のメッセージが削除されます。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


