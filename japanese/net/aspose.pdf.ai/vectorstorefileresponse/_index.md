---
title: "クラス VectorStoreFileResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.VectorStoreFileResponse クラス。ベクトルストアファイルの応答です。"
type: docs
weight: 1440
url: /ja/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse class

ベクトルストア ファイルのレスポンスです。

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | ベクトルストアファイルが作成された時刻の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | このベクトルストアファイルに関連付けられた最後のエラーを取得または設定します。エラーがない場合は null になります。 |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します。常に vector_store.file です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | ベクトルストアファイルのステータスを取得または設定します。ステータスは in_progress、completed、cancelled、failed のいずれかです。ステータスが completed の場合、ベクトルストアファイルは使用可能であることを示します。 |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | バイト単位でのベクトルストアの総使用量を取得または設定します。これは元のファイルサイズと異なる場合があることに注意してください。 |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | ファイルが添付されているベクトルストアの ID を取得または設定します。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


