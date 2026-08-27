---
title: "クラス CompletionCreateRequest"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.CompletionCreateRequest クラス。Create Chat Completion エンドポイントへのリクエストを表します。"
type: docs
weight: 230
url: /ja/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

Chat Completion 作成エンドポイントへのリクエストを表します。

```csharp
public class CompletionCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | -2.0 から 2.0 の間の数値を取得または設定します。正の値は、これまでのテキスト中での既存頻度に基づいて新しいトークンにペナルティを課し、モデルが同じ行をそのまま繰り返す可能性を低減させます。 |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | 完了時に指定トークンが出現する確率を取得または設定します。トークン（トークナイザーでのトークン ID で指定）を -100 から 100 のバイアス値にマッピングする JSON オブジェクトを受け取ります。 |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | 出力トークンの対数確率を返すかどうかを取得または設定します。true の場合、メッセージ内容に含まれる各出力トークンの対数確率を返します。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/completioncreaterequest/maxcompletiontokens/) { get; set; } | 完了時に生成するトークンの最大数を取得または設定します。 |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | これまでの会話を構成するメッセージのリストを取得または設定します。 |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | 使用するモデルの ID を取得または設定します。 |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | 各入力メッセージに対して生成するチャット完了の選択肢数を取得または設定します。選択肢全体で生成されたトークン数に基づいて課金されることに注意してください。コストを最小化するには n を 1 に保ちます。 |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | -2.0 から 2.0 の間の数値を取得または設定します。正の値は、これまでのテキストに出現しているかどうかに基づいて新しいトークンにペナルティを課し、モデルが新しいトピックについて話す可能性を高めます。 |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | モデルが出力しなければならない形式を指定するオブジェクトを取得または設定します。GPT-4 Turbo および gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。 |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | シード値を取得または設定します。この機能はベータ版です。指定した場合、システムは決定的にサンプリングしようと最善を尽くし、同じシードとパラメータでの繰り返しリクエストが同じ結果を返すようにします。ただし、決定性は保証されず、バックエンドの変更を監視するには system_fingerprint 応答パラメータを参照してください。 |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | API がそれ以上トークンを生成しない最大 4 つのシーケンスを取得または設定します。 |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | ストリーミングを使用するかどうかを取得または設定します。設定すると、ChatGPT のように部分的なメッセージ差分が送信されます。トークンは利用可能になり次第データのみのサーバー送信イベントとして送信され、ストリームは data: [DONE] メッセージで終了します。 |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | 使用するサンプリング温度（0 から 2 の範囲）を取得または設定します。0.8 のような高い値は出力をよりランダムにし、0.2 のような低い値はより焦点が合い決定的になります。 |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | モデルが呼び出すツール（存在する場合）を制御するオブジェクトを取得または設定します。none はモデルがツールを呼び出さずメッセージを生成することを意味します。auto はモデルがメッセージ生成または1つ以上のツール呼び出しを選択できることを意味します。required はモデルが1つ以上のツールを必ず呼び出す必要があることを意味します。{"type": "function", "function": {"name": "my_function"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます。ツールが存在しない場合のデフォルトは none です。ツールが存在する場合のデフォルトは auto です。 |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | モデルが呼び出す可能性のあるツールのリストを取得または設定します。現在、ツールとしてサポートされているのは関数のみです。これを使用して、モデルが JSON 入力を生成できる関数のリストを提供します。最大 128 個の関数がサポートされます。 |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | 温度サンプリングの代替手段である nucleus sampling（核サンプリング）を取得または設定します。モデルは top_p 確率質量を持つトークンの結果を考慮します。したがって、0.1 は上位 10% の確率質量を構成するトークンのみが考慮されることを意味します。 |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | エンドユーザーを表す一意の識別子を取得または設定します。これにより OpenAI が濫用を監視・検出するのに役立ちます。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


