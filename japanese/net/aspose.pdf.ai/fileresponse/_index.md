---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.FileResponse クラス。FileResponse オブジェクトは、OpenAI にアップロードされたドキュメントを表します。
type: docs
weight: 400
url: /ja/net/aspose.pdf.ai/fileresponse/
---
## FileResponse クラス

FileResponse オブジェクトは、OpenAI にアップロードされたドキュメントを表します。

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FileResponse](fileresponse/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | ファイルのサイズ（バイト単位）を取得または設定します。 |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | ファイルが作成された時刻の Unix タイムスタンプ（秒単位）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得します。 |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | ファイルの名前を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP レスポンスヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | API エンドポイントで参照できるファイル識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | レスポンスが成功したかどうかを示します。 |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | 常にファイルであるオブジェクトタイプを取得または設定します。 |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | ファイルの意図された目的を取得または設定します。サポートされている値は、assistants、assistants_output、batch、batch_output、fine-tune、fine-tune-results、vision です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラー理由フレーズを取得します。 |

### 参照

* クラス [BaseResponse](../baseresponse/)
* インターフェース [IEntityId](../ientityid/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)