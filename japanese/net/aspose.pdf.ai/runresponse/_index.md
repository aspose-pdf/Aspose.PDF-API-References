---
title: "クラス RunResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.RunResponse クラス。スレッド上の実行ランを表します"
type: docs
weight: 1100
url: /ja/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

スレッド上の実行ランを表します。

```csharp
public class RunResponse : BaseResponse, IStatus
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunResponse](runresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | この実行に使用されるアシスタントの ID を取得または設定します。 |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | 実行がキャンセルされた時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | 実行が完了した時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | 実行が作成された時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | 実行が期限切れになる時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | 実行が失敗した時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | 実行が未完了である理由の詳細を取得または設定します。実行が未完了でない場合は null になります。 |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | この実行でアシスタントが使用した指示を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | この実行に関連付けられた最後のエラーを取得または設定します。エラーがない場合は null になります。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | 実行中に使用されたと指定された完了トークンの最大数を取得または設定します。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | 実行中に使用されたと指定されたプロンプトトークンの最大数を取得または設定します。 |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | この実行でアシスタントが使用したモデルを取得または設定します。 |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します。これは常に thread.run です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | 実行を継続するために必要なアクションの詳細を取得または設定します。アクションが不要な場合は null になります。 |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | モデルが出力しなければならない形式を取得または設定します。GPT-4o、GPT-4 Turbo、そして gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ \"type\": \"json_object\" } に設定すると JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合、システムメッセージまたはユーザーメッセージでモデルに JSON を生成するよう指示する必要があります。これを行わないと、モデルはトークン上限に達するまで空白のストリームを無限に生成し続け、長時間実行され「スタック」したように見えるリクエストになる可能性があります。また、finish_reason=\"length\" の場合、メッセージ内容が一部切り捨てられることがあります。これは生成が max_tokens を超えた、または会話が最大コンテキスト長を超えたことを示します。 |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | 実行が開始された時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | 実行のステータスを取得または設定します。ステータスは queued、in_progress、requires_action、cancelling、cancelled、failed、completed、incomplete、または expired のいずれかです。 |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | この実行で使用されるサンプリング温度を取得または設定します。設定しない場合、デフォルトは 1 です。 |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | この実行の一部として実行されたスレッドの ID を取得または設定します。 |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | モデルが呼び出すツール（存在する場合）を取得または設定します。none はモデルがツールを呼び出さずメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージ生成または1つ以上のツール呼び出しのいずれかを選択できることを意味します。required はモデルがユーザーに応答する前に1つ以上のツールを必ず呼び出さなければならないことを意味します。{\"type\": \"file_search\"} や {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すよう強制されます。 |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | この実行でアシスタントが使用したツールの一覧を取得または設定します。 |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | この実行で使用される nucleus サンプリング値を取得または設定します。設定しない場合、デフォルトは 1 です。 |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | 実行前にスレッドがどのように切り詰められるかを制御するトランケーション戦略を取得または設定します。これを使用して実行の初期コンテキストウィンドウを制御します。 |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | 実行に関連する使用統計情報を取得または設定します。実行が終了状態でない場合（例：in_progress、queued など）、この値は null になります。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


