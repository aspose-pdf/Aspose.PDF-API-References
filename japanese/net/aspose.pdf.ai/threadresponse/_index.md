---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadResponse クラス。メッセージを含むスレッドを表します
type: docs
weight: 1180
url: /ja/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse クラス

メッセージを含むスレッドを表します。

```csharp
public class ThreadResponse : BaseResponse
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ThreadResponse](threadresponse/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | スレッドが作成された時刻の Unix タイムスタンプ（秒単位）を取得または設定します。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP レスポンスヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | API エンドポイントで参照できる識別子を取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | レスポンスが成功したかどうかを示します。 |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | オブジェクトに添付できる 16 のキーと値のペアのセットを取得または設定します。これは、オブジェクトに関する追加情報を構造化された形式で保存するのに役立ちます。キーは最大 64 文字、値は最大 512 文字までです。 |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | 常にスレッドであるオブジェクトタイプを取得または設定します。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラー理由フレーズを取得します。 |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | このスレッド内のアシスタントのツールに提供されるリソースのセットを取得または設定します。リソースはツールの種類に特有です。たとえば、code_interpreter ツールはファイル ID のリストを必要とし、file_search ツールはベクターストア ID のリストを必要とします。 |

### 参照

* クラス [BaseResponse](../baseresponse/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)