---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.TruncationStrategy クラス。スレッドが実行前にどのように切り捨てられるかを制御する切り捨て戦略を表します。
type: docs
weight: 1240
url: /ja/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy クラス

スレッドが実行前にどのように切り捨てられるかを制御する切り捨て戦略を表します。

```csharp
public class TruncationStrategy
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | 実行のコンテキストを構築する際に、スレッドからの最新のメッセージの数を取得または設定します。 |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | スレッドに使用する切り捨て戦略を取得または設定します。デフォルトは auto です。last_messages に設定すると、スレッドはスレッド内の最新の n 件のメッセージに切り捨てられます。auto に設定すると、スレッドの中央にあるメッセージはモデルのコンテキスト長 max_prompt_tokens に収まるように削除されます。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)