---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepResponse クラス。実行のステップを表します
type: docs
weight: 1060
url: /ja/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse クラス

実行のステップを表します。

```csharp
public class RunStepResponse : BaseResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | 実行ステップに関連付けられたアシスタントのIDを取得または設定します。 |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | 実行ステップがキャンセルされた時のUnixタイムスタンプ（秒）を取得または設定します。 |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | 実行ステップが完了した時のUnixタイムスタンプ（秒）を取得または設定します。 |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | 実行ステップが作成された時のUnixタイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTPレスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | 実行ステップが期限切れになった時のUnixタイムスタンプ（秒）を取得または設定します。親の実行が期限切れの場合、ステップは期限切れと見なされます。 |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | 実行ステップが失敗した時のUnixタイムスタンプ（秒）を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTPレスポンスヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTPステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | APIエンドポイントで参照できる実行ステップの識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | レスポンスが成功したかどうかを示します。 |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | この実行ステップに関連する最後のエラーを取得または設定します。エラーがない場合はnullになります。 |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | オブジェクトに添付できる16のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに役立ちます。キーは最大64文字、値は最大512文字までです。 |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | オブジェクトタイプを取得または設定します。これは常にthread.run.stepです。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラー理由のフレーズを取得します。 |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | この実行ステップが属する実行のIDを取得または設定します。 |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | 実行ステップのタイプを取得または設定します。これはmessage_creationまたはtool_callsのいずれかです。 |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | 実行ステップのステータスを取得または設定します。これはin_progress、cancelled、failed、completed、またはexpiredのいずれかです。 |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | 実行ステップの詳細を取得または設定します。 |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | 実行されたスレッドのIDを取得または設定します。 |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | 実行ステップに関連する使用統計を取得または設定します。この値は、実行ステップのステータスがin_progressの間はnullになります。 |

### 参照

* クラス [BaseResponse](../baseresponse/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)