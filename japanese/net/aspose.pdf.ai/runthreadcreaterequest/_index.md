---
title: "クラス RunThreadCreateRequest"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.RunThreadCreateRequest クラス。スレッドを作成し、1 回のリクエストで実行する要求を表します。"
type: docs
weight: 1150
url: /ja/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest class

スレッドを作成し、1 回のリクエストで実行するリクエストを表します。

```csharp
public class RunThreadCreateRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | この実行を実行するために使用するアシスタントの ID を取得または設定します。 |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | アシスタントの指示を上書きする指示を取得または設定します。これは実行ごとに動作を変更する際に便利です。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | 実行中に使用できる最大完了トークン数を取得または設定します。実行は、実行の複数ターンにわたって指定された完了トークン数のみを使用するよう最善を尽くします。実行が指定された完了トークン数を超えると、ステータスが incomplete で終了します。詳細は incomplete_details を参照してください。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | 実行中に使用できる最大プロンプトトークン数を取得または設定します。実行は、実行の複数ターンにわたって指定されたプロンプトトークン数のみを使用するよう最善を尽くします。実行が指定されたプロンプトトークン数を超えると、ステータスが incomplete で終了します。詳細は incomplete_details を参照してください。 |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | オブジェクトに添付できる最大16個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大64文字、値は最大512文字までです。 |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | この実行を実行するために使用されるモデルの ID を取得または設定します。ここに値を指定すると、アシスタントに関連付けられたモデルを上書きします。指定しない場合は、アシスタントに関連付けられたモデルが使用されます。 |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | モデルが出力しなければならない形式を取得または設定します。GPT-4o、GPT-4 Turbo、そして gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ \"type\": \"json_object\" } に設定すると JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合、システムメッセージまたはユーザーメッセージでモデルに JSON を生成するよう指示する必要があります。これを行わないと、モデルはトークン上限に達するまで空白のストリームを無限に生成し続け、長時間実行され「スタック」したように見えるリクエストになる可能性があります。また、finish_reason=\"length\" の場合、メッセージ内容が一部切り捨てられることがあります。これは生成が max_tokens を超えた、または会話が最大コンテキスト長を超えたことを示します。 |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | ストリーミングを使用するかどうかを取得または設定します。true の場合、実行中に発生するイベントのストリームをサーバー送信イベントとして返し、実行がターミナル状態に入り data: [DONE] メッセージで終了します。 |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | 使用するサンプリング温度（0 から 2 の範囲）を取得または設定します。0.8 のような高い値は出力をよりランダムにし、0.2 のような低い値はより焦点が合い決定的になります。 |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | スレッド作成のリクエストを取得または設定します。 |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | モデルが呼び出すツール（存在する場合）を取得または設定します。none はモデルがツールを呼び出さずメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージ生成または1つ以上のツール呼び出しのいずれかを選択できることを意味します。required はモデルがユーザーに応答する前に1つ以上のツールを必ず呼び出さなければならないことを意味します。{\"type\": \"file_search\"} や {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます。 |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | アシスタントのツールで使用されるリソースのセットを取得または設定します。 |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | この実行でアシスタントが使用できるツールを上書きするツールを取得または設定します。実行ごとに動作を変更するのに便利です。 |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | 温度サンプリングの代替である nucleus sampling の値を取得または設定します。モデルは top_p 確率質量のトークン結果を考慮します。たとえば 0.1 は上位 10% の確率質量を持つトークンのみが対象となります。通常、temperature とこの値はどちらか一方だけ変更することを推奨します。 |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | 実行前にスレッドがどのように切り詰められるかを制御するトランケーション戦略を取得または設定します。これを使用して実行の初期コンテキストウィンドウを制御します。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


