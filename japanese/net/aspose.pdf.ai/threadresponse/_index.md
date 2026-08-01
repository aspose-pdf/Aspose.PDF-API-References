---
title: "クラス ThreadResponse"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.ThreadResponse クラス。メッセージを含むスレッドを表します。"
type: docs
weight: 1270
url: /ja/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse class

メッセージを含むスレッドを表します。

```csharp
public class ThreadResponse : BaseResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ThreadResponse](threadresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | スレッドが作成された時点の Unix タイムスタンプ（秒）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 個のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに便利です。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | オブジェクトのタイプを取得または設定します。これは常に thread です。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | このスレッドでアシスタントのツールに利用可能になるリソースのセットを取得または設定します。リソースはツールの種類に固有です。たとえば、code_interpreter ツールはファイル ID のリストが必要で、file_search ツールはベクトルストア ID のリストが必要です。 |

### 関連項目

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


