---
title: "クラス RunStepResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.RunStepResponse クラス。ランの実行ステップを表します。"
type: docs
weight: 1140
url: /ja/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

実行の実行中のステップを表します。

```csharp
public class RunStepResponse : BaseResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | ランステップに関連付けられたアシスタントの ID を取得または設定します。 |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | ランステップがキャンセルされた時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | ランステップが完了した時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | ランステップが作成された時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | ランステップが期限切れになった時刻の Unix タイムスタンプ（秒）を取得または設定します。親ランが期限切れの場合、ステップも期限切れとみなされます。 |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | 実行ステップが失敗した時刻の Unix タイムスタンプ（秒単位）を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | API エンドポイントで参照できる実行ステップの識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | この実行ステップに関連付けられた最後のエラーを取得または設定します。エラーがない場合は null になります。 |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | オブジェクトの種類を取得または設定します。常に thread.run.step です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | この実行ステップが属する実行の ID を取得または設定します。 |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | 実行ステップのタイプを取得または設定します。message_creation または tool_calls のいずれかです。 |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | 実行ステップのステータスを取得または設定します。in_progress、cancelled、failed、completed、または expired のいずれかです。 |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | 実行ステップの詳細を取得または設定します。 |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | 実行されたスレッドの ID を取得または設定します。 |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | 実行ステップに関連する使用統計情報を取得または設定します。実行ステップのステータスが in_progress の間、この値は null になります。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


