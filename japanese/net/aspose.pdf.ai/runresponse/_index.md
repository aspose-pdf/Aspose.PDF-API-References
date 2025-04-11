---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunResponse クラス。スレッド上での実行ランを表します
type: docs
weight: 1020
url: /ja/net/aspose.pdf.ai/runresponse/
---
## RunResponse クラス

スレッド上での実行ランを表します。

```csharp
public class RunResponse : BaseResponse, IStatus
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunResponse](runresponse/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | このランの実行に使用されたアシスタントの ID を取得または設定します。 |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | ランがキャンセルされた時の Unix タイムスタンプ（秒）を取得または設定します。 |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | ランが完了した時の Unix タイムスタンプ（秒）を取得または設定します。 |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | ランが作成された時の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | ランが期限切れになる時の Unix タイムスタンプ（秒）を取得または設定します。 |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | ランが失敗した時の Unix タイムスタンプ（秒）を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP レスポンスヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | ランが不完全である理由の詳細を取得または設定します。ランが不完全でない場合は null になります。 |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | このランのためにアシスタントが使用した指示を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | レスポンスが成功したかどうかを示します。 |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | このランに関連する最後のエラーを取得または設定します。エラーがない場合は null になります。 |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | ランの過程で使用された最大の完了トークン数を取得または設定します。 |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | ランの過程で使用された最大のプロンプトトークン数を取得または設定します。 |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに役立ちます。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | このランのためにアシスタントが使用したモデルを取得または設定します。 |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | 常に thread.run であるオブジェクトタイプを取得または設定します。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラー理由のフレーズを取得します。 |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | ランを続行するために必要なアクションの詳細を取得または設定します。アクションが必要ない場合は null になります。 |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | モデルが出力する必要があるフォーマットを取得または設定します。GPT-4o、GPT-4 Turbo、および gpt-3.5-turbo-1106 以降のすべての GPT-3.5 Turbo モデルと互換性があります。{ "type": "json_object" } に設定すると、JSON モードが有効になり、モデルが生成するメッセージが有効な JSON であることが保証されます。重要: JSON モードを使用する場合、システムまたはユーザーメッセージを介してモデルに JSON を生成するよう指示する必要があります。これがないと、モデルはトークン制限に達するまで空白のストリームを生成し続け、長時間実行されているように見える「スタック」したリクエストになります。また、finish_reason="length" の場合、メッセージの内容が部分的に切り取られる可能性があることに注意してください。これは、生成が max_tokens を超えたか、会話が最大コンテキスト長を超えたことを示します。 |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | ランが開始された時の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | ランのステータスを取得または設定します。ステータスは queued、in_progress、requires_action、cancelling、cancelled、failed、completed、incomplete、または expired のいずれかです。 |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | このランに使用されたサンプリング温度を取得または設定します。設定されていない場合は、デフォルトで 1 になります。 |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | このランの一部として実行されたスレッドの ID を取得または設定します。 |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | モデルによって呼び出されるツール（ある場合）を取得または設定します。none はモデルがツールを呼び出さず、代わりにメッセージを生成することを意味します。auto はデフォルト値で、モデルがメッセージを生成するか、1 つ以上のツールを呼び出すかを選択できることを意味します。required はモデルがユーザーに応答する前に 1 つ以上のツールを呼び出す必要があることを意味します。{"type": "file_search"} や {"type": "function", "function": {"name": "my_function"}} のように特定のツールを指定すると、モデルはそのツールを呼び出すことになります。 |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | このランのためにアシスタントが使用したツールのリストを取得または設定します。 |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | このランに使用された核サンプリング値を取得または設定します。設定されていない場合は、デフォルトで 1 になります。 |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | ランの前にスレッドがどのように切り捨てられるかを制御する切り捨て戦略を取得または設定します。これを使用して、ランの初期コンテキストウィンドウを制御します。 |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | ランに関連する使用統計を取得または設定します。この値は、ランが端末状態（つまり、in_progress、queued など）でない場合は null になります。 |

### 参照

* クラス [BaseResponse](../baseresponse/)
* インターフェース [IStatus](../istatus/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)