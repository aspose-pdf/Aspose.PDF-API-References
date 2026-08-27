---
title: "クラス FileResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.FileResponse クラス。FileResponse オブジェクトは、OpenAI にアップロードされた document を表します。"
type: docs
weight: 420
url: /ja/net/aspose.pdf.ai/fileresponse/
---
## FileResponse class

FileResponse オブジェクトは、OpenAI にアップロードされたドキュメントを表します。

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FileResponse](fileresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | ファイルのサイズ（バイト単位）を取得または設定します。 |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | ファイルが作成されたときの Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | ファイル名を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | API エンドポイントで参照できるファイル識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | 常に file であるオブジェクトタイプを取得または設定します。 |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | ファイルの意図された目的を取得または設定します。サポートされている値は assistants、assistants_output、batch、batch_output、fine-tune、fine-tune-results、vision です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


