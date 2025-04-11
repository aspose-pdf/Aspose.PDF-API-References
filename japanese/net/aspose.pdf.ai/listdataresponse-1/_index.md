---
title: Class ListDataResponseT
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ListDataResponse1T クラス。最初と最後の ID などの追加情報を含むリストデータ応答を表し、さらにアイテムがあるかどうかを示します。
type: docs
weight: 670
url: /ja/net/aspose.pdf.ai/listdataresponse-1/
---
## ListDataResponse&lt;T&gt; クラス

最初と最後の ID などの追加情報を含むリストデータ応答を表し、さらにアイテムがあるかどうかを示します。

```csharp
public class ListDataResponse<T> : DataResponse<T>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ListDataResponse](listdataresponse/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Data](../../aspose.pdf.ai/dataresponse-1/data/) { get; set; } |  |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 応答の詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 応答エラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得します。 |
| [FirstId](../../aspose.pdf.ai/listdataresponse-1/firstid/) { get; set; } | リストの最初の ID を取得または設定します。 |
| [HasMore](../../aspose.pdf.ai/listdataresponse-1/hasmore/) { get; set; } | リストにさらにアイテムがあるかどうかを示す値を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [LastId](../../aspose.pdf.ai/listdataresponse-1/lastid/) { get; set; } | リストの最後の ID を取得または設定します。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラー理由のフレーズを取得します。 |

### 参照

* クラス [DataResponse&lt;T&gt;](../dataresponse-1/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)