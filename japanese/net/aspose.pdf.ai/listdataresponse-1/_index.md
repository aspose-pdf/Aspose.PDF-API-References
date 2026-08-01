---
title: "クラス ListDataResponseT"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.ListDataResponse1T クラス。最初と最後の ID や追加項目の有無などの追加情報を含むリストデータレスポンスを表します。"
type: docs
weight: 720
url: /ja/net/aspose.pdf.ai/listdataresponse-1/
---
## ListDataResponse&lt;T&gt; class

最初と最後の ID、さらに項目が残っているかどうかなどの追加情報を含むリストデータレスポンスを表します。

```csharp
public class ListDataResponse<T> : DataResponse<T>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ListDataResponse](listdataresponse/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Data](../../aspose.pdf.ai/dataresponse-1/data/) { get; set; } |  |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | レスポンスの詳細を取得または設定します。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP レスポンスエラーを取得または設定します。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | エラー情報を取得または設定します。 |
| [FirstId](../../aspose.pdf.ai/listdataresponse-1/firstid/) { get; set; } | リスト内の最初の ID を取得または設定します。 |
| [HasMore](../../aspose.pdf.ai/listdataresponse-1/hasmore/) { get; set; } | リストにさらに項目があるかどうかを示す値を取得または設定します。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 応答ヘッダーを取得または設定します。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP ステータスコードを取得または設定します。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 応答が成功したかどうかを示します。 |
| [LastId](../../aspose.pdf.ai/listdataresponse-1/lastid/) { get; set; } | リスト内の最後の ID を取得または設定します。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | エラーの理由フレーズを取得します。 |

### 関連項目

* class [DataResponse&lt;T&gt;](../dataresponse-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


