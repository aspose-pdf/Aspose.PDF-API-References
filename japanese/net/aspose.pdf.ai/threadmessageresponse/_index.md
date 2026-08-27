---
title: "クラス ThreadMessageResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.ThreadMessageResponse クラス。スレッド内のメッセージを表します"
type: docs
weight: 1250
url: /ja/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

スレッド内のメッセージを表します。

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | 該当する場合、このメッセージを作成したアシスタントの ID を取得または設定します。 |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | メッセージに添付されたファイルのリストを取得または設定します。 |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | メッセージが完了した時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | メッセージの内容をテキストおよび/または画像の配列として取得または設定します。 |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | メッセージが作成された時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | メッセージが未完了としてマークされた時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | 未完了メッセージと、その未完了の理由に関する詳細を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します。常に "thread.message" です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | メッセージを生成したエンティティを取得または設定します。"user" または "assistant" のいずれかです。 |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | このメッセージの作成に関連付けられたランの ID を取得または設定します。メッセージが手動で作成された場合、値は null です。 |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | メッセージのステータスを取得または設定します。queued、in_progress、requires_action、completed のいずれかです。 |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | このメッセージが属するスレッドの ID を取得または設定します。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


