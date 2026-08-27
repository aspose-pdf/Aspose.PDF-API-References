---
title: "クラス Choice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.Choice クラス。チャット完了応答における選択肢を表します。"
type: docs
weight: 210
url: /ja/net/aspose.pdf.ai/choice/
---
## Choice class

チャット完了レスポンス内の選択肢を表します。

```csharp
public class Choice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Choice](choice/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | モデルがトークンの生成を停止した理由を取得または設定します。モデルが自然な停止点または指定された停止シーケンスに達した場合は stop、リクエストで指定された最大トークン数に達した場合は length になります。 |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | 選択肢リスト内の選択肢のインデックスを取得または設定します。 |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | 選択肢の対数確率情報を取得または設定します。 |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | モデルによって生成されたチャット完了メッセージを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | 選択肢の内容を文字列として返します。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


