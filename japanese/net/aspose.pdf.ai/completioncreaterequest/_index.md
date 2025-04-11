---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionCreateRequest クラス。Create Chat Completion エンドポイントへのリクエストを表します。
type: docs
weight: 220
url: /ja/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest クラス

Create Chat Completion エンドポイントへのリクエストを表します。

```csharp
public class CompletionCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | -2.0 と 2.0 の間の数値を取得または設定します。正の値は、これまでのテキスト内の既存の頻度に基づいて新しいトークンにペナルティを与え、モデルが同じ行を逐語的に繰り返す可能性を減少させます。 |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | 完成時に指定されたトークンが出現する可能性を取得または設定します。トークン（トークナイザー内のトークン ID によって指定）を -100 から 100 の関連バイアス値にマッピングする JSON オブジェクトを受け入れます。 |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | 出力トークンの対数確率を返すかどうかを取得または設定します。true の場合、メッセージの内容に返された各出力トークンの対数確率を返します。 |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | 完成時に生成する最大トークン数を取得または設定します。 |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | これまでの会話を構成するメッセージのリストを取得または設定します。 |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | 使用するモデルの ID を取得または設定します。 |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | 各入力メッセージに対して生成するチャット完了の選択肢の数を取得または設定します。生成されたトークンの数に基づいて料金が発生することに注意してください。コストを最小限に抑えるために n を 1 に設定してください。 |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | -2.0 と 2.0 の間の数値を取得または設定します。正の値は、これまでのテキストに出現するかどうかに基づいて新しいトークンにペナルティを与え、モデルが新しいトピックについて話す可能性を高めます。 |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | モデルが出力する形式を指定するオブジェクトを取得または設定します。GPT-4 Turbo および gpt-3.5-turbo-1106 より新しいすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、モデルが生成するメッセージが有効な JSON であることを保証する JSON モードが有効になります。 |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Seed 値を取得または設定します。この機能はベータ版です。指定された場合、同じシードとパラメータでの繰り返しリクエストが同じ結果を返すように、決定論的にサンプリングするようにシステムが最善を尽くします。決定論は保証されておらず、バックエンドの変更を監視するために system_fingerprint 応答パラメータを参照する必要があります。 |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | API がさらにトークンを生成するのを停止する最大 4 つのシーケンスを取得または設定します。 |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | ストリーミングを使用するかどうかを取得または設定します。設定されている場合、ChatGPT のように部分的なメッセージデルタが送信されます。トークンは、利用可能になるとデータのみのサーバー送信イベントとして送信され、ストリームは data: [DONE] メッセージで終了します。 |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | 使用するサンプリング温度を取得または設定します。0 から 2 の間で、高い値（例：0.8）は出力をよりランダムにし、低い値（例：0.2）はより焦点を絞った決定論的なものにします。 |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | モデルによって呼び出されるツールを制御するオブジェクトを取得または設定します。none はモデルがツールを呼び出さず、代わりにメッセージを生成することを意味します。auto はモデルがメッセージを生成するか、1 つ以上のツールを呼び出すかを選択できることを意味します。required はモデルが 1 つ以上のツールを呼び出さなければならないことを意味します。{"type": "function", "function": {"name": "my_function"}} を指定すると、そのツールを呼び出すようにモデルが強制されます。ツールが存在しない場合は none がデフォルトです。ツールが存在する場合は auto がデフォルトです。 |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | モデルが呼び出す可能性のあるツールのリストを取得または設定します。現在、ツールとしては関数のみがサポートされています。モデルが JSON 入力を生成する可能性のある関数のリストを提供するために使用します。最大 128 の関数がサポートされています。 |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | 温度によるサンプリングの代替手段である、核サンプリングを取得または設定します。モデルは top_p 確率質量を持つトークンの結果を考慮します。したがって、0.1 はトップ 10% 確率質量を構成するトークンのみが考慮されることを意味します。 |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | あなたのエンドユーザーを表す一意の識別子を取得または設定します。これにより、OpenAI が監視し、悪用を検出するのに役立ちます。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)