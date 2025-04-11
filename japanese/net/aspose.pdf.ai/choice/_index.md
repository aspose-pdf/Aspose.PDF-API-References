---
title: Class Choice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.Choice クラス。チャット完了応答における選択を表します。
type: docs
weight: 200
url: /ja/net/aspose.pdf.ai/choice/
---
## Choice クラス

チャット完了応答における選択を表します。

```csharp
public class Choice
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Choice](choice/)() | デフォルトコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | モデルがトークンの生成を停止した理由を取得または設定します。これは、モデルが自然な停止点または提供された停止シーケンスに達した場合、またはリクエストで指定された最大トークン数に達した場合に停止します。 |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | 選択肢のリストにおける選択のインデックスを取得または設定します。 |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | 選択のための対数確率情報を取得または設定します。 |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | モデルによって生成されたチャット完了メッセージを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | 選択の内容を文字列として返します。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)