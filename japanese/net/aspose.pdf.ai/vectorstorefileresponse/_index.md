---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileResponse クラス。ベクターストアファイルの応答
type: docs
weight: 1350
url: /ja/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse クラス

ベクターストアファイルの応答です。

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | ベクターストアファイルが作成された時刻のUnixタイムスタンプ（秒単位）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 応答の詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP応答エラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTPステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | APIエンドポイントで参照できる識別子を取得または設定します。 /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | このベクターストアファイルに関連する最後のエラーを取得または設定します。エラーがない場合はnullになります。 |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | 常に vector_store.file であるオブジェクトタイプを取得または設定します。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラー理由のフレーズを取得します。 |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | ベクターストアファイルのステータスを取得または設定します。ステータスは in_progress、completed、cancelled、または failed のいずれかです。completed ステータスは、ベクターストアファイルが使用可能であることを示します。 |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | バイト単位のベクターストアの総使用量を取得または設定します。これは元のファイルサイズとは異なる場合があります。 |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | ファイルが添付されているベクターストアのIDを取得または設定します。 |

### 参照

* クラス [BaseResponse](../baseresponse/)
* インターフェース [IStatus](../istatus/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)