---
title: "クラス VectorStoreResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.VectorStoreResponse クラス。ベクトルストア オブジェクトです。"
type: docs
weight: 1480
url: /ja/net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse class

ベクトルストアオブジェクトです。

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | ベクトルストアが作成されたときの Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | ベクトルストアの有効期限ポリシーを取得または設定します。 |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | ベクトルストアが期限切れになるときの Unix タイムスタンプ（秒）を取得または設定します。 |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | 処理されたファイル数を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | ベクトルストアが最後にアクティブだったときの Unix タイムスタンプ（秒）を取得または設定します。 |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | ベクトルストアの名前を取得または設定します。 |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します（常に vector_store です）。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | ベクトルストアのステータスを取得または設定します。ステータスは expired、in_progress、completed のいずれかです。completed のステータスはベクトルストアが使用可能であることを示します。 |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | ベクトルストア内のファイルが使用する合計バイト数を取得または設定します。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


