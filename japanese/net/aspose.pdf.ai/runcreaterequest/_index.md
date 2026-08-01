---
title: "クラス RunCreateRequest"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "クラス Aspose.Pdf.AI.RunCreateRequest。run の作成リクエストを表します。"
type: docs
weight: 1060
url: /ja/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest class

実行を作成するリクエストを表します。

```csharp
public class RunCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | 追加の指示を取得または設定します。run の指示の末尾に追加の指示を付加します。これは、他の指示を上書きせずに、run ごとに動作を変更するのに便利です。 |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | run を作成する前に、スレッドへの追加メッセージを取得または設定します。 |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | この実行を実行するために使用するアシスタントの ID を取得または設定します。 |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | アシスタントの指示を上書きする指示を取得または設定します。これは実行ごとに動作を変更する際に便利です。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | 実行中に使用できる最大完了トークン数を取得または設定します。実行は、実行の複数ターンにわたって指定された完了トークン数のみを使用するよう最善を尽くします。実行が指定された完了トークン数を超えると、ステータスが incomplete で終了します。詳細は incomplete_details を参照してください。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | 実行中に使用できる最大プロンプトトークン数を取得または設定します。実行は、実行の複数ターンにわたって指定されたプロンプトトークン数のみを使用するよう最善を尽くします。実行が指定されたプロンプトトークン数を超えると、ステータスが incomplete で終了します。詳細は incomplete_details を参照してください。 |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | この実行を実行するために使用されるモデルの ID を取得または設定します。ここに値を指定すると、アシスタントに関連付けられたモデルを上書きします。指定しない場合は、アシスタントに関連付けられたモデルが使用されます。 |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | レスポンス形式を取得または設定します。モデルが出力しなければならない形式を指定します。GPT-4o、GPT-4 Turbo、そして gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ \"type\": \"json_object\" } に設定すると JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合、システムメッセージまたはユーザーメッセージでモデルに JSON を生成するよう指示する必要があります。これを行わないと、モデルはトークン上限に達するまで空白のストリームを無限に生成し続け、長時間実行され「スタック」したように見えるリクエストになる可能性があります。また、finish_reason=\"length\" の場合、生成が max_tokens を超えた、または会話が最大コンテキスト長を超えたことを示し、メッセージ内容が部分的に切り取られることがあります。 |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | ストリーミングを使用するかどうかを取得または設定します。true の場合、実行中に発生するイベントのストリームをサーバー送信イベントとして返し、実行がターミナル状態に入り data: [DONE] メッセージで終了します。 |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | 使用するサンプリング温度（0 から 2 の範囲）を取得または設定します。0.8 のような高い値は出力をよりランダムにし、0.2 のような低い値はより焦点が合い決定的になります。 |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | モデルが呼び出すツール（存在する場合）を取得または設定します。none はモデルがツールを呼び出さずメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージ生成または1つ以上のツール呼び出しのいずれかを選択できることを意味します。required はモデルがユーザーに応答する前に1つ以上のツールを必ず呼び出さなければならないことを意味します。{\"type\": \"file_search\"} や {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます。 |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | この実行でアシスタントが使用できるツールを上書きするツールを取得または設定します。実行ごとに動作を変更するのに便利です。 |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | 温度によるサンプリングの代替として、トップ確率質量 top_p を考慮する nucleus sampling と呼ばれる手法を取得または設定します。たとえば 0.1 は上位 10% の確率質量を占めるトークンのみが考慮されることを意味します。通常、temperature とこの設定は同時に変更せず、どちらか一方を調整することを推奨します。 |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | 切り捨て戦略を取得または設定します。run の前にスレッドがどのように切り捨てられるかを制御します。これを使用して、run の初期コンテキストウィンドウを制御します。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


