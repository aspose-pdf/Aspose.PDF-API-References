---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreResponse クラス。ベクターストアオブジェクト
type: docs
weight: 1390
url: /ja/net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse クラス

ベクターストアオブジェクト。

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | ベクターストアが作成された時の Unix タイムスタンプ（秒単位）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | ベクターストアの有効期限ポリシーを取得または設定します。 |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | ベクターストアが期限切れになる時の Unix タイムスタンプ（秒単位）を取得または設定します。 |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | 処理されたファイルの数を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP レスポンスヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | レスポンスが成功したかどうかを示します。 |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | ベクターストアが最後にアクティブだった時の Unix タイムスタンプ（秒単位）を取得または設定します。 |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに役立ちます。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | ベクターストアの名前を取得または設定します。 |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | オブジェクトタイプを取得または設定します。これは常に vector_store です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラー理由フレーズを取得します。 |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | ベクターストアのステータスを取得または設定します。ステータスは expired、in_progress、または completed のいずれかです。completed のステータスは、ベクターストアが使用可能であることを示します。 |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | ベクターストア内のファイルによって使用されるバイトの総数を取得または設定します。 |

### 参照

* クラス [BaseResponse](../baseresponse/)
* インターフェース [IEntityId](../ientityid/)
* インターフェース [IStatus](../istatus/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)